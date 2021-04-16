# Read: 06 - JS Object Literals; The DOM

FROM THE DUCKETT JS AND JQUERY BOOK

Chapter 3: " object literals"

What is an Object ?

* objects group together a set of variables and functions to create a model of something you would
 recognize from the real world . in an object , variables and functions take on new names.
* in an objet , variables become known as properties
* in an object, functions becomes known as methods
* variables and named functions , properties and methods have a name and a value . in an object that
 name is called a key

Chapter 5: " Document Object model"

* browser represents a page using a DOM tree
* DOM trees 4 types of nodes :
  * document nodes
  * element nodes
  * attibute nodes
  * text nodes

* can select element nodes by their id or class attributes,by tag name, or using CSS selector syntanx
* DOM query can return more than one node, it will always return a NodeList
* from an element node , you can access and update its content using properties such as textContent and
 innerHTML or usin DOM manipulation techniques
* an element node can contain multiple text nodes and child elements that are siblings of each other
* browsers offer tools for viewing the DOM tree

# Understanding the problem domain is the hardest part of programming

## TLDR

Programmers often lack the skills needed to comprehend problem domains. If you understand the problem domain, programming is easy; if you don't, it's hard.
Talking to consumers or business people who are familiar with the problem domains is a waste of time. Eliminate cases and emphasis a specific aspect of the issue,
or improve your comprehension of problem domains, he says. It may be time-consuming, but it's much more efficient than hammering out a spec in a couple of hours.
Defterios, a self-confessed perfectionist, says.
>>
***The content below is an excerpt from the article.***
>>
```
"What is the hardest thing about writing code?

There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

However, as I focus on my programming experience and speak with several young programmers studying the trade, I've discovered the single most difficult thing to overcome.

Simple functionality that is easy to describe and, most importantly, understand. Since it was too simple to comprehend, the emphasis was shifted away from the issue domain
and toward the technology. Since I used this same application to teach a multitude of various innovations, it acted as a reference issue domain that didn't need relearning.
It also called for the comparison and contrast of various technologies.

Putting together a jigsaw puzzle is similar to writing code. Many problem domains resemble a puzzle with a hazy or non-existent image. The entire world is a jumbled mess. 
Many of the problem domains we encounter as programmers are difficult to comprehend and appear in a variety of ways based on perspective.

As programmers, we are often given inadequate information about the problem domain, and therefore lack the skills needed to comprehend it. We wrote code with the aim of constructing
components that we had removed from the "bigger picture."

If you understand the problem domain, programming is easy. I was given a pixel-perfect specification for a printer tab control and told precisely how it should work. Writing the 
coding for a function was a breeze. I've spent days trying to introduce a function only to have to go back and speak to a product owner about how and why anything can work the way 
it does. It's not like being on an Agile team, where you have to describe the issue in depth to the product owner before writing code. It may be time-consuming, but it's much more efficient th
an hammering out a spec in a couple of hours. It also gives you a good picture of the problem.

There are two things you can do to make learning the problem domain better if it is the most difficult aspect of programming. Eliminate cases and emphasis a specific aspect of
the issue. Improve your comprehension of problem domains. Doing something over is much more costly and time-intensive than doing them correctly the first time. We are developers 
have a tendency to believe that speaking with consumers or business people who are familiar with the problem domains is a waste of time. It's difficult to suppress the impulse
to "not spend any more time chatting" and ensuring that you thoroughly comprehend a dilemma before trying to address it with coding."

references :by john sonmez ,2013,Understanding the problem domain is the hardest part of programming,simleprogrammer page,
            16.04.2021,http://simpleprogrammer.com/2013/07/15/understanding-the-problem-domain-is-the-hardest-part-of-programming.

```
