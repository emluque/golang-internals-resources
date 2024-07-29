# Golang Internals Resources

This is a curated collection of Articles and Videos about Golang internals. It is intended for advanced/intermediate programmers who are new to Golang and want to understand what happens under the hood. Feel free to add to it!

## Data Structures and Data Types

### Nil
[Understanding Nil](https://www.youtube.com/watch?v=ynoY2xz-F8s) Talk by Francesc Campoy

### Slices
[Go Slices: usage and internals](https://blog.golang.org/go-slices-usage-and-internals) from The Go Blog

### Structs
[The empty struct](https://dave.cheney.net/2014/03/25/the-empty-struct) by Dave Chevney

### Maps
[Macro View of Map Internals In Go](https://www.goinggo.net/2013/12/macro-view-of-map-internals-in-go.html) by William Kennedy

[Inside the Map Implementation](https://youtu.be/Tl7mi9QmLns) Talk by Keith Randall

[How the Go runtime implements maps efficiently (without generics)](https://dave.cheney.net/2018/05/29/how-the-go-runtime-implements-maps-efficiently-without-generics) by Dave Cheney

### Interfaces
[Go Data Structures: Interfaces](https://research.swtch.com/interfaces) by Russ Cox

[Golang concepts from an OOP point of view](https://github.com/luciotato/golang-notes/blob/master/OOP.md) by Lucio Tato

[Understanding Go Interfaces](https://www.youtube.com/watch?v=F4wUrj6pmSI) Talk by Francesc Campoy

### Hacking the Golang Type System
[Hacking Go's type system](https://katcipis.github.io/blog/hack-go-types/) by Tiago Katcipis

## Go 1.18 Generics
[Go 1.18 Implementation of Generics via Dictionaries and Gcshape Stenciling](https://github.com/golang/proposal/blob/master/design/generics-implementation-dictionaries-go1.18.md)

## Concurrency Primitives

### Goroutines
[How Goroutines Work](https://nindalf.com/posts/how-goroutines-work/) by Krishna Sundarram

### Channels
[Channels in Golang](http://www.tapirgames.com/blog/golang-channel) by @TapirLiu

### Tools
["go test -race" Under the Hood](https://www.youtube.com/watch?v=5erqWdlhQLA) Talk by Kavya Joshi

## Scheduler

[Scalable Go Scheduler Design Doc](https://docs.google.com/document/d/1TTj4T2JO42uD5ID9e89oa0sLKhJYD0Y_kqxDv3I3XMw/edit#heading=h.mmq8lm48qfcw) by Dmitry Vyukov from the Go 1.1 Design Docs

[Go Preemptive Scheduler Design Doc](https://docs.google.com/document/d/1ETuA2IOmnaQ4j81AtTGT40Y4_Jr6_IDASEKg0t0dBR8/edit#heading=h.3pilqarbrc9h) by Dmitry Vyukov from the Go 1.3 Design Docs

[How does the golang scheduler work?](https://www.quora.com/How-does-the-golang-scheduler-work/answer/Ian-Lance-Taylor) by Ian Lance Taylor

[Go's work-stealing scheduler](https://rakyll.org/scheduler/) by Jaana B. Dogan

### Timers
[How Do They Do It: Timers in Go](https://lk4d4.darth.io/posts/go-timers/) by Alexander Morozov

## Memory
[The Go Memory Model](https://golang.org/ref/mem) from the Go Documentation

[Contiguous stacks in Go](http://agis.io/2014/03/25/contiguous-stacks-in-go.html) by Agis Anastasopoulos

[Contiguous Stacks](https://docs.google.com/document/d/1wAaf1rYoM4S4gtnPh0zOlGzWtrZFQ5suE8qr2sD8uWQ/pub) from the GO 1.3 Design Docs

### Garbage Collection
[Golang’s Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/) by Will Sewell

[Request Oriented Collector (ROC) Algorithm](https://golang.org/s/gctoc) by Rick Hudson and Austin Clements and
_[discussion at golang-dev](https://groups.google.com/d/topic/golang-dev/WcZaqTE51ZU/discussion)_

## Compilation
[A Quick Guide to Go's Assembler](https://golang.org/doc/asm) from the Go Documentation

[The Design of the Go Assembler](https://www.youtube.com/watch?v=KINIAgRpkDA) talk by Rob Pike

[Dropping Down Go Functions in Assembly](https://youtu.be/9jpnFmJr2PE) ([slides](https://github.com/golang/go/files/447163/GoFunctionsInAssembly.pdf)) talk by Michael Munday

[Golang Internals](https://blog.altoros.com/golang-part-1-main-concepts-and-project-structure.html) Series of Blog Posts by Siarhei Matsiukevich

[Go compiler internals: adding a new statement to Go](https://eli.thegreenplace.net/2019/go-compiler-internals-adding-a-new-statement-to-go-part-1/) two-part series of posts by Eli Bendersky

### SSA compiler
[SSA Backend for the Go Compiler](https://docs.google.com/document/d/1szwabPJJc4J-igUZU4ZKprOrNRNJug2JPD8OYi3i1K0/edit) by Keith Randall

[SSA optimization rules description language](https://quasilyte.dev/blog/post/go_ssa_rules/) by Iskander Sharipov

**Algorithms used by SSA compiler**

[Simple and Efficient Construction of Static Single
Assignment Form](http://pp.info.uni-karlsruhe.de/uploads/publikationen/braun13cc.pdf) by Braun, Buchwald, Hack, Leißa, Mallon, and Zwinkau

[A Linear Time Algorithm for Placing Φ-Nodes](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.8.1979&rep=rep1&type=pdf) by Sreedhar & Gao

## General

A lot of other information can be gathered from the [Go Design Documents](https://github.com/golang/go/wiki/DesignDocuments) and from the (now defunct) [Unofficial Go Internals wiki](http://web.archive.org/web/20150716120037/http://goin.wikispot.org/)
