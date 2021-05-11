---
title: What is Blockchain?
tags: [Blockchain]
style: fill
color: primary 
description: Learn about blockchain.
---
Still writing...<br/>
<i> Reference:  </i>

## Overview
Blockchain is one of the most interesting technologies in these days. Bitcoin and Ethereum are the most successful blockchain use case, and other Altcoins (minor coins) are following the major coins. The market size of coins, also known as virtual assets, cryptocurrency, virtual currency, has already excceeded ones of the legacy stock market. There are also fake coins, called SCAM, in the market. To understand why blockchain technology is hot and to avoid SCAM, we should understand the background and go deep into the technology.

## Terminology
- Blockchain
- DLT (Distributed Ledger Technology)
- Genesis block
- Computer Science: Hash, Linked List, SHA 256
- Two general problems
- Byzantine problems
- Consensus algorithm

#### 1

#### 2

#### 3

#### 4

#### 5


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
