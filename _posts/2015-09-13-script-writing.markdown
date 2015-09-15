---
layout: post
title: Create a Phoney Girlfriend
date: 2015-09-13T13:37:00+08:00
author: Angus Cheng
---

A lot of people are interested in writing scripts for Phoney Girlfriend. It's not that hard, but there's a few things you need to know.

**Terminology**

*NPC* - Non Player Character, the girlfriend or the boyfriend. The player receives messages from the NPC.

*Player* - The person playing Phoney Girlfriend. Player messages are messages that the player can choose from for a response.

**Use Google Drive**

The scripts for Phoney Girlfriend are pretty long, each one is about fifteen thousand words. It takes a while to create one script. We review all the scripts, and becasue of this we want to read them as you write them. We also want to add in comments and suggest edits. [So Google Drive is a must.](https://drive.google.com)

**Biography**

![](/assets/2015-09-13-script-writing/biography.png)

The script starts off with your character's biography, this text is shown in the purchase screens inside Phoney Girlfriend. It also includes the initial profile picture you would like to use.

**Message Blocks**

![](/assets/2015-09-13-script-writing/message_block.png)

A message block starts off with a message from an NPC, followed by messages the player can choose to select. These messages can branch out further. We branch out to at most three levels.

**Picture Messages**

![](/assets/2015-09-13-script-writing/picture_message.png)

State the message number, then include the text "PICTURE MESSAGE", then import in the image you want to use. Picture messages are usually followed by a message block related to the picture.

**Voice Messages**

![](/assets/2015-09-13-script-writing/voice_message.png)

Write the message number, then include the text "AUDIO MESSAGE". You then write what the character says in the voice message, include the tone and any sound effects you would like included. We pass this text over to our voice actors and they'll use this to figure out how to act out the audio message.

**Update Profile Picture Nodes**

![](/assets/2015-09-13-script-writing/profile_pic.png)

Write the text CHANGE PROFILE PICTURE and include the picture you want it to be changed to. Profile Pictures must be square images like 640x640 and they cannot have borders. 

**Pipe characters**

We use pipe character to break up longer messages into multiple messages.

![](/assets/2015-09-13-script-writing/npc_pipes.png)

The above text will break out into four separate messages.

<pre>
People are dancing.
The tunes are bumpin’.
Everyone’s getting drunk.
Some girl lost her shoes trying to twerk on a table, ha ha.
</pre>

![](/assets/2015-09-13-script-writing/player_pipes.png)

Pipes are use to break out Player Messages too, but the first message appears as an option to the player when they are selecting responses, and the following messages come in automatically. So you need to craft the messages so that the first message makes sense on it's own. In the above example

<pre>
It’s going well… [This text is what the player selects]
Kinda hungover, though.
But don’t worry, nothing serious.
</pre>

**Delays**

![](/assets/2015-09-13-script-writing/delay.png)

Every four messages or so, it's good to add in a delay ranging from 15 minutes to 2 hours. We don't want any delays larger than two hours. We do this to keep things realistic and build up anticipation.

**Descriptive Player Messages**

![](/assets/2015-09-13-script-writing/descriptive_pm.png)

These are player messages that don't explicitly say what the player is going to write, but gives them an idea of what to expect. In the above example the player will see the first mesasgage "(Flirt with her)". When they select that option, the text "(Flirt With Her)" will not be written out as a message, instead the following message "You in that bikini yet? ;)" will be written.

**Do Not**

Don't mention companies, brand names, trademarks or famous people.

**Highlighting**

If there's a section you're worried could be too risque/offensive, select it and add in a comment so I can help you decide. I will read the entire script, but it's best to point these sections out to me.

**Full Example Script**

[Click here](https://docs.google.com/document/d/1SjNY4zXQyXby6ZN9QYZUvAYVYsK0EQAWgHDbDWqQgAc/edit?usp=sharing) to check out Leilani's full script on Google Drive.



