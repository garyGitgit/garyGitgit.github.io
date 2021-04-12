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
Nginx is one of the most popular web server. Apache was the top web server, but as of 2019, Nginx has become the top web server.

# Gunicorn
- running on Unix
- WSGI implementation in Python
- details: https://docs.gunicorn.org/en/stable/design.html 

##### References
1. *https://sgc109.github.io/2020/08/15/python-wsgi/*
2. *https://www.ibm.com/cloud/learn/web-server-vs-application-server*
3. *https://sieunlim.tistory.com/17*

<style>
body{
  font-family: 'Roboto', sans-serif;
}
</style>


