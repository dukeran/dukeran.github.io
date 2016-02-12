---
layout: post
title: "Boolean Values"
date: 2016-02-07 00:44:33 -0500
categories: code-for-thought
comments: true
sharing: true
footer: true
 
---
####Fundamentals of Ones and Zeros

Thanks to a friend of mine, I've recently been doing a lot of Kata on __Codewars__. If you've never done katas on Codewars before, I would _highly, highly, highly_ reccomend it. It's a great site where your competitive nature can get the best of you as you compete with other friends for 'honor'. There are eight levels of difficulty and each kata is a creative coding problem that you solve for honor points. The beginner's level, level 8, is a good overview of incredibly basic coding concepts. Once you enter your solution you are able to see how others solved the same kata. 

--> http://www.codewars.com 

My username is __dukeran__ if you want to add me! 

#####_special note: if the same solution was posted by more than two people then I will not site the code._

After going through Chris Pine's _Learn to Program_  book, here is the solution I came up with: 

```ruby
	def boolean_to_string(b)
  		if b == true 
    "true"
  		else b == false
    "false"
  end
end
```
This is a straightforward code which works just fine but doesn't utilize the fundamental concept of Boolean values. 

<!--more-->
It wasn't until I saw other answers and started doing some research that I learned more about it. It started when I saw the most popular answer and was instantly confused: 

```ruby 
def boolean_to_string(b)
  b ? "true" : "false"
end
```
At first I cocked my head and then wiped my glasses. First of all, what does the ```?``` mean? and why don't you have to specifically tell ruby that `if b = true...` How does ruby automatically know to test for true and false? 

The program above may seem painfully simple to any programmer worth their salt but to a newbie in the field, it was a confusion fest - especially when it comes to Ruby. I find that as a Linguistics major with no background in coding, many expert programmers assume that these fundamentals are pure common sense. This is not the case for most non-programmers and I want to break everything down step by step. 

-finish-


need to have a question mark to denote the boolean theory!!
