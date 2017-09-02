---
title: Why We Shouldn't Have Learned Java
date: 2017-09-02
tags:
    - C++
    - Java
    - JavaScript
categories:
    - Programming
    - Computer Science
icon: fa-times-circle
---

### Caution: Opinions Ahead


#### Java is too verbose
This is a simple "Hello world" program in Java, with conservative spacing:

```java
class Hello {
   public static void main(String[] args) {
       System.out.println("Hello world!");
   }
}
```

Three whole lines of complete gibberish if you're completely new to programming. Let's compare this with Python:

```py
print("Hello world!")
```

Wow, just three words, essentially. And you only need to type what you mean.

And not only is this shorter, but you can also understand everything you just wrote: "I want to *print* "Hello world!" out". That's it. Compared to the Java example, we easily got lost at the beginning.

What is a class? What does "public static blah blah" mean? What is "String args"? A lot of it was explained to us as "You'll learn this later." And I don't really blame them now, since they don't really have a choice. You can't explain what a `class` is until they know what object oriented programming is. And you can't teach what `public` means until they understand scoping. Blind faith is what they relied on, and it really doesn't help the learning process when you just type out the boilerplate knowing only that without it, the program isn't going to work.