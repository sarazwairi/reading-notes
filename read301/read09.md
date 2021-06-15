# FUNCTIONAL PROGRAMMING

## Functional Programming Concepts

## What is functional programming?

 is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## What is a pure function and how do we know if something is a pure function?


It returns the same result if given the same arguments (it is also referred as deterministic)

It does not cause any observable side effects

## What are the benefits of a pure function?

The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:

Given a parameter A → expect the function to return value B

Given a parameter C → expect the function to return value D

## What is immutability?

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

## What is Referential transparency?

Basically, if a function consistently yields the same result for the same input, it is referentially transparent.

pure functions + immutable data = referential transparency

Node JS Tutorial for Beginners #6 - Modules and require()

## What is a module?

Module is just essentially another JavaScript file

## What does the word ‘require’ do?

That is in the global object in node js and we can use it any where

## How do we bring another module into the file the we are working in?

Export it from the module file and then require it at our file

## What do we have to do to make a module available?

Store the required as a variable and export it