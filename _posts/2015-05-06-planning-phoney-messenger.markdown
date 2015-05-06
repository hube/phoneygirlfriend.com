---
layout: post
title: "Planning Phoney Messenger"
date: 2015-05-06T16:13:37+08:00
author: Angus Cheng
---

In a previous post I introduced Phoney Messenger. We aim to use as much of the code from Phoney Girlfriend as possible, but certain things have to change. Hubert and I still haven't worked out exactly how to deal with the changes so I'm going to brain storm a few ideas here.

<!--more-->

**User Interface**

We need to be able to switch between situations in Phoney Messenger. One way to do this is to have a World list, which then lets you pick a character list and then finally a chat list. 

[Image of the various views with arrows]

Is this too confusing? Adding in a whole new UI screen complicates the user interface by quite a lot. I like minimising the number of taps. Another idea I had was to allow sliding left/right at the Chat List to change the situation. Will people know to do this?

[Image of three chat lists, middle chat list has arrows on it indicating it slides over to another chat list]

**Script Changes**

Scripts in Phoney Girlfriend assume there will only be one character talking to you, but Phoney Messenger scripts will always have more than one. How do we deal with this? We could define up front how many characters are in a script, and then in the script have nodes that define character changes.

[Screenshot of XML file with character list up front]
[Screenshot of XML file with CharacterChange node]
Do we allow replying to multiple characters in the same world at the same time? Do we restrict it so that you can only reply to one character per world to progress the script? 

Do we want to include integers th at are incremented and decremented? So that we can add in if statements to control the flow of the story? 

Hubert and I are 1337 programmers, so we could go for the most general solution, but that means more coding work, more testing work and an increased chance of bugs.

**Voting for scripts**

We want Phoney Messenger to be a successful app on it's own, but we have an ulterior motive. We want to figure out what scripts are popular and then release a stand alone game based on that script.
That means it wouldn't be fair to have free scripts and locked scripts in Phoney Messenger. Obviously the free scripts would get more attention and therefore be more likely to get more votes. The fair thing to do is unlock all the scripts. If we do that, we'll have to make money another way. 
One obvious idea is to place ads in the app, lately it seems like advertising can be quite a good way to make money. Another option is to allow users to vote on an script with real money. Someone might say "Yes I really love this script, I'll donate $5 so that I can see it become a real game". Will people pay even if they don't need to?