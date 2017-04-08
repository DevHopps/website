---
layout: post
title:  "My thoughts on Tower Power (Postmortem)"
date:   2016-08-30 00:00:00
preview_img: towerpower-preview.jpg
image: towerpower.jpg
categories:
- ludum-dare
- gamedev
---

Here is the Postmortem of my latest Ludum Dare game [“Tower Power”][towerpower]. It's just a day late!

## What went right

I am really happy to have participated in this Ludum Dare and actually having enough time to finish something. 
The last time I really participated was 3 years ago - waaay too long ago. 
The start went really smooth. The Setup-UI thingy for LigGDX projects works really well. 
3 years ago it was way more complicated (especially including different frameworks and the correct native files). 
It just works now after a few clicks.

## What went okay-ish

My initial idea was something like “Crashed spaceship on planet. Awoke ancient alien race. 
The crewmen must find resources to repair the ship while also defending the ship”. 
Welp, including the crewmen and all their logic (I had a little “need-tree” in mind 
(Needs food if hurt to heal, needs Water every x hours, needs sleep every x hours) 
would've been way too much for me to handle in the short time so I cut that feature really quick. 
The game pretty much went from “Colonist-survival with Tower Defence mechanics” to “Tower Defence only”. 
I think that was the right decision.

The graphic side of things are always “meh” by me - but considering it's just a short time 
and I do them *really* quick (and moreover I can't draw), I am contend with them. 
I went a bit overboard on the particle Effects to make the game at least somewhat “visually” pleasing. 
I'm not really sure that worked.

The same goes pretty much for the sound effect - [Bfxr][bfxr] fits small games quite well.

## What went wrong

No music - but no surprise here. I never do them on Ludum Dare and pretty much can't do music myself… 
I should really look into it and at least try it at some point.

The next part might sound a bit harsh: The game itself is quite sh*t.

It's literally just some blobs running to the closest building. 
[Imagine playing Starcraft with just Banelings][banelinks]. T
here is just no variance in the enemies (I don't count different sizes as variance). 
Also at the end I quite got the [Starship Troopers][starshiptroopers] feeling, 
but to really feel like that there should've been even more aliens.

I just did 2 different buildings. A fast-shooting bunker and a slow-shooting rocket launcher (with AoE damage). 
The variance the Alien-Enemy is lacking, is also missing for the buildings.

The balance is off. If you start with bunkers and later build rocket-launchers when the money builds up you've won. 
You can probably win by only placing bunkers.

The terrain is just flat. No obstacles, no “chocke points”, no height differences. Just plain old boring.

I also wanted to include a Upgrades, but that never happened.

The Theme doesn't fit the game. I'm “happy” that I atleast added the word “ancient” in the description…

## Conclusion: Enough room for improvement

As you can read above, I'm quite happy about participating again. But the game, ugh. 
It has so many shortcomings in it's current state… 
On the positive side it can be improved on so many different things and I will indeed come back to it 
(Either in the form of a mobile game or as a HTML5 thingy). 
I also put the “crewman-survival” concept on my “pile” of ideas, but that is already gigantic as is.

I think this is all I want to say right now. If you want to chat I am [@Dev_Hopps on Twitter][twitter], 
[DevHopps on Discord][discord] and am reachable at mail@hopps.me via Email.

[You can download the game from here!][towerpower]

[towerpower]: http://ludumdare.com/compo/ludum-dare-36/?action=preview&uid=7316
[bfxr]: http://www.bfxr.net/
[banelinks]: https://youtu.be/FpS6nbjpfiQ?t=14s
[starshiptroopers]: https://www.google.de/search?tbm=isch&q=starship+troopers&tbs=imgo:1&gws_rd=cr&ei=aMDFV_qNB8HSU4Gxh9gM
[twitter]: https://twitter.com/Dev_Hopps
[discord]: https://discordapp.com/
