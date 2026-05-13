---
title: Making Windows ClickLock useable

---

# Making Windows ClickLock useable

## TL;DR

Want visual or audio feedback (or both) when Windows locks the mouse for you? Head to [ClickLockIndicator on github](https://github.com/kmcnaught/ClickLockIndicator) and download straight from the [releases page](https://github.com/kmcnaught/ClickLockIndicator/releases)

## Introduction

In using desktop software, you're often expected to click a mouse button, hold it down, and move the mouse - to perform a drag action. This is an extremely common interaction in most software, but one that can be very difficult for someone with a disability who might use an alternative pointing device, or find it difficult to maintain pressure on a button while moving a mouse. 

Most operating systems offer a setting called "Click Lock" or "Drag Lock" or similar, which allows you to 'lock' your mouse down while you move the cursor, breaking up the drag into a long click, a move, and another click. Just hold down the mouse button for a certain (configurable) amount of time, and it will lock it for you. Click again to release. 

To turn this on in Windows, search for "Lock mouse button on long click", go to Settings -> Accessibility -> Mouse pointer and touch -> Mouse (not "Mouse pointer and touch") -> Click Lock, or click the following direct link to [Mouse accessibility settings](ms-settings:easeofaccess-mouse).

Why is this worth a blog post? Well, I've known about this setting for decades. On many occasions I've suggested it to individuals. In the process of looking up how to turn it on, I usually turn it on myself and check it will work for their situation. 

I then leave it on by mistake and it keeps inexplicably infuriating me - turning on when I don't want it, not turning on when I do, and generally causing more trouble than it's worth. While I'm sure some people learn to benefit from it, I'm left wondering whether my recommendation actually helped, or just added confusion and unpredicability to a user's assistive tech setup. But it should be so simple, right?

I was working with an individual for a while, and iterating on various parts of her setup. We reflected on **why** the ClickLock was not being as useful as it might be, and realised that there is **zero user feedback** on its current state. Is it switched on, and you just haven't held your mouse down for long enough, or did you turn it off by mistake (or perhaps deliberately, in a fit of late night rage?). If you do perform a manual "hold down and drag" action yourself, how do you know if letting go of the mouse button will release the object or keep the mouse locked down?

## First solution: AutoHotkey

If someone is already happy using [AutoHotkey](https://www.autohotkey.com/) scripts, they make an excellent test ground for small self contained accessibility hacks. We wrote 2 scripts, each of which starts a timer when you hold down the mouse, and if you reach the designated *amount of time mouse button needs to be down to lock* then it gives you feedback. One script plays a system chime when the lock engages, and when it releases. The other script displays some overlay text next to the cursor. You could use either script, or both, and they would just run in the background giving you the feedback you wanted. 

This was useful enough it became part of the individual's standard setup, proving it was useful. But I think you'll agree it's not the prettiest, and not great for sharing with others.

![Dragging a MakeCode block with ClickLock, showing CLICKLOCK ACTIVATED 3 times next to mouse cursor](/images/click-lock-ahk.gif)

## Final solution: Standalone app, written by AI

This was an excellent small piece of work to offload to AI - the scope is small, the result easy to test. I had a chat with Claude Code about the goal, gave it the existing AutoHotkey scripts as a starting point, and brainstormed some UI improvements to squeeze in. There were a few issues along the way, but with some mild supervision we soon had a standalone portable app built in C#.


Run the app, and optionally get it to register to be launched on startup. Now, any time you hold the mouse down for more than half the configured lock time, it will start a visible "charging" animation to show you how much longer you need to hold it for (or warn you to release if you *don't* want it engaging). Once locked, the fully charged ring changes colour and stays up, until released. Optionally, it can make an accompanying 'click' noise whenever it engages or disengages. This is much cleaner visually than the AutoHotkey version, and feels really natural. Since building the app 3 weeks ago I've forgotten to turn off ClickLock on my own machine, and I actually like it! 

![Dragging a Scratch code block with Click Lock indicator, showing a charging animation](/images/scratch-click-lock.gif)


## Closing thoughts

Program state hidden from the user is so often a barrier to adoption. When behaviour is different in different scenarios, we call this a "mode". Modes can be powerful, but only if a user feels in control. This was a great example of an accessibility option that *technically* did the right thing, but the *user experience* prevented it from actually being used. But because it seemed like such a simple thing, it took a long time before I realised something was missing. In the end, the fix was tiny!





