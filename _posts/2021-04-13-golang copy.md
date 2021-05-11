---
title: What is Go Lang?
tags: [Golang]
style: fill
color: warning
description: Learn about Go Lang.
<!-- external_url: https://blog.usejournal.com/how-to-undo-your-git-failure-b76e31ecac74 -->
---
Still writing...<br/>
<i> Reference: [Learn Go Programming - Golang Tutorial for Beginners](https://www.youtube.com/watch?v=YS4e4q9oBaU&t=3193s&ab_channel=freeCodeCamp.org) </i>

## Overview
Golang was made by Google to take some of features that other languages, such as Java, C++ and Python, don't have. <br/>
- See [official website](https://golang.org/).
- See [community](https://golang.org/conduct).

## Features
- Simplicity
- Fast compile time
- Garbage collected
- Built-in concurrency
- Compile to standalone binaries

#### Simplicity
Go doesn't have various kind of code styles. For example, in Java, it has various kinds of iteration: for loop, while loop, do while ... On contrary, Go has only one iteration: for statement.

#### Fast compile time
Traditional languages, such as C and C++, are compiled by GCC compiler, which have relatively low compile time. However, Go doesn't. It has faster compile time. 

#### Garbage collected
Traditional languages, such as Java, have Garbage Collection (GC) function to manage memory resources. This function sometimes make the program slow. However, Go has fast GC function, and it makes users unaware of GC while running programs.

#### Built-in concurrency
One of the powerful function of Go is concurrency. As a number of programs require concurrency functions, Go supports built-in concurrency function (go routine), enabling developers to easily work on concurrency programming.

#### Compile to standalone binaries


## Applications

- Web framework (backend): echo, gin ...
- Blockchain: Ethereum
- Prometheus exporter: mongodb exporter, oracle exporter, node exporter ...

## Basics
*Reference: [How to write go code](https://golang.org/doc/code), [Tutorial Point / Go](https://www.tutorialspoint.com/go)*

##### Data types
Go is a statically-typed (strict type) language.
```
```

##### Variables
###### Declaration
```go
// types: int, float32, string ...
var variable_name variable_type; # semicolon (;) is optional
var v1, v2, v3 variable_type;
```
###### Assignment
```go
var v1, v2, v3 int
v1 = 1
v2 = 2
v3 = 3

// dynamic type declaration / type inference in Go
v4 := 4 
```

##### Control Flow

###### if statement
```go
if (condition) { ...}
```

###### for statement
```go
// no parentheses () is allowed
for condition {...}
```

```go
package main

import (
	"fmt"
)

func main(){
	//fmt.Printf("hello world\n")
	var a, b int
	var fa, fb float32
	var str string = "hello world"

	a = 1
	b = 2
	fa = 1.0
	fb = 2.0
	c := 0.99
	fmt.Printf("20210414", str)
	if (a < b) {
		fmt.Printf ("%d is larger than %d\n", b, a)
	}

	if (fa > fb) {
		fmt.Printf ("%d is smaller than %.2f\n", b, a)
	}

	for i := 1 ; i < 5; i++ {
		fmt.Printf("%d th print\n")
		fmt.Printf("%d + %d = %d\n", a,b,a+b)
		fmt.Printf("%.2f - %.2f = %.2f\n", fa, fb, fa-fb)
	}
	// %d covers all variable types
	fmt.Printf("%d is a value of c variable.\n", c)
}

```

##### Development Environment

###### Some useful commands
```csh
$ go mod init
$ go mod tidy
$ go get github_url(/...)
$ go run your_file.go
$ go build your_file.go
$ go test (require testing package and testing file)
```
###### How to install external packages?
If the current go doesn't include external packages required by your go file, it will generate errors like this:
```csh
$ go run main.go
main.go:5:2: no required module provides package github.com/labstack/echo/v4; to add it:
	go get github.com/labstack/echo/v4

$ go get github.com/labstack/echo/v4
```

###### How to manage package dependencies to avoid conflicts?
go.mod file is a file that manages package dependencies in your go code. The file includes go version and version for each package. go.sum file is a file that 
```csh
$ go mod init main # find imported packages in package (main is an example. you should input your go file)
$ go mod tidy      # install missing packages and remove unnecessary packages
```

###### How to make testing file?

```go
//main.go
package hello

func Hello() string {
    return "Hello, world"
}
```
```go
// test.go
package hello

import (
	"fmt"
	"testing"
)

func TestHello(t *testing.T) {
	want := "Hello, world"
	fmt.Println(want)
	if got := Hello(); got != want {
		t.Errorf("Hello() = %q, want %q", got, want)
	}
}
```

###### Some tips
- main package (package main) must exist to run ```go run your_file.go ```


<br/><br/>
<hr>
<br/>

##### References
1. *https://soyoung-new-challenge.tistory.com/130*

<style>
body{
  font-family: 'Roboto', sans-serif;
}
</style>
