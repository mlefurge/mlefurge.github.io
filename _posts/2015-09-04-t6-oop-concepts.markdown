---
layout: post
title:  "Technical Entry 6 - Object Oriented Programming Concepts"
date:   2015-09-04
categories: blog entry
---
Blocks, procs and lambdas, oh my. I remember preparing for the DBC interview and going through CodeAcademys Ruby tract. I also remembered that there was an entire section on blocks, procs and lambdas but couldn’t really remember anything besides the fact that it existed. When I saw the blog prompt, I thought this would be a great opportunity for a refresher.

Lets start with blocks. Blocks are not objects. Strange, right? Well, its true. Blocks are actually just the little snippets of code that can be executed and that lie between curly braces or the do..end keywords.  Blocks are used by other methods. A method like #each will take the block and apply the expression to the method. Because a block is not an object, it cannot be saved to a variable. Fear not, that’s why procs exist.

A proc is a block that has been saved to a variable. Just like you can assign a variable the value of the integer three, you can also create a proc and give it the value of a block of code. This helps keeping your code DRY – once you create your proc, you can use it as many times as you need without having to rewrite the block of code. To create a block, all you need to do is call Proc.new and pass it the block of code that you want to save. Check out the example below.

Lambdas and procs are very similar. In fact, lambdas are objects of the proc class. One of the main differences between the two has to do with how it handles arguments. Procs don’t care if they receive the wrong number of arguments. They will simply ignore unexpected arguments and assign nil to any missing arguments. Lambas on the other hand, will raise an Argument error if passed the incorrect number of arguments. Another difference between the two is how they deal with control flow keywords (e.g., return and break). When Ruby encounters a return inside of a proc, it returns but does not pass control back to the calling method. After a lambda encounters a return, it will pass control back to the calling method.

<script src="https://gist.github.com/mlefurge/7d6bdb23a2a2f2ae369f.js"></script>


