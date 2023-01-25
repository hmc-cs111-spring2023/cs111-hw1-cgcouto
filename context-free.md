# Context Free

##  Who is this programming language for?

This language is for those who want to make digital art in a very computer science-y way, one that is inspired by context-free grammars! 

## What is easy to do in this language? Why is it easy?

Context Free makes is pretty simple to create recursive shapes. This is because the syntax for doing so is pretty easy: you just need to do a recursive call in the shape definition along with some shape adjustments!

## What is hard to do in this language? Why is it hard?

It can be hard to write text in this language because there is no feature that does it for you with a given string; you need to spell out each letter line by line. This is doable, but it's much less convenient than having a TEXT primitive shape available to you.


## How did you learn how to program in this language?

I looked at the initial 'WELCOME' file that boots when you start Context Free as well as the CF Wiki found [here](https://github.com/MtnViewJohn/context-free/wiki). In particular, the first example under Shape Rules on the wiki was helpful for understanding recursive shapes.

## What is the underlying _computational model_ for this programming language? 
_We don't yet have a great definition of the term "computational model". 
For now, try to come up with the clearest, most concise explanation of what 
happens when a ContextFree program runs._

The DSL begins at the startshape and searches downward through any subshapes to see what must be drawn. Then it renders all of the shapes to get the final image (over many iterations if there are any recursive shapes in there).

## What do you think is interesting about the ContextFree program you wrote?

I really like the smoke effect that I created! It's cool how it leveraged the recursive capabilities of Context Free to make smoke that's somewhat convincing.