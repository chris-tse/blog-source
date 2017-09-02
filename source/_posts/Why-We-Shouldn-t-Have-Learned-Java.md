---
title: Why We Shouldn't Have Learned Java
categories:
  - Programming
  - Computer Science
icon: fa-times-circle
date: 2017-09-02
tags:
---


Let's get this blog rolling with its first actual post.

I first learned Java in our Intro to CS course and I have been stuck with it in school until recently in my junior year courses. I didn't really think much of it at the time. Since then I've taken up several different languages either for work out of personal interest, and I've now developed a certain love-hate relationship with Java.

#### Caution: Opinions Ahead

The basics of the language are easy enough to learn for a beginner, is cross platform so students can use it regardless of platform, and the Java API has many features implemented for use out of the box. Despite all this, I believe that there are better choices out there for an Intro to CS course. Let's take a look at a few reasons why this is. And to be clear, this is all in my opinion.

#### Java is too verbose
This is a simple "Hello world" program in Java, with conservative spacing:

```java
class Hello {
   public static void main(String[] args) {
       System.out.println("Hello world!");
   }
}
```

About three lines filled with a lot of technical jargon. Compared to Python:

```py
print("Hello world!")
```

Wow, much shorter. And you only need to type what you mean. Literally, `print` the words "Hello world!" to the screen. Back when I was still a beginner, I know for sure which one I would have found less intimidating.

However, the length itself isn't really the issue as much as the amount of keywords involved.

#### Java is too *technically* verbose
When a beginner picks up Java, they inevitably ask at the beginning: "What is a class?", "What does `public` mean?", "What is `static`?", and the list goes on.

Professors explain this by saying "You'll learn this later." And I don't really blame teachers for that, since they don't really have a choice. You can't explain what a `class` is until they know what object oriented programming is. And you can't teach what `public` means until they understand scoping. By contrast, the Python example contains just one keyword, and it's much easier to explain what it does, and is quite intuitive, as is the rest of the language.

In my class, the professor literally referred to  `public static void main(String[] args)` as the "black magic incantation" that would make our programs run. Oh, and she also made us chant it in unison. Great way to learn programming, right?

#### Not high level, yet not low level

Java is considered a high level language, but it's definitely less abstracted unlike Python or JavaScript. It also isn't as low level as C or Rust where you deal with manual memory management. I think that starting with Java results in the inability to paint a full picture of how the computer works

In my opinion, I also believe that when learning programming, one should generally start from one end of the high/low level spectrum and slowly move to the other end.

On one hand, we could start with a scripting language with many features like Python or JavaScript. Once they've gotten the basics of programming down such as variables, conditionals, and loops, then we can move onto Java and introduce more strict C-like syntax with strong typing. Finally, move onto C/C++, demonstrating how the conveniences in Python and Java were actually abstracted away, showing how to allocate memory.

Or we could go the other way around. Start with the bare metal and basic memory management. Once they have been thoroughly annoyed by all the work involved in something as simple as expanding an array, then we can move up to something like Java. It's a little less work now, still with similar syntax but a lot less memory management. Finally, introduce the concept of scripting and functional languages and loosely typed languages.

By traveling the entire spectrum, the student gets a chance to get a more complete view of programming. They understand the low level concepts of memory and pointers, but also understand that there are higher level languages that abstract those things away for easier development of applications that don't require that degree of memory management.

Starting with something like Python or JavaScript would have made the initial learning curve much less steep and much less mysterious. Once the basics have been solidified, then we can move onto something a little lower level.