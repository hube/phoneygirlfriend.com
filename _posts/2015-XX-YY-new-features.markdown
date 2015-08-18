---
layout: post
title: New Features
date: 2015-XX-YYT13:37:00+08:00
author: Angus Cheng
---

Phoney Girlfriend has stayed pretty much the same for about a year, we've added in new content and released to iOS but the gameplay hasn't really changed. So here's some new features we're considering.

**Variables**

These are really cool, even if we only implement numbers and booleans. Right now, our scripts don't really have a memory of what the player did. One example is we could create a money variable, and if your money is above a certain amount, you can do different things. You can also do different stuff to gain more money in the script.

Another thing is we can set booleans to determine what the player has done. So if the player says he has a dog, we'll set:
<pre>has_dog = true</pre>

Then later the NPC can say "Hey how's you're stupid dog?". This is pretty cool, it allows writers to create cooler more realistic scripts.

**Multi Line Player Messages**

When I'm playing Phoney Girlfriend, I feel flooded by the NPC. I don't get a chance to write too much. That can be changed with multi line Player Messages, and decisions that don't explicitly say what will be typed.

<pre>
Brenda: Hey Angus how's it going?

1) Good
Angus: Good
Brenda: Nice

2) [Talk about something else]
Angus: Brenda!
Angus: I don't have time to answer
Angus: There's a raptor chasing after me as I type
Angus: Oh God!
Angus: It's getting closer!!!
Brenda: Stop moving! Raptors can only see you when you move.
</pre>

This could be more fun, it gives the script writers more flexibility with what can be written, and attaches more character to our players.

**Group Chats**

Right now you can only chat with one character per script. We actually have the capability to change this, so that you could be part of a group chat of two or more Phoney Characters. To do this wouldn't be super hard, we'd just need to get our script writers to write such scripts.

**Online Gameplay**

This is a really cool feature, but I'm not sure how to make it work entirely. The plan is to create a script where to real people will chat with one or more phoney characters. For example we create a script where Angus and Hubert are talking to Phoney Brenda. 

<pre>
Phoney Brenda: Hey Angus, what have you been doing today?

Angus
1) Spend the day looking out the window.
Phoney Brenda: Yes... there's a lot great stuff outside of windows.

2) Ate bananas.
Phoney Brenda: Good good, that's good.

3) Wrote some brilliant code.
Phoney Brenda: Yeah right!

Phoney Brenda: What about you Hubert? What did you do?
Hubert
1) Hubed all day
Phoney Brenda: Great!

2) I was going to Hube, but didn't have time.
Phoney Brenda: You should make time for Hubing.
</pre>

So the idea is, Hubert and I will be both talking to Brenda, this will require an internet connection to send out the messages I choose to Hubert, and to receive the messages Hubert chooses. Another great thing about this feature is it encourages users to get their friends to play.



