---
title: "Java As A First Language: A Bad Idea"
categories:
  - Programming
  - Computer Science
icon: fa-times-circle
date: 2017-09-02
tags:
---


Let's get this blog rolling with its first actual post.

I first learned Java in our Intro to CS course and I have been stuck with it in school until recently in my junior year courses. I didn't really think much of it at the time. Since then I've taken up several different languages either for work or out of personal interest, and I've now developed a certain love-hate relationship with Java.

#### Caution: Opinions Ahead

The basics of the language are easy enough to learn for a beginner. It's cross platform so students can use it regardless of the OS on their personal machines, and the Java API has many useful classes and features implemented for you out of the box. Despite all this, I believe that there are better choices out there for an Intro to CS course. Let's take a look at a few reasons why I think this is.

#### Java is too verbose
This is a simple "Hello world" program in Java, with conservative spacing:

```java
class Hello {
   public static void main(String[] args) {
       System.out.println("Hello world!");
   }
}
```

About three lines filled with a lot of technical jargon, five if we count the closing braces. Comparing this to Python:

```py
print("Hello world!")
```

Wow, much shorter. And you only need to type what you mean. Literally, `print` the words "Hello world!" to the screen. Back when I was still a beginner, I know for sure which one I would have found less intimidating.

However, the length itself isn't really the issue as much as the amount of keywords involved.

#### Java is too *technically* verbose
When a beginner picks up Java, they inevitably ask at the beginning: "What is a class?", "What does `public` mean?", "What is `static`?", and the list goes on.

Professors explain this by saying "You'll learn this later." And I don't really blame them for that, since they don't really have a choice. You can't explain what a `class` is until they know what object oriented programming is. And you can't teach what `public` means until they understand scoping. By contrast, the Python example contains just one keyword, is much easier to explain what it does, and is a lot more intuitive.

In my class, the professor literally referred to  `public static void main(String[] args)` as the "black magic incantation" that would make our programs run. Oh, and she also made us chant it in unison. Great way to learn programming, right?

#### Not high level, yet not low level

Java is considered a high level language, but it's definitely less abstracted unlike Python or JavaScript. It also isn't as low level as C or Rust where you need to manage memory manually. Starting with Java results in the inability to paint a full picture of how the computer works. When learning programming, one should start from one end of the high/low level spectrum and slowly move towards the other end.

On one hand, we could start with a scripting language with many features like Python or JavaScript. Once the students have gotten the basics of programming down such as variables, conditionals, and loops, then we can move onto Java and introduce more strict C-like syntax with strong typing. Finally, move onto C/C++, demonstrating how the conveniences in Python and Java are actually abstracted away.

Or we could go the other way around. Start with the bare metal and basic memory management. Once the students have been thoroughly annoyed by all the work involved in something as simple as expanding an array, then we can move up to something like Java. It's a little less work now, still with similar syntax but a lot more abstract. Finally, introduce the freedom and ease-of-use of scripting and functional languages and loosely typed languages. In fact, this is how Harvard's introductory course CS50 structures their progression of topics.

By traveling the entire spectrum, the student gets a chance to get a more complete view of programming. They become familiar with low level concepts such as memory management and pointers, but also understand that there are higher level languages that abstract those things away for easier and more rapid development of applications that don't require that degree of control.

#### In the end, the choice isn't mine

These were some reasons why I don't think we should be teaching Java as what might be the very first programming language for many students. While it's a language with many strong suits, I find that there are better ways to introduce programming and CS concepts than sticking with only Java for your first two years of college. Let me know in the comments what programming languages you think are a good idea to start with.