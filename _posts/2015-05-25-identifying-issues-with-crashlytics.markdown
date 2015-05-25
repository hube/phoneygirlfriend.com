---
layout: post
title: Identifying Issues With Crashlytics
date: 2015-05-25T15:28:09+08:00
author:
---

![](/assets/2015-05-25-identifying-issues-with-crashlytics/crash-graph.png)

In Phoney Girlfriend 0.6.2, we introduced an analytics library called
[Crashlytics](https://get.fabric.io/crashlytics) (now a part of the
[fabric](https://get.fabric.io/) suite of tools offered by Twitter). Crashlytics
has already helped us identify a major issue that has been affecting users for
quite a while now.

<!--more-->

The graph at the top of this post shows the number of users using Phoney
Girlfriend who have **not** experienced a crash. As you can see, that number was
quite low (as low as 30.8% on May 5) until we released version 0.6.5 on May 8.

How could we let almost 70% of our users experience crashes for so long? The
number one reason why is because we didn't know about it! We rely on many
different sources to identify issues in PG: user reviews on
[Amazon](http://www.amazon.com/Baller-Industries-Phoney-Girlfriend/dp/B00QYCGVQK),
[Flurry analytics](http://www.flurry.com/), and manual testing. Somehow, each of
these sources failed to surface the issues our users were experiencing.

Looking back, there are several reasons these crashes went unnoticed:

1. The major source of crashes occurred in a non-user facing component. When the
  app crashed, the user likely didn't notice that it happened. We never saw any
  reviews reporting such an issue.
2. These crashes weren't reported by Flurry. Flurry's error logs show only a
  small number of issues that affected less than 200 users.
3. We have never been able to reproduce this issue when testing. Or perhaps like
  our users, we never noticed these crashes when testing.

Fortunately, now that we have Crashlytics reporting issues like this, we can
begin to investigate and fix these crashes. As you can see in the comparison
below, the vast majority of our users no longer experience a crash in version
0.6.5.

<table>
<tr>
<td markdown="1">
[![][crashes-0.6.4]][crashes-0.6.4]
*There were over __10,000__ reported crashes in 0.6.4 affecting __1055__ unique
users*

[crashes-0.6.4]: /assets/2015-05-25-identifying-issues-with-crashlytics/crashes-0.6.4.png
</td>
<td markdown="1">
[![][crashes-0.6.5]][crashes-0.6.5]
*There are only __125__ reported crashes in 0.6.5 affecting __97__ unique users*

[crashes-0.6.5]: /assets/2015-05-25-identifying-issues-with-crashlytics/crashes-0.6.5.png
</td>
</tr>
</table>

Crashlytics has already helped us identify and address a major issue affecting
our users. In the future, we can look forward to a more stable, more reliable,
crash-free Phoney Girlfriend!
