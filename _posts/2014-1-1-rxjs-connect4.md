---
layout: post
title:  "RxJS - Connect4"
date:   2014-1-1 10:35:01
categories: jekyll update
---

RxJS - Connect4
---------------

{% include rxjs-connect4/rxjs-connect4.html %}

### Rx
RxJS is a library to aid in reactive functional programming.  To learn more about Rx and functional programming checkout this blog post.

- [Learn RX](http://reactive-extensions.github.io/learnrx)
- [Netflix Rx Marble Diagrams](http://netflix.github.io/RxJava/javadoc/rx/Observable.html)

### Program Flow
The program treats key events as program logic control.  So everytime a key is pressed (left, right, or enter) the world state
is updated and notifies other observers.

### Furthur Work
I am going to try rewriting the program with a different async library.

- [JS/Pipe](http://jspipe.org/)