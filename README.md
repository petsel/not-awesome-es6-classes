# Not Awesome: ES6 Classes

A curated list of resources on why ES6 (aka ES2015) classes are NOT awesome

Reverse-inspired by all of the awesome lists on GitHub, like [Awesome](https://github.com/sindresorhus/awesome) and [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness)

## Table of Contents

- [Introduction](#introduction)
- [TL;DR](#tl;dr)
- [Reading](#reading)
- [Videos](#videos)
- [License](#license)

## Introduction

While ES6 brings several useful and syntactically pleasing new features to JavaScript, there are many people in the JS community who feel that adding class syntax to the language was a mistake. I share this sentiment, but I have encountered quite a few programmers in the wild who don't agree or simply don't seem to understand why some of us have this opinion. So, I wanted to create an online reference where people could come to learn specifically about this issue and why they might not actually need class syntax in JavaScript.

## TL;DR

- JavaScript is a class-free, object-oriented programming language. It eschews [classical inheritance](https://en.wikipedia.org/wiki/Class-based_programming) in favor of [prototypal inheritance](https://en.wikipedia.org/wiki/Prototype-based_programming).
- Many believe prototypal inheritance to be more flexible and freeing than classical inheritance due to its less rigid nature.
- The ES6 class syntax, constructors, the `new` keyword, etc. are ideas taken from the classical inheritance model to make programmers coming from languages like C++, Java, C#, etc. more comfortable and do not really belong in JavaScript.
- While prototypal inheritance is very powerful in its own right, there is a growing movement among developers, both within and outside of JavaScript (Ex: [Golang](https://talks.golang.org/2012/splash.article#TOC_15.), to shift away from inheritance in favor of object composition. 
- ES6 class syntax is essentially syntactic sugar that will end up obfuscating the true nature of JavaScript and confusing the next generation of programmers learning it.
- You should consider factory functions, object composition, and/or prototypal inheritance via simply using prototypes and Object.create() while avoiding constructors and the `new` keyword altogether.


## Reading

- [Common Misconceptions About Inheritance in JavaScript](https://medium.com/javascript-scene/common-misconceptions-about-inheritance-in-javascript-d5d9bab29b0a)
- [Composition over Inheritance](https://medium.com/humans-create-software/composition-over-inheritance-cb6f88070205)
- [Delegation vs Inheritance in JavaScript](https://javascriptweblog.wordpress.com/2010/12/22/delegation-vs-inheritance-in-javascript)
- [Factory functions in JavaScript](https://medium.com/humans-create-software/factory-functions-in-javascript-video-d38e49802555)
- [How to Fix the ES6 `class` keyword](https://medium.com/javascript-scene/how-to-fix-the-es6-class-keyword-2d42bb3f4caf)
- [Introducing the Stamp Specification -- Move Over, `class`: Composable Factory Functions Are Here](https://medium.com/javascript-scene/introducing-the-stamp-specification-77f8911c2fee)
- [Javascript OO Without Constructors](http://tobyho.com/2012/10/21/javascript-OO-without-constructors/)
- [The Two Pillars of JavaScript -- Part 1: How to Escape the 7th Circle of Hell](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)
- [Think twice about ES6 classes](http://christianalfoni.github.io/javascript/2015/01/01/think-twice-about-classes.html)

## Videos

- [Ashley Williams: If you wish to learn ES6/2015 from scratch, you must first invent the universe](https://www.youtube.com/watch?v=DN4yLZB1vUQ)
- [Composition over inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA)
- [Douglas Crockford: The Better Parts - JSConfUY 2014](https://www.youtube.com/watch?v=bo36MrBfTk4)
- [Factory Functions in JavaScript](https://www.youtube.com/watch?v=ImwrezYhw4w)
- [Fluent 2013 - Eric Elliott, "Classical Inheritance is Obsolete: How to Think in Prototypal OO"](https://www.youtube.com/watch?v=lKCCZTUx0sI)
- [Nordic.js 2014 • Douglas Crockford - The Better Parts](https://www.youtube.com/watch?v=PSGEjv3Tqo0)
- [Source Decoded 3: Javascript -- Prototypes, Prototypal Inheritance done right.](https://www.youtube.com/watch?v=Yvf_kUBZmXg)

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
