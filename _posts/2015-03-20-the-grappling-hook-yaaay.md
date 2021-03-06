---
layout: post
title: "The grappling hook, yaaay!"
date: 2015-03-20
---

I knew there were tons of game engines, game making tools, physics engines, whatever... My point was to learn C++ right? I would not learn much by using one of those stuff. Also I felt like those stuff are a bit big for my project, unnecessarily big. And I thought like using those tools would make the game worse, performance-wise. So I decided to make my game from scratch, from almost, I would only use the SFML as graphics library and thats it. An old friend who studies to be a graphic artist loved the idea and accepted to make it together, I need a graphic artist right? 

![Free-roaming in New York, Spider-man 2](/assets/img/spider-man-2-city.jpg "Free-roaming in New York, Spider-man 2")

After implementing the basic platformer physics, I realized thats too mainstream. I needed something fancier, GRAPPLING HOOK! Yeah why not, I loved to swing in Spider-man 2 on Playstation 2 when I was a boy. That was probably the most enjoyable mechanic around, maybe still is. But I wanted my game to be special, not a clone, noone wants that. So I searched the web about 2d grappling hook platformers, found tons of results... That made me feel a bit bad but when I keep inspecting them, I realized the hook mechanics of those games are not that good, and if the hook is well-implemented, that game is suuuuuper slow and about puzzles and stuff.

I am a FPS gamer myself and I play only the fast-paced ones like HL, Quake, TF2. Because I like the speed, the acceleration. Most of the platformers have fixed movement speed, you can't exceed the speed limit. I mean, why? Why would you limit the player? Let him enjoy the glorious physics and feel the acceleration, no? I say yes. So my key is the freedom of movements. Are you skilled? Then go play it fast, you don't need to walk. 

![Grappling Hook, 2 days later after starting](/assets/img/2dayslater.png "Grappling Hook, 2 days later after starting")

Yeah I implemented the hook in 2 days already. Is it done? For most of the grappling hook games I found on internet, yes, this was "done". But I am a bit perfectionist about this kind of stuff. If it does not feel good enough, then it means it's bad, simple as that. I tried many many algorithms to implement the physics of the hook. Some of them were easy like, pull the character directly to the hook, many games are using that but you don't really swing that way, I wanted the character to swing, just like in Spider-man 2 or Worms Armageddon! Then I finally made the guy swinging, but this time it was feeling a bit weird because, it was fixed movement. Character was swinging right and left but I was not really controlling the movement. Then I tried a different method, I was able to control the hook's movement but when I am swinging, sometimes character was decelerating when it should accelerate. After fixing that issue, I finally implemented the hook as the way I wanted, then I started tweaking it. And all these stuff costed me around 2 months and I am still tweaking it time to time to catch the "absolute perfect" feeling of the controls.
