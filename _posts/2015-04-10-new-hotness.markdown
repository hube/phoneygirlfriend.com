---
layout: post
title: "New Hotness"
date: 2015-04-10T10:38:37+08:00
author: Hubert Lee
---
We've been working hard on the next version of Phoney Girlfriend and Phoney
Boyfriend. Here's a small preview of what's coming in the next update.

## New Characters
We're introducing two new girlfriends and one new boyfriend in the next update.

<table style="table-layout: fixed; width: 100%; border-spacing: 1em;">
<tr>
<td markdown="1">
![Alexis](/assets/2015-04-10-new-hotness/alexis.jpg "Alexis")
</td>
<td markdown="1">
![Sofia](/assets/2015-04-10-new-hotness/sofia.jpg "Sofia")
</td>
<td markdown="1">
![Andy](/assets/2015-04-10-new-hotness/andy.jpg "Andy")
</td>
</tr>
<tr>
<td markdown="1">
_**Alexis** is a 21 year-old student. She is a pretty girl who is geeky and kind of shy._
</td>
<td markdown="1">
_**Sofia** is a 24 year old nurse. She’s an intelligent and confident young woman who loves her job._
</td>
<td markdown="1">
_**Andy** is a heartthrob of a fitness model with a little bit of a bad boy side._
</td>
</tr>
</table>

## Characters Taking Time Off

<table style="table-layout: fixed; width: 100%; border-spacing: 1em;">
<tr>
<td markdown="1" style="width:30%">
![Airport Gate](/assets/2015-04-10-new-hotness/airportGate.jpg "Airport Gate")
</td>
<td markdown="1" style="width:70%">
* Aloria, Ashley, and Jenny are taking a break from Phoney Girlfriend
  * Ashley and Jenny will still be available if you previously purchased them
  * Aloria will still be available if you started a conversation with her, but
    you won't see her any more if you reset your app
* Angus is now available exclusively on Phoney Boyfriend
  * Angus will still be available on Phoney Girlfriend if you previously
    purchased him
* Angus and James now have trial modes enabled
</td>
</tr>
</table>

## New Features

### Android Download Manager

<table style="table-layout: fixed; width: 100%; border-spacing: 1em;">
<tr>
<td markdown="1" style="width:70%">
We're now taking advantage of Android's built-in
[DownloadManager](https://developer.android.com/reference/android/app/DownloadManager.html)
to download character content packs. This means that we can more reliably
download content and we can perform downloads in the background, so you can
start your chat immediately!

The old download system we were using was based on Android's
[AsyncTask](https://developer.android.com/reference/android/os/AsyncTask.html),
which, though well-suited for background jobs, raised exceptions when the
hosting activity was paused (e.g. the user backed out of the Activity or another
app came to the foreground).
</td>
<td markdown="1" style="width:30%">
![Old dialogs](/assets/2015-04-10-new-hotness/download-progress-dialog.png "Old dialogs")

*Goodbye download progress dialog!*
</td>
</tr>
</table>

## Living in a Material World
Last June at [Google I/O](https://www.google.com/events/io), Google announced
its newest UI paradigm,
[Material Design](http://www.google.com/design/spec/material-design/introduction.html),
which launched with the latest Android 5.0 devices in November. Material Design
has now arrived for Phoney Girlfriend and Phoney Boyfriend! We've refreshed many
UI elements to stay up-to-date with this new design.

<table style="table-layout: fixed; width: 100%; border-spacing: 1em;">
<tr>
<td markdown="1" style="width:50%">
![New dialogs](/assets/2015-04-10-new-hotness/material-dialogs.png "New dialogs")

*Material style dialogs*
</td>
<td markdown="1" style="width:50%">
![New App Bar](/assets/2015-04-10-new-hotness/material-app-bar.png "App Bar")

*Material style App Bar*
</td>
</tr>
</table>

## Feature Requests
Are there any features you'd like to see in the next update? Any bugs that have
been frustrating you? Send us an email at <phoneygirlfriend@gmail.com> to let us
know!
