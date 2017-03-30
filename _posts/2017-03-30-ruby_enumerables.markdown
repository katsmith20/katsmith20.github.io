---
layout: post
title:  "Ruby Enumerables"
date:   2017-03-30 21:39:20 +0000
---


**Iterating through Ruby Iteration**

The Learn.co Iteration sections do a great job taking you through simple iteration to complex looping constructs. But of course, in typical Ruby fashion, the "simple" loops require more code that is inherent in the more "complex" iterators. 

For example, when using a `while` loop, programmers need to create a block of code that will yield when iterating over each element and execute necessary code. This can take up multiple lines of code, and while it may be clear and succinct, *why take 5 lines of code when we can execute the same thing with one line?* So while this is a "basic" way to iterate an array over a block of code, the code required to execute such iteration is more complex than necessary.

There are a TON of iterators available to create more succinct and easy to read methods. For example, when using `.collect `or `.map` for example, the iterator inherently creates a new array with collected elements, without the coder having to explicitly push each element into a new array. 

While working through the lessons, I found that working with the more "complex" enumerators was difficult when I did not have a full understanding of the basic functions of iterators. Understanding *yield* was imperative for me to fully understand what each iterator was actually doing. 

Now that I fully grasp how enumerables and enumerators work, it is important that I know which iterators are available in Ruby. There is a plethora of methods that a Ruby programmer can call, and a good place to start looking is [here](http://ruby-doc.org/core-2.2.3/Enumerable.html)! 
