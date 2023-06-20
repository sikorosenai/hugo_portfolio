---
title: "First"
date: 2023-06-20T16:55:59+02:00
draft: true
cover:
    image: Screenshot 2023-06-11 at 12.38.45.png
    alt: 'Test image'
    caption: 'Hey its an image'
---

- Multi-way/Multi-bit multiplexer: An m-way n-bit multiplexer selects one of its m n-bit inputs, and outputs it to its n-bit output. The selection is specified by a set of k selection bits, where $k = \log_2{m}$ (because there must be enough combination of bits to have the possibility for each in to be selected). 
In the project I will need a 4-way 16-bit multiplexer and an 8-way 16-bit multiplexer, but the principles are the same: 
```API Style
Chip name: Mux4Way16
Input: a[16],b[16],c[16],d[16], sel[2]
Output: out[16]
```

# Chapter 1

The implementation of a process is the "how", the abstraction is the "what".

> Any real-world computation can be translated into an equivalent computation involving a Turing machine.

At the bottom, all computers are essentially equivalent.
Abstraction is essential to this course. All projects are built upon the previous projects shoulders, and no knowledge of how it works is necessary. This is a VERY important concept in computer science for all sorts of reasons. A simplistic one is to imagine how a team of engineers will work on a big system together, without trodding on each others toes.
