I: Instructor<br>
G: Grouchy<br>
N: Newbie<br>
S: Sharp<br>

1. I:
Refactoring, I'm almost sure it's not a new concept to any of you. So, what is refactoring?
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
I just don't get it, what is this nonsense, why do you have to re-invent everything. We also did this Refactoring, we just called it Rewrite!
Rewrite, is when you clean up the mess after you write the code.
When you rewrite, you keep the same behavior, just this time you write the code the right way.
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
1. S: I have some doubts about the benefit of this workshop since I've just finished reading the Refactoring book and I'm pretty sure I understand the concept.
1. I: Oh, may I ask about your hobbies like arts or sports?
1. S: Sure, I've been dancing ballet since I was 5, I used to practice a lot, I still take dance classes whenever I have time.
1. I: Nice, do you think you could become a good dancer only by reading books and watching online materials?
1. S: Oh, of course not.
1. I: Would you trust a heart surgeon without proven practical experience?
1. G: If that was case I wouldn't be here anymore.
1. I: Do you think anyone could successfully ride bicycles for the first time just because they have a good understanding of the physics and gyroscopic effects involved in bicycle stability?
1. N: Not with my bicycles.
1. I: Refactoring is not different. Books are important, though when it comes to building a skill, the best way is to practice with others that already know how to do it.
1. N: So, if I understand correctly, the majority of the time is used for implemeting new behavior and just a small portion of the effort is about refactoring. Why investing in building a new skill that is only rarely used?
1. I: Oh, you got it all wrong, I should have made it more clear at the beginning. Refactoring is not a task on the task board that you do from time to time. Refactoring is an ongoing activity. In fact, I spend more time refactoring the existing code than adding new functionality. The development of almost every new feature starts with refactoring in order to make the necessary adjustments to the current design so that the new code will be elegantly introduced into the existing solution.
1. I: More than that, as software developers, we spend most of our time reading code written by us and by others. As we browse through the code, we frequently come up with new ideas for adjustments and improvements that could have made the code easier to maintain. Developers with high awareness for software maintainability know that those great thoughts of improvement worth nothing unless they are rigorously applied to the code. We call this high awareness for software maintainability Clean Code Culture.
1. G: Ok, I think I got the idea, I just don't understand why? why would you choose to work like that? 
1. N: Yea, and when? like do you always refactor, or are there cases where you choose a different technique?
1. I: Mmm... these questions start a whole new discussion. The discussion about why and when we should refactor. I think it's a good time for a short break. We will answer these questions in the next episode. Stay with us.
