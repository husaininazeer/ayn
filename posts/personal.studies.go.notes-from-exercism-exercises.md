---
title: Notes from Excersim
author: huscous
---

## How to write a function in Go?

```go
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
- the type of each parameter / input is stated, and likewise the type of
  output

## How to initialise variables?

```go
// explicitly stating the type:
var someVariable int

// implicitly inferring the type (the compiler will do it for you)
someOtherVariable := 10 // type will be int

// variable's value can be changed, but not its type
someOtherVariable = 20 // works
someOtherVariable = 'a string' // does NOT work

```

## How to initialise constants?

```go
// constants can NOT change their value
const aNumber = 30 

```


