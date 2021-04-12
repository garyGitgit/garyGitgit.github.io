---
title: What is Gunicorn and Nginx?
tags: [Gunicorn, Nginx]
style: fill
color: primary
description: Gunicorn is a WSGI implementation in Python, and Nginx is a web server, such as Apache.
---
Still writing...<br/>
## Overview
Gunicorn is a WSGI implementation in Python, and Nginx is a web server, such as Apache. Both are essential components when developing web server applications. When developing server applications in various languages and frameworks, such as (Python-Django,Flask), (Javascript-Node.js), (Java-Spring), we should deploy server application as a service. Gunicorn and Nginx is one of tech stacks to deploy server applications. 
<br/><br/>
To understand each component, first, we should understand WSGI and web server.

## What is Web server and WSGI?
1. Web server is a server providing static files, such as html, css, js and image files, on clients' requests. Apache and Nginx is the most widely used web servers. To understand web server, we should understand web application as well. As the early stage web servers only served static files and complex logics were needed, web application, which processes business logic, was required. For each progmaming languages, Spring for Java, Flask and Django for Python have been developed to support such needs. As those diffrent kinds of web application had to be compatible with different kinds of web servers, a standard interface was required. **CGI (Common Gateway Interface)** was it.

2. Simply, CGI received HTTP request from web server, transferred request components, such as URL, method and parameters, in environment variables and executed business logic script. The stdout result was transferred back to the web server. The problem of CGI was each execution of script required memory loading, and it was too slow. Even if CGI had the problem, it was widely used for its compatibility for various languages. To solve this problem, **WSGI (Web Server Gateway Interface)**  has been released.

3. WSGI trasnfers HTTP request to web application via **Callable object**. This object includes HTTP request components and callback function. The callback function is used for returning result to the web server.

# What is Nginx?
1. Nginx is one of the most popular web server. Apache was the top web server, but as of 2019, Nginx has become the top web server. Both Apache and Nginx are commonly used to handle static files, such as html, css, js, images and videos. However both web servers have different mechanisms: Apache creates thread for each connection, on the other hand, Nginx doesn't. **As Nginx is event-driven way, it doesn't require thread creation for each connection, meaning it uses lower resource than Apache**. This can solve **C10K problem** that Apache has. C10K problem is a problem that when Apache web server cannot handle over 10,000 connections concurrently.

2. Nginx also has another feature: **reverse proxy**. To understand reverse proxy, we should understand proxy server first. Proxy server is mostly used to communicate users: for example, my company doesn't allow direct Internet access for security reason, and only via proxy server, internal employees could access to Internet. On the ohter hand, reverse proxy is located on a server side, not a user side. This means that a server returns requests via reverse proxy server. In sum, the main difference of (forward) proxy server and reverse proxy server is where the proxy server is located: forward proxy is located in front of uesrs and reverse proxy is located in front of servers. This kind of mechaism is good for protecting WAS (Web Application Server), which directly connects to internal databases, from external attacks. 

3. Another advantage of reverse proxy is that **load balancing** is available. As Nginx is a reverse proxy, it can do load balancing as well.

# What is Gunicorn?
Gunicorn is **Python implementation of WSGI for Unix system**. Gunicorn consists of master thread and worker thread. Worker threads handles each request, and the recommended number of workers, according to the official guide, is 2x(num of cores) + 1.

# How does Nginx, Gunicorn and Django work?
As mentioned above, Nginx is a web server which is located at the very front of servers. It receives HTTP requests from outside. And Gunicorn is used as CGI to transfer HTTP requests to WAS. Django, used as WAS, is a framework that enables server programing easier with MVC (Model, View, Design) Pattern. In developers' view, they don't have to worry web server side or WSGI implementation because both Nginx and Gunicorn work instead.
<br/>
<br/>
<hr>
<br/>

##### References
1. *https://sgc109.github.io/2020/08/15/python-wsgi/*
2. *https://www.ibm.com/cloud/learn/web-server-vs-application-server*
3. *https://sieunlim.tistory.com/17*
4. *https://m.blog.naver.com/jhc9639/220967352282*

<style>
body{
  font-family: 'Roboto', sans-serif;
}
</style>


