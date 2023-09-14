---
title: Notes from Excersim
author: huscous
created: 2023-08-24 10:52
tags: [go, programming, notes]
---

## How to write a function in Go?

``` go
function PublicFunction(functionIput int) string {
    return "A public function was called"
}

// a private function
function privateFunction(functionInput int) string {
    return "A private function was called"
}
```

  - functions named in `PascalCase` are public, `camelCase` ones are
    private
  - the type of each parameter / input is stated, and likewise the type
    of output

## How to initialise variables?

``` go
// explicitly stating the type:
var someVariable int

// implicitly inferring the type (the compiler will do it for you)
someOtherVariable := 10 // type will be int

// variable's value can be changed, but not its type
someOtherVariable = 20 // works
someOtherVariable = 'a string' // does NOT work
```

## How to initialise constants?

``` go
// constants can NOT change their value
const aNumber = 30
```

## What are the different types of comments you can have in Go?

``` go
// n.b. apparently 'go doc [command]' function can extract all of the
comments to make documentation about Go.

// 1. Package comments

// Package somepackage does something that is useful
package somepackage

// 2.  Function comments

// SomeFunction takes in no values and returns an int of 0.
function SomeFunction() int {
  return 0
}

// 3.  (package-level) Variable comments

// BookName is a string that represents a name of a book.
var BookName
string
```

