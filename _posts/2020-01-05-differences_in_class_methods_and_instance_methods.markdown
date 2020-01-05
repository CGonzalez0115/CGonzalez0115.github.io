---
layout: post
title:      " Differences in Class Methods and Instance Methods"
date:       2020-01-05 23:30:01 +0000
permalink:  differences_in_class_methods_and_instance_methods
---


**Firstly, what is a class method? **

A class method is a method that is bound to a class rather than its object. It is appropriate to use them in cases that do not deal with the instance of a class.

**What is an instance method?**

Instance methods are methods that require an object of its class to be created before it can be called. 

A class method provides a purpose to the class itself, whereas an instance method provides a purpose to only one instance of a class. When you are using a class method you cannot call this upon an instance, however, you do have the ability to call this upon the class. As is vice versa with the use of an instance class.
![](https://imgur.com/9ExB6JA)
For example, if you called find on this Alphabet class it would work. If you called letter on the class it would raise an error.

There are multiple ways to define class methods such as the two below.
![](https://imgur.com/5NzyKpo)
The first was noted in the previous example above, it is the easiest to work with and the easiest to read. The second is also commonly used, however, when using multiple methods in the class it can get confusing.
![](https://imgur.com/Bw91UeN)
There are also multiple ways to define instance methods, such as the ones below.

In conclusion, the biggest, most important difference between a class and instance method is that a class method can call upon the class and the instance method can call upon an instance within the class.
