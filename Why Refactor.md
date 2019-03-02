I: Instructor<br>
G: Grouchy<br>
N: Newbie<br>
S: Sharp<br>

1. I: Hi, Welcome back. In the last episode, we described Refactoring as an ongoing effort of improving the code's structure while keeping its observable behavior unchanged. We mentioned that refactoring is performed in micro steps and that it takes time and practice to build our refactoring skills. We ended the last episode with some open questions I would like to address in this one. Grouchy, can you remind us of the question you've asked?

1. G: Sure, I said I got a general idea, I just don't understand how micro steps make you go faster? It seems to me like a waste of time when you can simply rewrite the module!

1. I:I Agree, micro-steps don’t make you go faster. Micro-steps make you go safer! It is the safety that we build into our everyday activities that makes us go faster. Wherever both the probability and the cost of an error are high, the only way to make a fast progress is to make it safe.
1. I: Look at this guy on the slackline. Clearly, he is playing a very risky game, the probability of making a mistake is very high as well as the cost of such a event. Would you advise him to run to the end and get done with it or to take the smallest steps he can?

1. G:  I can see how small steps can help with keeping the balance on a rope. Though, I still can't understand what this nice story has to do with software.

1. I: Clearly, this is just an analogy. As we all know, computer programs are both complex and fragile and we humans are error-prone. With software, like with walking on a rope, the probability of making a mistake is pretty high. The cost of such an error may get high as well. Anyware between wasting the time of expensive workers and the actual damage to the users of the system. The reason small refactoring steps are safer is that it is easier to convince, or even to prove, they preserve the observable behavior. Thus, micro-steps significantly reduce the risk of introducing new defects.

1. I: The return on our investment is both immediate and in the long run. In the short run by almost eliminating the need to debug, and in the long run by avoiding new defects caused by a failure to preserve the exact same behavior. As it is most likely to happen with Rewrite. In both cases, we save a lot of time and money.

1. N: I understand Refactoring may be an alternative to rewrite in some cases, but in the previous episode you said refactoring is an ongoing activity that consumes a significant portion of your time. Why would you refactor code that already works and has nothing to do with the task you're working on?

1. G: Yea, you know the good old saying: “if it ain't broke, don't fix it”.

1. I: I think of refactoring as an investment. An investment of effort in the present in order to harvest the fruits in the future. Tell me, do you fold your clean clothes and place them sorted in the closet? Or do you just store the pile of clean laundry at the corner of the room?

1. S: Oh me? You bet I do, I fold it right away, I like to keep my closet super clean.

1. I: Why is that? After all, it is much faster to just drop the clean laundry at the corner of the room and use your time for doing something more significant. No?

1. N:  I prefer investing some time now rather than wasting my time later every time I get dressed.

1. I: Me too, and I assume most of us will do the same.

1. G: I keep my stuff nicely folded in the closet since otherwise, my wife will divorce me!

1. I: Oh, I see what you’re saying, we are in the same boat BTW! In general, when more than one person is involved, maintaining an agreed upon order becomes a crucial factor for the effectiveness of the group.

1. I: As for your question Newbie, you asked if I would refactor code that already works. The answer is yes, I continuously, rigorously refactor for the exact same reasons I keep my closet well organized. It saves time and effort for me and for any other developer that will ever have to read or change the code. For me, refactoring is an ongoing maintenance activity of keeping the code expressive and easy to change.

1. S: On my team, we have many automated tests, you know, like unit tests and system tests. As with all changes, when we need to rewrite or improve the implementation of some unit, we make the change in a separate branch and we only merge it into the main trunk after all the tests pass. So my question is since we already have good safety mechanisms, why should we refactor on top of that and not simply make the necessary changes as we do today? After all, refactoring is a slower method of implementing the change, no?!

1. I: I'm glad you asked. First, you don't have to refactor. As I've already mentioned, I refactor since for me refactoring is both safer and faster. Adding another safety mechanism is never a bad idea especially if it doesn't slow you down.

1. I: May I ask what do the other team members do when they need to make changes to the same files you are working on?

1. S: Sure, since we usually know what each of us is working on, and to avoid merge problems, we tend to wait for the other team member to complete their task so that we can safely add our change on top of that.

1. I: And, do you find waiting an efficient way of using the team’s time?

1. S: Obviously not. But,you know, they really could apply their changes if it's urgent, and I will handle the painful conflicts at the end when I merge my changes.

1. I: Right, and since you know the merge at the end might be painful, does it have any affect your coding habits as you make your changes?

1. S: Well, I do the minimal amount of changes so that I don't complicate the merge at the end. 
Clearly, I try to avoid any unnecessary changes that may complicate merging at the end. Duh!

1. I: So, you and all your other team members will, in general, avoid making occasional code improvements due to the fear of the complications it may impose on merging the change at the end! right?

1. S: Right, like, do you have any other suggestions?

1. I: Sure, we can avoid all that with refactoring, but before I explain how, I must say that to my experience the fear of change is a primary cause of code decay. Wherever there is fear of making improvements, for whatever reason, the code will slowly decay, the effort of adding new behavior will slowly rise until it reaches a point where it becomes unbearable. Whenever there is fear, the code will eventually rot even in the presence of safety mechanisms like unit tests.

1. I: Refactoring helps us reduce fear in several ways. First, since micro steps are a safer approach, my general confidence while making the change is higher. Second, since the observable behavior is always preserved, I tend to merge into the main branch every few minutes. Obviously, it is impossible to have a significant conflict when each of the merged changes is by itself of insignificant size. Hence, the fear of complications as a result of merging a big change is eliminated as well.

1. I: And I have one last question, with the big rewrite approach, when we have a task that may take several days or more. If due to some emergency or change in priority, you need to pivot to another task? What happens with all your unfinished work?

1. G: We keep the unfinished change in a separate branch in case we will decide to complete it in the future.

1. S: Right, but in many cases, we will never complete the task since as the days go by, the code base continues to change, and the old task becomes less relevant and harder to merge.

1. I: Right, just like Waiting, Partially Done Work is a waste we can completely avoid with refactoring.
Since I merge so frequent, I always have the option to end the refactoring activity and move on to another task without losing the effort that was already made. That’s a big advantage.

1. G: Ok, you got me onboard, or at least I'm willing to give it a try. But what should I now tell my boss? That from now on I will spend half of my time refactoring? Do you want to get me fired?!
1. S: Yea, I can't wait to see the look on our Product Owner's face when we'll tell him we can't add the new feature since we need to refactor.

1. I: Well, I would simply say nothing!

1. G,S,N: Are you out of your mind!

1. I: I'm completely sober. After all the responsibility, or even obligation for keeping the code at its best shape, is no one else's but ours. Our job is to maintain a codebase that enables the fast delivery of new features. A messy pile of code lines will always fail with achieving this goal. You're simply doing your job! And yet, in those rare cases where you still must explain your activities to your managers or the PO, I would simply suggest you have them watch this episode. If it got you on board, it may convince them as well.

1. I: Here is a short list of the advantages we've mentioned so far:

First, when compared with a rewrite, refactoring is a safer approach. If we take into consideration the time we save on debug and avoiding defects, it is also, in many cases, a faster one.

We mentioned that refactoring is an ongoing maintenance activity of keeping the code at its best shape so that we can continue delivering business value at the fastest sustainable pace.

We said that since the code is always kept valid, we tend to merge very often. This has 3 major advantages: 
First, it reduces the time we waste waiting to a minimum, 
second, it eliminates the hassle and risk involved in merging a big change. 
And third, it gives us the option to pivot to another task without losing the work that was already done.

1. N: This discussion is a little too abstract for me, I think a demo could help a lot.

1. I: Yep, I agree, thanks for reminding me, it is a workshop after all. 
In the next few episodes, we will experience refactoring in practice. 
We will start by presenting a significant code sample. Then we will discuss the code smells and clean up the mess using refactoring techniques.

1. I: It will be a lot of fun. So, stay with us. See you in the next episode.
