---
title: Studying Compiler
date: 2023-09-12 1:33:47 +01000
categories: [compiler, learning]
tags: [compiler, parser] 
--- 

## Studying Compiler
I've always been fascinated by how programming languages are created. This concept used to feel like magic to me when I was only programming in Python and JavaScript. Last year, I decided to learn C and was introduced to some low-level programming concepts. I experienced many "aha!" moments on concepts I failed to understand in Python. So, I decided to study compiler design. I undertook an initial exploration through Austin Henley's [Let's Make a Teeny Tiny Compiler](https://austinhenley.com/blog/teenytinycompiler3.html) series,  where I successfully wrote a [simple compiler](https://github.com/danieldamilare/simple_compiler) in C that compiles a dialect of BASIC into C. Additionally, I wrote a [simple math expression evaluator](https://github.com/danieldamilare/math_evaluator). 


Building on my progress, my next endeavour in compiler writing was writing the __CDECL translator__, which takes an English statement defining a C  declaration and generates the equivalent C code. For instance, a statement like ```x is a pointer to a struct temp```  would generate ```struct temp * x```. Although I was successful in writing the parser, I faced challenges in generating the C code which further motivated me to formally study compiler design.

To comprehensively study compiler design, I will be using [Compiler Design in C by Allen Holub](https://holub.com/goodies/compiler/compilerDesignInC.pdf) (the book is old, but I love its content) and the renowned "Dragon Book". These should keep me busy for several months. I will also be writing blog posts documenting my learning journey.

If you have better resources for learning compilers, feel free to share them in the comments.
