---
layout: post
title: "High ping, VPN and Source executables"
date: 2020-07-06
---

I am having high ping recently, and I can see it in Team Fortress 2, Left 4 Dead. For example an European server I get 105 ms, but it should be 50-70. So I started looking for solutions.

I already have ExpressVPN, and connecting to Germany Frankfurt helps a little, making it go down to 90. Similar with Dashlane Password Manager's VPN, which is provided by Hotspot Shield. Both were freezing from time to time, ExpressVPN for 20 seconds every couple minutes and Hotspot Shield for 3 seconds every minute.

I saw WTFast before, offering better routes to the servers than the ones ISP provides. So I started the trial, tried many options and did many tests. Lowest ping was 70 which is really good but it was hanging for a long time as well, around 20 seconds. This is unacceptable so I removed it. 

I looked for alternatives and found ExitLag, and it is amazing. Allowing me to add maximum of 4 routes, best combination is 1 TCP and 3 UDP I think, since FPS games work with UDP. And TCP is there for other stuff, I heard that Overwatch uses it sometimes. 

ExitLag is a lot easier to use than anything else because it shows me more useful information about latency, paths etc. Ping went from 105 to 53-61 and zero freezes, it is just perfect.

Even though ExitLag has over 400 games including Team Fortress 2, it did not have Left 4 Dead, and that was a big deal breaker for me. However I know that TF2 and L4D are using the same game engine, Source Engine. 

I know that TF2 executable is `hl2.exe` so I thought ExitLag was just looking for that name. I renamed `left4dead.exe` to `hl2.exe` but it did not launch, saying `Setup file 'gameinfo.txt' doesn't exist in subdirectory 'hl2'. Check your -game parameter or VCONFIG setting`. Then I made a basic shortcut to the `hl2.exe` and added the `-game left4dead` to the shortcut path. It worked, but launching the game from Steam is looking for `left4dead.exe`. So I didn't go with this route since I want to put game launch options at Steam like `-novid -lv`.

To solve all these, I renamed `left4dead.exe` to `hl2.exe` and then I ran CMD as Administrator. Then I ran `mklink "D:\SteamLibrary\steamapps\common\left 4 dead\left4dead.exe" "D:\SteamLibrary\steamapps\common\left 4 dead\hl2.exe"`. It made a shortcut called `left4dead.exe` (not `left4dead.exe.lnk`) which points to the renamed `hl2.exe`.

Steam was able to find and launch `left4dead.exe` and even apply `-novid -lv -freq 280 -noborder -fullscreen` launch options. And yes, ExitLag detected Left 4 Dead as Team Fortress 2 and worked the same way!

I thought it would be good to save this experience here, for future myself or a random stranger.