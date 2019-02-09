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
1. S: I have some doughts about the benefit of this workshop since I've just finished reading the Refactoring book and I'm pretty sure I understand the concept.
1. I: oh, may I ask about your hobbies like arts or sports?
1. S: Sure, I was dancing ballet since I was 5, I used to practice a lot, I still take dance classes whenever I have time.
1. I: Nice, Could you become a dancer only by reading books and watching online materials?
1. S: I find it hard to believe.
1. I: Will you trust a heart surgeon without proven practical experience?
1. I: Do you think anyone could successfully ride bicycles for the first time just because they have good understanding of the phisics and gyroscopic effects involved in bicycle stability?
1. I: Refactoring is not different. Books are important, though when it comes to building a skill, the best way is to practice with others that already know how to do it.
1. N: So, if I understand correctly, the majority of the time is used for writing the software and just a small portion of the effort is about refactoring. Why investing in building a skill that is only rarely used?
1. I: Oh, you got it all wrong, I should have said it at the beginning. Refactoring is not a task on the task board. Refactoring is an ongoing activity. In fact, I spend more time refactoring the existing code than writing new code. The development of almost every new feature starts with refactoring in order to make the necessary adjustments to the current design so that the new code will be elegantly introducesd into the existing solution.
1. I: More than that, as software developers, we spend most of our time reading code that was written by us and by others. As we browse through the code, we very often come up with adjustments and improvements that could have made the code easier to maintain. Developers with high awareness for software maintainability know that those great thoughts of improvments worth nothing unless they are rigurously applied to the code. We call this high awareness for software maintainability Clean Code Culture.
