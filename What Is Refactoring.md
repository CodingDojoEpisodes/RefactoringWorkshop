I: Instructor<br>
G: Grouchy<br>
N: Newbie<br>
S: Sharp<br>

1. I:<br>
Refactoring, Refactoring… what is refactoring?
1. G:<br>
Refactoring is when you clean up the mess after you write the code.
1. N:<br>
Refactoring is when you use all those advanced editing tools in the IDE like rename and extract method.
Names of refactorings
1. S:<br>
I know, refactoring is when you change the internal structure of the code without changing its behavior.
The refactoring book
1. I:<br>
Right, refactoring is the art of changing the internal structure of the code while keeping its behavior unchanged.
1. G:<br>
Wow, wow, wow, what is this nonsense, why do you have to re-invent everything. We also did this Refactoring, we just called it Rewrite!
Rewrite, is when you clean up the mess after you write the code.
When you rewrite you fix the design and keep the behavior, just this time you write the code the right way.
1. I:<br>
You’re raising a very good question. What is the difference between refactoring and rewrite? Are they the same thing?
1. S:<br>
Oh, huge difference, Refactoring is when you change existing code without changing its behavior. Rewrite, on the other hand, is when you write it from scratch.
1. N:<br>
What if you clean up the code and rewrite just one method. Is it refactoring or rewrite?
1. G:<br>
Well, this Refactoring practice sounds exactly like Rewrite to me. The essence of rewriting is changing the internal structure while keeping the behavior.
1. I:<br>
Ok, Ok, these are good questions, let me try to explain. 
For me, Refactoring is like playing a game. I call this game Customer is In the Room.
When I refactor, a customer or any other stakeholder can always, at any point in time, challenge me to run under development software and I will be able to run the current code I’m working on, without any delays. 
With rewrite, you can’t do that. You will only be able to run the software when you are done rewriting the unit. Now, that's a big difference.
1. G:<br>
Without any delays?! Without any delays?!! Let me tell you, young man, I’ve been in the software industry long enough to know there is no “without any delays” in software. 
You need to finish the change, you need to debug, you need to test, you need to fix all the defects, only then you can run the software.
1. N:<br>
Yeh, how do you do that? How can you run the code without delays?
1. I:<br>
I acheive that by composing the change as a sequence of micro-steps called refactoring transformations. 
Each transformation is a tiny change to the code’s structure that is promised to keep the behavior intact. 
Since it takes no more than a few seconds to perform these transformations, my software is always valid and I can always run my current ‘under-development’ code.
1. G:<br>
Micro-steps!?. I just don’t understand why would you choose to work like that.
1. Breaking the change into such tiny steps seem so inefficient. There must be a price in time or effort you pay with this approach!
1. I:<br>
If there is something I learned about software development in the last 30 years it is that the smaller the steps you take, the faster and safer the progress is!
Most IDEs today support refactoring by offering a wide range of automated refactoring transformations. 
To my experience, when I refactor, I go safer and faster than rewrite. Much faster.
1. I:<br>
Let me show you how it is done
