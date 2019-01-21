I: Instructor<br>
G: Grouchy<br>
N: Newbie<br>
S: Sharp<br>

1. I:
Refactoring, Refactoring… what is refactoring?
1. G:
Refactoring is when you clean up the mess after you write the code.
1. N:
Refactoring is when you use all those advanced editing tools in the IDE like rename and extract method.
1. S:
I know, refactoring is when you change the internal structure of the code without changing its behavior.
The refactoring book
1. I:
Right, refactoring is the art of changing the internal structure of the code while keeping its behavior unchanged.
1. G:
Wow, wow, wow, what is this nonsense, why do you have to re-invent everything. We also did this Refactoring, we just called it Rewrite!
Rewrite, is when you clean up the mess after you write the code.
When you rewrite you fix the design and keep the behavior, just this time you write the code the right way.
There is no differenct between refactoring and rewrite!
1. I:
You’re raising a very good question. What is the difference between refactoring and rewrite? Are they the same thing?
1. S:
Oh, huge difference, Refactoring is when you change existing code without changing its behavior. Rewrite, on the other hand, is when you write it from scratch.
1. N:
What if you clean up the code and rewrite just one method. Is it refactoring or rewrite?
1. G:
Why do I care if I write from scratch or just change the code. The essence stays the same! Cleaning up the mess.
1. I:
Ok, Ok, those are good questions again, let me try to explain. 
For me, Refactoring is like playing a game. I call this game Customer is In the Room.
It means that when I refactor, a customer or any other stakeholder can always, at any point in time, challenge me to run under development software and I will be able to run the current code I’m working on, without any delays. 
With rewrite, you can not do that. You will only be able to run the software when you are done rewriting the unit. Now, that's a big difference.
1. G:
Without any delays?! Without any delays?!! Let me tell you, young man, I’ve been in the software industry long enough to know there is no “without any delays” in software. 
You need to finish the change, you need to debug, you need to test, you need to fix all the defects, only then you can run the software.
1. N:
Yeh, how do you do that? How can you always be able to run the code without delays?
1. I:
I achieve that by composing the change as a sequence of micro-steps called refactoring transformations. 
Each transformation is a tiny change to the code’s structure that is promised to keep the behavior intact. 
Since it takes no more than a few seconds to perform these transformations, my software is always valid and I can always run my current ‘under-development’ code.
1. G:
Micro-steps!?. I just don’t understand why would you choose to work like that.
Breaking the change into such tiny steps seem so inefficient. There must be a price in time or effort you pay with this approach!
1. I: 
Well, I can surely understand why someone may perceive this approach to be somewhat expensive. 
It takes a lot of discipline and practice before we can truly enjoy the fruits of this skill. 
The temptation to just clean up the mess by one big rewrite is always there as well as the illusion of speed. 
Have you considered the risk in rewriting an already working software? How many new defects will you introduce, how many days or weeks will it take to restabilize the system? With rewrite, can you really predict the price?
If there is something I learned about software development in the last 30 years it is that the smaller the steps you take, the faster and safer the progress is!
Most IDEs today support refactoring by offering a wide range of automated refactoring transformations. 
To my experience, when I refactor, I go safer and faster than rewrite. Much faster.
1. I:
Let me show you how it is done
