# Concepts of Functional Programming in Javascript

After a long time learning and working with object-oriented programming, I took a step back to think about system complexity.
>“Complexity is anything that makes software hard to understand or to modify." — John Outerhout

Doing some research, I found functional programming concepts like immutability and pure function. Those concepts are big advantages to build side-effect-free functions, so it is easier to maintain systems — with some other benefits.
In this post, I will tell you more about functional programming, and some important concepts, with a lot of code examples. In Javascript!
What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia.
Pure functions benefits
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D
A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.