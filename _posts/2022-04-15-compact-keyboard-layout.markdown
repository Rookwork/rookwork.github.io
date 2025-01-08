---
layout: post
title:  How I made a compact keyboard layout
description: My fingers hurt, but I needed to type. It was time to make a change.
date:   2022-04-15 15:01:35 -0500
image:  '/images/keyboard-layout/layout-image.png'
tags:   [something I made]
---
It is probably unsurprising that I type *a lot*. I don't keep track, but it's easily thousands of words per day. I'd say 500,000 words a year is a pretty fair estimate if maybe even a little conservative. That's more than the [entirety of the Lord of the Rings books](http://lotrproject.com/statistics/books/wordscount), every year! So when my fingers started to hurt while typing, that was a big problem.

Specifically, most of my pain was concentrated along the outside edges of my hands along my pinky fingers and up to my wrists. This is, as far as I know, somewhat unusual as far as typing strains go, but I immediately had a theory for why this was happening: modifiers. 

Since I type primarily in English, I have to make use of Shift quite a bit for all those pesky capital letters. Shift is traditionally positioned on the outer edges of a keyboard and hit with your pinky fingers. What I think started happening for me is, I held Shift so often that I would use it as kind of a pivot to support the rest of my hand, briefly but consistently putting a lot of weight on my pinky fingers. Eventually, those little guys had enough. 

Fortunately, I was already very familiar with the world of hobbyist and ergonomic keyboards having built my own and working for a company that makes them. Using a split keyboard no doubt helps me not suffer even more strains, but this issue went beyond the basic form of the keyboard I was using. 

I needed an all new keyboard layout. 

## Research
My first and core decision was what to do about Shift. I considered keeping a fairly normal layout and just moving Shift to my thumbs, but if I was going to be taking on the challenge of learning a new layout, I wanted to do something that would truly fix the problem. I wanted to fix not just Shift, but everything that wasn't really optimal about my layout. My solution was home row mods.

I had heard of home row mods before, but they were still mysterious to me. Surely they couldn't actually be comfortable to use, right? My fears were abated by [this fantastic article from Precondition](https://precondition.github.io/home-row-mods). If you're curious about home row mods, I highly recommend giving it a read. I went into it knowing very little and came out of it feeling not just ready, but excited to try them.

My next stop was one of the most popular home row mods setups: [Manna Harbour's Miryoku](https://github.com/manna-harbour/miryoku). Looking through this layout filled in the last few gaps I still had, mainly giving me a reference for how many layers I could expect to use and roughly what to put on them. Manna Harbour is kind enough to have made the Miryoku layout in Oryx already, so I could have just cloned that, but I could already tell there were some changes I would need to make to suit my preferences, and I thought building the layout from scratch would help me consider it more carefully, so I got started from a completely blank slate.

## Development
The first versions of my layout were not particularly interesting. They were very close to default Miryoku with a few tweaks and omissions. The more interesting developments came as I ran into problems.

### My weak pinkies strike again
After reading Precondition's guide on home row mods, I was aware of the idea that some people preferred to put their mods on the bottom row of keys rather than the home row. This was always sort of my backup plan if I found home row mods too difficult. What I did not expect was home row mods working great for my stronger inner fingers but terribly for outer fingers.

My solution was ultimately very simple and kind of elegant if I'm allowed to say so. I left my two most-used mods on the home row my strong fingers, and I moved my least used mods down a row. That way, I still had the primary benefits of home row mods while keeping the home row keys that fall under my weaker fingers still usable. I'm sure I'm not the first person to think of staggering the home row mods like this, but I don't see this configuration brought up very often -- I really like it. 

### Which modifiers to choose
The positions of my mods were sorted out, but how to arrange them remained up in the air. I use macOS about 90% of the time, but I do boot into Windows and Linux from time to time for testing or just miscellaneous tasks. The problem with this is macOS uses CMD for common shortcuts in place of CTRL. 

I knew Shift would be my primary modifier, and CMD would have been the natural choice for my secondary modifier, but I really didn't want to have to deal with reorienting myself every time I switched operating systems. I don't spend a ton of time overall outside of macOS, but I do switch frequently for short periods, so this would regularly be a problem. 

I discovered the solution in macOS itself. In System Preferences > Keyboard > Modifier Keys, I changed CTRL to CMD and CMD to CTRL. This means macOS sees CTRL key presses as CMD, and vice versa, so I can make CTRL my secondary modifier key and the most common shortcuts will always work for me no matter what OS I'm on. This does mean that I have to think twice about shortcuts that I'm less familiar with on macOS, but this hasn't been a big problem for me so far.

### Numbers and symbols
The basic structure of Miryoku was good, but the arrangement of the numbers and symbols didn't really make sense to me. This isn't a knock on Miryoku, though -- everyone will have different preferences for this.

Numbers were a pretty easy choice. I created a layer that mimics a dedicated num pad on the right half. I wasn't sure if I would like this; I was a heavy number row user before. I took to this *very* quickly though, and now I can't go back. 

Symbols took a little more experimentation, but I like the method I eventually came up with. The symbols on the home row are the ones I use most frequently, the symbols above those correspond to numbers 1-5, and the symbols below the home row correspond to number 6-0. These straightforward assignments make the symbols easy to remember and keeps everything accessible.  

### The gaming issue
Finally, the part of my layout that I was the most unsure what to do about once I started going down the home row mods path. Most of my typing is for work, but I do like playing games from time to time. The problem here is all this experimentation I was doing wouldn't work at all for games. 

On a raw technical level, dual-function keys don't always work with all games. Some games have issues recognizing them, and there's not a lot that can be done to change this. Even beyond that though, there are deeper reasons why my layout wouldn't work for games. 

The more I experimented, the more I realized playing games actually involves subtly different actions than typing. Assuming I have a decent grasp on spelling, typing words is fundamentally pretty predictable. I think what I want to communicate, then I action it. 

Gaming flips the script. Not only do I think things then action then, but I also have to react to things. This is the fundamental reason that compact layouts are trickier to game with. There is a material advantage to having as many discrete actions available to trigger instantly as possible. In other words, I can tolerate the brief delays of dual-function keys in normal typing, but it's a disadvantage that can't really be ignored in games.

To solve this, I took inspiration from games: I cheated. :)

#### Optimization with a purpose
I use "cheat" jokingly. Creating this compact layout required a lot of thought and the new developments were exciting. As I got more comfortable with it, it felt like it was the solution for everything. "When you've got a shiny new hammer, everything seems like a nail."

I pretty quickly decided to break my Miryoku-inspired 36-key template. I had plenty of keys available with the larger Moonlander board, after all. 36 keys was just a little bit too limiting, so I added a couple of keys to the outer column. I may even add the number row back. It's still compact, but not as compact as possible. 

Working on my gaming layers was a fitting final act to designing this layout. It snapped me out of a fixation on having an exactly 36-key layout, and helped me realize home row mods, a compact layout, dual-function keys... these are just different means to and end: typing comfortably. 

## The "final" layout
I won't pretend I mastered this layout right away. It took about a week of typing very slowly in my downtime to start to get comfortable, and I also had to spend extra time in the games I played regularly getting used to the new layout. Then, when I was feeling like I had some grasp on this, I took the plunge and switched to it full-time. To my surprise, it worked.

I put "final" in quotes here because I don't think there's ever going to be a real final layout for me. This iteration has been working for me for several months with minimal tweaks though, so I think it's safe to call it a success even if I ultimately make more changes down the line.

In short, this layout is designed to minimize reaching and relies on my weakest fingers as little as possible. I was worried it would be difficult to get used to, but after just a couple of weeks, I felt nearly perfectly comfortable with it. I do occasionally have some difficulty with more traditional keyboard layouts with modifiers on the outside now, but I can adapt if I need to. I don't think the years of ingrained muscle memory of traditional layouts can ever truly be overwritten. 

I also created a layout tour with ZSA's configurator, Oryx. I recommend stepping through it if you're curious about the layout. The tour lets me interactively comment on specific keys so you can see my thoughts in context. 

<div style="padding-top: 60%; position: relative;"> <iframe src="https://configure.zsa.io/embed/moonlander/layouts/xDpMW/latest/0" style="border: 0; height: 100%; left: 0; position: absolute; top: 0; width: 100%"></iframe> </div>

I've been quite happy with the result! I highly encourage you to give a smaller, layer-heavy layout a try. I won't claim this is the future for everyone, but it's not as difficult to get used to as you might think, and it's really helped me. 

## Future ideas
Even though I'm broadly happy with my layout in its current state, I sometimes idly think about ways I might be able to make it better. Here are a few ideas that I'm considering and that you can consider as well. 

### Callum mods
An alternative to home row mods, [Callum Oakley's Callum mods](https://github.com/qmk/qmk_firmware/blob/master/users/callum/readme.md) intrigue me. The idea is to use oneshot keys to switch to layers for a single keypress, and then switch back. Home row mods have worked fairly well for me, but  eliminating the need to hold keys at all is something I want to try out. 

### Navigation keys on the number row
I have a nav layer with various shortcuts to change windows and tabs, but I almost never use them. There's nothing inherently wrong with this, but at the same time, I would like to get more use out of these shortcuts. Now that I have an unused number row, I'm thinking of assigning these shortcuts there instead. They would be about as accessible as possible, so I could better evaluate whether I don't use them because I forget about them or because I really don't have a use for them in my workflow.

### Tweaks to the thumb clusters
I modeled my three-key thumb clusters off of Miryoku, and they work just fine, but I'm tempted to try to make do with two-key thumb clusters instead. The benefits of this change would be pretty minimal admittedly, but relying on just two keys instead would make my layout a little more flexible. 