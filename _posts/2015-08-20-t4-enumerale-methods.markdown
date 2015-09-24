---
layout: post
title:  "Technical Entry 4 - Enumerable Methods"
date:   2015-08-20
categories: blog entry
---
Arrays have come up a lot in the last two weeks. It’s probably the reason behind me wanting to use an array to solve every challenge. It’s also probably the reason why that whenever I start typing any web site address that beings with the letter “r” my web browser autocompletes to ruby-doc.org/core-2.2.2/array.html.  In my research, I’ve often run across the method map.  I haven’t found many, if any, chances to use it so started wondering if it’s because I don’t actually know how to use it. So I figured, what better topic to do this blog entry on than the map method.

First things first, the method “map” and the method “collect” are they same and are used interchangeably. However, throughout this blog entry, I’ll keep things consistent and use only “map”.  Generally, when I start solving a challenge I begin with visiting the ruby docs. Even though I can’t understand the majority of their definitions, it’s a good place to start.  I looked up the definition of “map” and this one is actually pretty straightforward. It reads, “returns a new array with the results of running block once for every element in enum. If no block is given, an enumerator is returned instead.”

While the definition seems pretty straight forward, its still pretty dry and tough to really understand what map is capable of.  It might be best explained through a couple examples. Take a look at the examples below and the commentary that I have added.  Also, here’s a <a href= "https://www.youtube.com/watch?feature=player_embedded&v=1zWj9BReAX8"> short video</a> that gives another good example of the map method.

<script src="https://gist.github.com/mlefurge/64f0a924047958bc5432.js"></script>
