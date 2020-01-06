---
layout: post
title:      "Compare and contrast of attr_accessor, attr_reader, and attr_writer"
date:       2020-01-05 19:56:41 -0500
permalink:  compare_and_contrast_of_attr_accessor_attr_reader_and_attr_writer
---

When we are wanting to fluidly access attributes included within our module it is often easier to use attr_accessor, attr_reader, and attr_writer.
Although they are indeed all created to access attributes, they all do so in different manners.
An attr_reader only reads the value of an attribute and cannot change it(it is a getter method). An attr_writer can only change the value of an attribute but cannot read it(it is a setter method). An attr_accessor does both and allows us to access more information with less work(it is a getter and setter).
These incredibly useful three methods allow you to access and set instance variables from the outside of the class without having to explicitly define the getter and setter methods ourselves.
![](https://i.imgur.com/W7mPhHK.jpg)
