layout: true

.signature[@algogrit]

---
class: center, middle

# Why Go

Gaurav Agarwal

---

# Agenda

* GO IS AWESOME!

---

class: center, middle

![Me](assets/images/me.png)

Software Engineer & Product Developer

Principal Consultant & Founder @ https://agarwalconsulting.io

ex-Tarka Labs, ex-BrowserStack, ex-ThoughtWorks

---
class: center, middle

```golang
package main

import "fmt"

func main() {
  fmt.Println("Hello, world!")
}
```

---

class: center, middle

Co-organizer of Chennai Go meetup
Volunteer at Golang India - Remote study group

---

# Go

* simple, concurrent language
* Born @ Google
* Sub-millisecond response times!!!
* Cross-compilation
* Goroutines & channels
* Go Toolchain
* Binaries!

---
class: center, middle

# Go's programming style

---

* Syntax is close to C
* Simplicity over complexity
* Concurrency over parallelism
* Neither Object-oriented nor functional in nature
* Statically typed, type inferred language
* Others

---
class: center, middle

## Syntax is close to C

---

```go
import "fmt"
```

```go
func main() {
  //
}
```

```go
var aNumber int = 42
```

```go
fmt.Printf("%d", aNumber)
```

---
class: center, middle

## Simplicity over complexity

---

```go
for i := 0; i < 10; i++ {
  //
}
```

---
class: center, middle

## Concurrency over parallelism

---
class: center, middle

Concurrency is the composition of independently executing processes, while parallelism is the simultaneous execution of (possibly related) computations.

.content-credits[https://blog.golang.org/concurrency-is-not-parallelism]

---
class: center, middle

## Neither Object-oriented nor functional in nature

---

* No classes *(it does have `structs`)*
* functions can return functions
* Lack of generics
* No map/reduce/fold etc.
  * *Though you could implement them yourselves*
* No inheritance

---
class: center, middle

## Binaries

---
class: center, middle

Automation and Command-line tools - Go is also a great tool to make complex automation tools for developers. It fast, lightweight and follows unix “Do one thing. And do it well.”. DevOps is beginning to use more and more golang.

---
class: center, middle

## *Others*

---

* Pointers (with Memory-safety!)
* `struct` with receiver functions
* Implicit `interface`s
* `slices`
* `channels`
* `goroutines`
* [Garbage collector](https://blog.golang.org/ismmkeynote)
* Comprehensive standard library...
* and great documentation to go along with it!

---
class: center, middle

Code
https://github.com/algogrit/presentation-why-go

Slides
https://why-go.slides.algogrit.com
