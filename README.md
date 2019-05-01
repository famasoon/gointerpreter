gointerpreter
===

## Overview
I learned how to implement program language in the following book.
And I implemented an interpreter for `monkey` language by Golang.
* English [Writing An Interpreter In Go](https://interpreterbook.com/)
* Japanese [Go言語でつくるインタプリタ](https://www.oreilly.co.jp/books/9784873118222/)

## What is monkey language
monkey language supports following features and types
* C like syntax
* Variable bindings
* Data types: booleans, strings, hashes, integers and arrays
* Some builtin functions
* Higher-order functions
* Closures

## Usage
Use the following command.

```sh
$ git clone https://github.com/famasoon/gointerpreter
$ cd gointerpreter
$ go run main.go
```

## TODO
* [ ] Support macro system
