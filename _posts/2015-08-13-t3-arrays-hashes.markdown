---
layout: post
title:  "Technical Entry 3 - Arrays & Hashes"
date:   2015-08-13
categories: blog entry
---
Growing up my brother and I would take out our toys and play with them all over the house. One day (well, it probably happened more than once), we left the toys lying around the house and my mom couldn’t find something she was looking for. After she cleaned up our mess, found what she was looking for, she proceeded to tell us that instead of putting the toys away she threw them out (she really just hid them but I didn’t find that out until later). As traumatic as that experience was, it certainly taught me the importance of organization. Although after a recent visit to my brother’s house, I can tell that the incident didn’t affect him nearly as much as it did me.

Anyway, the point I’m trying to make is that organization is key. It’s important in programming, just like it’s important in everyday life. One-way to keep our code organized is through arrays and hashes.  Arrays and hashes are both indexed collections however; they each have specific attributes that make them useful in different situations.

What do I mean when I say indexed collections? Think of it this way. Think of an array like a numbered list. Each item on your list is given an index number. For programming, the index listing starts at zero (as opposed to one). You can call on any item in your list by referencing the index number, or key. If you don’t know the index number, Ruby also allows you to find objects in your array through a handful of other ways. Below is an example of an array.

<script src="https://gist.github.com/mlefurge/6b14d45b437381f0640c.js"></script>

Hashes are very similar but instead of storing collections of objects using an index number as a key, Ruby lets you use any object as a key.  Hashes are useful when the information you are storing doesn’t make sense to keep in a numbered list. An example of this might be if you want to store all of your friends’ favorite foods. You could use the persons name as the key and their favorite food as the value. So each time you wanted to access that person’s favorite food, you would use their name as the key and the hash could print out their favorite food. Below is an example of a hash.

<script src="https://gist.github.com/mlefurge/a41c77911fbb7e7cf89e.js"></script>