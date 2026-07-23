# Functional Programming
## Intro Into Functional Programming
Functional Programming is a programming paradigm that treats computation as the evaluation of mathematical functions, so unlike object oriented programming (OOP), which organizes code around objects and mutable state, functional programming emphasizes on the pure functions, immutability, and avoiding side effects. From what I gathered current software systems evolve and become more complex leading to functional programming gaining a clear popularity because it makes code more predictable, easier to test, and less prone to bugs.

## What Is Functional Programming?
Functional programming is based on the idea that functions should be treated as first-class citizens. This means functions can be stored in variables, passed as arguments to other functions, and returned from functions. Rather than modifying data directly, functional programs create new data structures from existing ones.

The primary goal of functional programming is to minimize complexity by reducing reliance on mutable state. When functions depend only on their inputs and always return the same output for the same inputs, programs become more predictable and easier to debug.

## What I learned
### Pure Functions
There exists a few different kinds of functions one being a pure function. A pure function always produces the same result and does not affect anything outside of itself. So, no matter how many times you use the same input the output will always remain the same. This makes pure functions much easier to understand, test, and debug because there are no hidden effects occurring elsewhere in the program.

### Immutability
Another important concept I learned was immutability. Rather than changing existing data, functional programming promotes creating new versions of data when updates are needed. Initially, this approach seemed less efficient because it felt easier to simply modify existing values. However, I came to understand that immutability helps prevent unexpected changes that can cause bugs. When different parts of an application are working with the same data, keeping the original data unchanged makes it much easier to track how information is being used throughout the program.

### High-Order Functions
Higher-order functions either accept other functions as arguments or return functions as results. They provide powerful tools for working with collections of data in a clean and readable way. The functions map(), filter(), and reduce() methods, rather than relying on traditional loops, allow developers to express their intentions more clearly. The map() function can be used to transform data, filter() can be used to select data that meets certain conditions, and reduce() can be used to combine multiple pieces of data into a single result.
The functions improve the readability of a subject which I found was quite handy. Instead of focusing on the details of how a loop processes data, the code clearly communicates on exactly how it is supposed to happen. This process allows the program to be easier to maintain and understand, especially when working on larger projects or collaborating with other developers.

## Reflection
Through my gathering of knowledge, I have found that functions... well have their function. They allow a programming style to be able to get a foot-hold and form its own foundation. I don't see functional programming as a replacement to object oriented programming. Instead, I see it as another tool that can help me write better code similar to AI. The best developers seem to combine different programming paradigms depending on the problem they're solving, and functional programming gives me another valuable approach to add to my skill set.
Functional programming encourages developers to avoid that whenever possible, which can feel strange at first. I also noticed that functional programming sometimes requires writing code differently than I normally would. While the solutions are often cleaner, it takes practice to recognize opportunities to use functional techniques effectively, which I clearly do not have as of now. 
Despite the learning curve, I can see the benefits. Pure functions and immutability create code that is easier to reason about because there are fewer hidden changes happening behind the scenes. When something goes wrong, it becomes easier to trace where the problem originated. I hope to eventually use it effectively but right now it is as handy as a hammer to a monkey.
