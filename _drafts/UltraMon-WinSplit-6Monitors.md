---
title: UltraMon + WinSplit + 6 Monitors = Happy!
date: 2014-08-31 00:00:00 Z
layout: post
author: Brian Boatright
excerpt: My 10yr Multi-Monitor Evolution
---

## Shouldn't Windows be renamed Mousy's or Fingers?
Is it just me or is it beyond contemp in 2014 Windows 8.1 that you must pay $30-40 for a program to enable the manipulation of WINDOWS via keyboard shortcuts in a operating system named... "Windows"! Since Windows 7 and Aero you could "snap" windows to a specific area of the screen or use the Win key plus your arrows to snap them left, right, or full screen. But do to anything more you need a third party app like Win-Split Revolution (free), Ultra-mon ($35), or some other window manager. Maybe the os should have been called "Mousers" or today may "Fingers" because that's what they seem to be focused on. I type fast and anytime I move away from my keyboard to move a window I am wasting time. Having multiple monitors is awesome for productivity, especially when you get size of them and can just park an automatically updated status screen, or trello, or just a document you need to reference while working on something else. I never thought when I got three screens that I would need six, but now that I have six I want more! More screens equals less time moving windows and screens and the video cards they need are getting cheaper and cheaper. 

## My 10yr Multi-Monitor Evolution

So I've had multiple monitors for over 12 years, it started out with three 15" avidav and a ergotron triple monitor stand. I never liked having a single screen to the side, my OCD wouldn't allow it. So I started out with three!

That worked for a few years and then I replaced those Avidav 15" with three Samsung 204B monitors. The 204B is one of my favorites but are really heavy. After about 5 years of use I had to replace most of the caps in all three of them. Considering I paid about $250 ea and $25ea in replacement caps, I'm quite happy with them. In fact I still use two of them in my current setup, in portrait mode.

My current setup is a single 30" Dell as my main with a 204B (20") in portrait mode on each side. I had this setup for about six months before I learned that I could use one of my older video cards and run three more monitors, how awesome! So I found a deal on some new Dell 24" on eBay and those are sitting above the others. My stand is one I found on Amazon for a few hundred that allowed me to stack them. I was using a XTC stand but they do not sell the monitor arm by itself and to buy another would cost the full amount. That said they are the best triple monitor stands you will find. The individual adjustments for each monitor is perfect.

Enough gloating. My friend and business partner Mike, told me about two programs to help manage windows in a multi-monitor setup. He uses both, but until recently I was only using Win-Split. The feature I was looking for just in not possible in the current verison of Win-Split. What I wanted was a shortcut to move the active screen to a specific monitor. When you have more than one, you waste a lot of time moving windows around. That's when I started researching Ultra-Mon and found it had scripting and in fact there was already a script that would Move the Active Window to a specific monitor.

## Win-Split Revolution
Win-Split is a great programa and it is free to use for non-commercial use. My company purchased a license for each of our employees when we started using it on a more perfmament basis. 

Basically Win-Split allows you quickly move and resize the active window  into a specific section of your monitor with a hotkey shortcut. The layouts and hot keys are customizable. Check out [Win-Split Revolution window manager](http://winsplit-revolution.com/).

## Ultra-Mon
UltraMon is capable of doing everything that Win-Split does but it was created long before Win-Split and had a different purpose in mind. 

#### Setting Up Ultra-Mon to reproduce Win-Split Functionality

##### My Win-Split Revolution Layout Setup
Down Left - 50%, 33%, 66%
Down - 100%, 33%77
Down Right - 50%, 33%, 66%
Left - 33%, 66%, 50%
Middle - 66%, 50%, 100%
Right - 66%, 50%, 33%
Up Left - 50%, 33%, 66%
Up - 100%, 33%
Up Right - 50%, 33%, 66%

##### My Win-Split Revolution Hotkey Settings
Down Left	- Ctrl+Alt+**Numpad(1)**
Down		- Ctrl+Alt+**Numpad(2)**
Down Right	- Ctrl+Alt+**Numpad(3)**
Left		- Ctrl+Alt+**Numpad(4)**
Center		- Ctrl+Alt+**Numpad(5)**
Right		- Ctrl+Alt+**Numpad(6)**
Up Left		- Ctrl+Alt+**Numpad(7)**
Up			- Ctrl+Alt+**Numpad(8)**
Up Right	- Ctrl+Alt+**Numpad(9)**

Mosaic - Ctrl+Alt+**M**
Fusion - Ctrl+Alt+**F**
Tools - Ctrl+Alt+**T**
Maximize Horizonatilly - Ctrl+Alt+**H**
Maximize Veritcally - Ctrl+Alt+**V**

##### Ultra-Mon Hotkey Settings
User the MoveActiveWnd.vbs Script
set hotkey to script in parens and add the monitor number after the script file location with a space like
`"D:\Dropbox\Shared\UltraMon-Scripts\Brian\MoveActiveWnd.vbs" 5`



Win+Numpad(4) = Top Left Monitor No. 4
Win+Numpad(5) = Top Center Monitor No. 5
Win+Numpad(6) = Top Right Monitor No. 6 
Win+Numpad(1) = Bottom Left Monitor No. 1
Win+Numpad(2) = Bottom Center Monitor No. 2
Win+Numpad(3) = Bottom Right Monitor No. 3
