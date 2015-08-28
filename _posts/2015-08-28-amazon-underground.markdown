---
layout: post
title: Amazon Underground
date: 2015-XX-YYT13:13:00+08:00
author: Angus Cheng
---

[Amazon has a pretty cool new monitization strategy for their app store](https://www.amazon.com/gp/feature.html?ie=UTF8&docId=1003016361&ref_=mas_surl_undrgrnd). They're willing to pay 0.2¢ for every minute a user spends in your app. What's the rationale behind it? I guess it's that developers should be rewarded for getting people to use their device. Will it work out for us though? What will be better for us IAPs or Underground?

**July 28 to August 25 Sales**

<pre>
Phoney Girlfriend - $1262.14 USD
Phoney Boyfriend - $35.58 USD
</pre>

Alright great, so let's divide those sales results by $0.002 to figure out how many minutes of play it'll take to match these sales results.

**How much time?**

<pre>
Phoney Girlfriend - $1262.14 / $0.002 = 631,070 minutes
Phoney Boyfriend - $35.58 / $0.002 = 17,790 minutes
</pre>

That seems like a lot, but that's over the course of a month. Immediately it becomes obvious that Phoney Boyfriend is more likely to benefit from this business model. So let's not crunch any more numbers for Phoney Girlfriend.

**Hypothetically**

Ideally we would know how many minutes were spent in our app in the sales period, and then we could simply multiply that by 0.002 and we'd know whether Amazon Underground would be good for us or not. Sadly we don't know how many minutes of Phoney Boyfriend were played. We do have the **Daily Active Users** and the *Time In App Per User** per day. 

Let's multiply those two values together, total them up and bam we'd have the total minutes value we were looking for.

![](/assets/2015-08-28-amazon-underground/excel.png)

30,149 minutes of Phoney Boyfriend were played which would get us:

<pre>30149 * 0.002 = $60.30 USD</pre>

That is a lot better than $35.58, it's pretty fair to say that we will get significantly more traffic for being one of the first Amazon Underground apps so we should be more profitable using the Underground business model. There is a bit of work involved with migrating Phoney Boyfriend to Underground, but at least in theory it should be a better model.



