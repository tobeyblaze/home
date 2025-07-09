_July 2025 Publication Note: I originally wrote and published this as an internal document for a previous employer. I've removed links and references to the company but otherwise didn't edit the content_

# Guide to Pairing during CTF

Created by Tobey Aumann | Last updated: May 25, 2021 - **12 min read**

### TODO “[CTF Pairing Success Planning Sheet]()”

## What is a CTF

Capture the Flag (CTF) in computer security is an exercise in which participants attempt to find text strings, called "flags", which are secretly hidden in purposefully vulnerable programs or websites. A capture the flag event is a great chance to learn about cybersecurity, to explore problems and publicly available resources to solve them, and get to know someone new. Here’s how it will work here: over the course of a week, you’ll spend 2-3 hours with a teammate from somewhere around the company. Together, you’ll look over a list of modules and decide which ones appeal to you most. Then, you’ll tackle the challenge -- your collaboration will let you use a system’s vulnerability to dig in and find the flag. It’ll be fun.

Working in pairs, you’re trying to solve as many problems as possible within your 2-3 hour pairing session. It doesn’t have to happen all at once, but it does have to happen -- every engineer is required to participate, as per our compliance requirements. 

As noted in the guide, you’re also going to be partnered, when possible, with someone who has domain knowledge in a totally different area from yours. That means that if you’re mostly a frontend engineer, your partner might be an SRE, or more backend focused. It’s a great way to get to know colleagues you otherwise might not meet.

How you hack is up to you. But where do you start?

## Getting Started

Pair programming can be stressful even with people you do know.  Pairing is an intense social interaction, which can be amplified by competition, even in this no-stakes, light-hearted version. To take the edge off, remember the goal: Complete the event. And if you’ve got questions, we’ve got a Slack channel for that #2021-ctf. For up to date information on the event’s logistics, check [the official guide]().

### Break the Ice

When you’re working with someone new, it’s a good idea to plan ahead. Break the ice ahead of time, start figuring out where each of your strengths are, and then write up a solid strategy for your work together. 

Start with something easy but useful. For example...


- Role + Team + Where in the World
    
- Favorite beverage while working
    
- How long have you been with the company?
    
-  Boring fact
    

**Mind the Learning Edge**

Start by being honest about what you’re looking to get out of the CTF. Are you looking to fast track your learning and feel compelled to SOLVE ALL THE THINGS? Or would you rather learn a thing or two without getting too stressed about how many points you get? It’s important to be clear with yourself going into the exercise so you can manage your own expectations as well as your partner’s. After all, you want to have a good time, and also to feel like you achieved something here. That starts with being on the same page. Be ready for some surprises, too -- even if you’ve been in the field for over a decade, there’s always something new to learn.

**Strengths and Preferences**

- What I’m looking to get out of this event
    
- Areas of expertise
    
- What I dabble in
    
- Pairing style preference (if any)
    
- Modules that look interesting
    

### Choose an approach

It’s not always easy to get in a rhythm with someone you’ve just met. For smoother sailing, decide what kind of pair you’ll be in advance. Decide on a process. Write it down and refer to it as you go. 

#### Pairing Styles

- Decide who’s going to start out as the driver (they’ll type) and who’s the navigator (the person seeding the ideas), so the ideas go through you both.
    
- Switch up who drives and who navigates, with the help of a timer.
    
- Make sure you’re using the same **definitions** of Driver and Navigator - you can use this handy chart to see which style suits you best:
    

Driver/Navigator Definitions - Pick One 

|   |   |   |
|---|---|---|
||Driver|Navigator|
|[Traditional](https://tuple.app/pair-programming-guide/styles#drivernavigator)<br><br>Most common|The person at the wheel, i.e. the keyboard. They are focused on completing the specific goal at hand, ignoring larger issues for the moment.<br><br>When driving: dictate aloud what you’re doing and why.|When navigating: ask questions rather than making demands. Leave the details of the coding to the driver.  Park next steps, potential obstacles, and ideas in a shared doc or chat to discuss at the next switch.|
|[Strong Style](http://llewellynfalco.blogspot.com/2014/06/llewellyns-strong-style-pairing.html)|Driver as Typist: For an idea to go from your head into the computer it MUST go through someone else's hands. Let the navigator tell you exactly what to type. It’s okay if you don’t understand why right away. Wait until the next switch.|For an idea to go from your head into the computer it MUST go through someone else's hands.<br><br>When navigating, give instructions to they typist at the highest level of abstraction they’ll understand.|

Even if you don’t typically use Strong Style pairing, it is particularly suited to the conditions of this CTF. You can read more about [how this method solves some of the common problems in pairing](http://llewellynfalco.blogspot.com/2014/06/llewellyns-strong-style-pairing.html#:~:text=%20this%20method%20of%20pairing%20is%20it%20solves%20many%20of%20the%20common%20problems%20i%20see%20occurring%20with%20pair%20programming), particularly the “1 person working, 1 person watching” problem.

_Note: There’s a third common style “Ping Pong” where the Navigator writes the test and the Driver writes the code to make it pass, but that’s not as relevant to a CTF where there’s no long lasting code, so we won’t delve into it here._

#### Working Agreements

Take a few minutes to agree on the details. A common workflow is:

1. Review the problem - agree on the high-level goal out loud.
    
2. In a shared doc, break the work into a handful of tasks and prioritize them. During the session, you can use this doc as a parking lot for ideas to help maintain focus.
    
3. Start the timer, picking up the first task.
    
4. Switch keyboard control and roles regularly (begin by aiming for at least one swap per module.)
    
5. Spend a few minutes after each module reflecting on the experience, i.e. a micro retro.

6. First, discuss what went well.
    
8. Then, consider what would make the next session 1% better.
    
9. Possible areas for improvement:

10. Focus: did distractions sneak in?
    
11. On a scale of 0-10, I’m getting what I want out of the CTF
    
12. Communication: were there long stretches of no talking?
    
13. Pacing: did the session feel like a grind at any point?
    
14. Division of responsibility: did you split the work up well?
    
15. Documentation: can we share how we solved the problem?
    

  

Take Breaks

Make sure you take breaks -- whether together or apart -- at the same time. You might miss out on some great ideas. You’ll also have to spend time getting the other person up to speed. Note them down.

#### Tech Check - Avoiding Technical Difficulties

In a recent survey about pairing, someone commented that part of the pleasantness of remote pairing is avoiding one of the famous pitfalls of side-by-side pairing, namely “the hell that is dealing with other people's computer setup. (Where's my Emacs foot pedal at?)”

That said, doing a quick tech check up front can save a lot of teeth-gritting friction.

### Tech Check

How will we share a keyboard?
    

- [Requesting or giving remote control](https://support.zoom.us/hc/en-us/articles/201362673-Requesting-or-giving-remote-control)
    
- [Live Share in Visual Studio](https://code.visualstudio.com/learn/collaboration/live-share)
    
- _git handover_ with  [GitHub - remotemobprogramming/mob: Tool for swift git handover.](https://github.com/remotemobprogramming/mob)
    
- other
    

Which editor will we use?
    

- Might be obviated by how the keyboard is shared
    
- Where will we whiteboard and jot down notes?
    

- Zoom Whiteboard
    
- [Excalidraw](https://excalidraw.com/)
    
- [Mural.co](https://www.mural.co/)
    
- etc
    

- What other tools/utilities should be installed or bookmarked? e.g. Wireshark
    
- How will we keep time for swaps / breaks?
    

- Whose phone?
    
- [MobTimer](http://mobtimer.zoeetrope.com/) website
    
- [GitHub - pluralsight/mob-timer: A mob programming application](https://github.com/pluralsight/mob-timer) electron app
    
- other
    

  

#### Learning Edge Re-visited

Last but not least, remember that the CTF experience is a group effort. Now that you know more about what you’re trying to accomplish and how you’re going to work, consider what you need to keep yourself in the zone. By sharing what each person needs, you can help each other be your best selves and get the most out of the team as you complete this challenge together .

## Conclusion

You’ve got this!

Given the inherent time and social pressures, it may be tempting to divide and conquer. Before you forfeit the opportunity to learn in the relative safety of CTF, consider this to be practice for the next incident where you might not know all the answers. Or, much more likely, the next time you’re exploring a new technology or particularly dark and dusty corner of a code base.  Embrace your beginner’s mind and build some empathy for your colleagues who are also learning something new.

And don’t forget to take breaks...

## FAQ & Troubleshooting

### 1 person working and 1 watching

If your navigator isn't engaged then you really are not even pairing. With Strong Style pairing, this is literally impossible - the only way for that to happen is for both people to be doing nothing.

The other way we disengage is to try to do something at the same time, like research. Researching techniques and methods is part and parcel of CTF challenges. However, browsing search results together on the same screen is usually both boring and not very effective.

One way to approach this is:

1. Together, brainstorm a list of questions and possible sources for those answers (e.g. particular websites)
    
2. Set a timebox - 10min might be long enough for these short challenges
    
3. Split up. Be explicit about whether you’re dividing up the questions, or trying to find answers for the same questions separately.
    
4. Regroup and share what you found.
    

### I’m pairing with someone with less experience

That junior developer is probably quite intimidated. After all, you really know what’s up, and they don’t. However, you have a great opportunity to help them develop their skills quite efficiently. So get excited. Then let the teaching begin. 

  

Ask the junior person questions so they can crack the code themselves. Let them type, move the mouse, etc etc. It might take twice as long, but you’re helping them learn the ropes. Don’t stop them from making the wrong move, and when they hit a roadblock, help them understand why. In the case of CTF, spelling it all out might reveal a different attack surface or vector, leading to a simpler solution. Your company will thank you.

  

Bonus: They might even make you think -- they’ll bring new perspectives to the table, and ask questions you haven’t considered since you were in their position. That’s a great time to figure it out together, and to show your pair how you problem solve. Don’t be afraid to say “I don’t know” -- it starts you on the road to research, and lets them know everyone has more to learn. 

Part of working together is taking breaks to keep the good ideas flowing. Ask your pair about their areas of expertise. Let them teach you something about a subject that interests them, and give them a chance to feel more equal. It’s key to encouraging people to stick around. Remember, you may both be experienced, but in completely different areas.

### I’m paired with a giant wizard, or at least someone more experienced

It’s your lucky day! You’re about to learn from someone who really knows what they’re doing. Don’t be intimidated, you’ve got lots to contribute, too. And they’ll be impressed by your enthusiasm, so dive right in. Get your fingers on the keyboard and start thinking about what needs to happen. Ask questions, take risks, and don’t be afraid to be wrong. You both know you’ll be slower at this, but you want to build out your judgement and knowledge for this time and beyond. Be open to seeing what you’re doing right, and where you’ve gone wrong. You’ll likely be sharing new perspectives and have approaches to offer that your pair hasn’t thought about in years, if ever.

Ask questions and tell them what you notice -- you may wind up pointing out design flaws and other inconsistencies that are well worth both of your attention. At the same time, be open to having your pair point you in the right direction and helping you grow as you go. You’re learning how to tackle challenges here and beyond. Remember, everyone has a lot to learn. You may both be experienced, but in completely different arenas.

Bonus: Part of working together is taking breaks to keep the good ideas flowing. That gives you a chance to get to know each other and share more about your hobbies, broader expertise and beyond.

### We’re both relatively experienced but in completely different areas

While it may be tempting to divide and conquer, you’ll forfeit the opportunity to learn in the safety of CTF. Think of this as practice for the next incident where you might not know the answer. Embrace your beginner’s mind and build some empathy for your colleagues who are also learning something new. Check out the sections on pairing with someone more and less experienced for ideas.

### WE BOTH LOVE TO TYPE

It’s more than likely that you’ll each have different ideas on how to implement something. Using the strong pairing style reframes the conversation. Instead of wanting to grab the keyboard and shut the other person out, it encourages you to let go of the keyboard and communicate your idea to your pair.  That’s a way better dynamic, and it creates a space where you can more comfortably share ideas while accomplishing the task at hand. 

### What if I’m not a strong coder?

Speaking from my own pairing experience as someone who can read code but not write it, don’t underestimate your contribution.

- Understanding the problem. Read through the module and play back to each other how you understand it. This is where you’ll catch any hints that have been dropped about where to look for the flag. It’s also the time to check potential misunderstandings of where the flag
    
- Brainstorm potential solutions. You can either do this together, or split up and then present your ideas to each other. This depends on how well-defined the solution already is, but also on your individual styles. Some people like some time to think by themselves, others like talking things through out loud while they are thinking. If one of you is less familiar with the domain or tech, take some time to share the necessary context with each other.
    
- Share your story. There is often more than 1 way to capture the flag, and comparing notes later is a lot easier if you have notes you can share that show what your pair tried, regardless of success.
    

More at:

- [Pair Programming Antipatterns](https://tuple.app/pair-programming-guide/antipatterns)
    
- [Pairing with Junior Developers | Tandem](https://madeintandem.com/blog/2015-1-pairing-with-junior-developers/)
    
- [How to pair with a junior developer](https://tuple.app/pair-programming-guide/how-to-pair-with-a-junior-developer)**
