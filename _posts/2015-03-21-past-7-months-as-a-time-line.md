---
layout: post
title: "Past 7.5 months as a timeline"
date: 2015-03-21
---

So yeah, how was the learning &amp; developing process I took last 7.5 months? I would like to show the older versions, but not all of them. Because I stuck around in some versions for couple months and did not change any visual stuff. And some prototyping took so much time.

Lets start.

[caption id="" align="aligncenter" width="380"]<img class="" src="http://s6.postimg.org/phz7d1dep/y_JHOWc_J.gif" alt="" width="380" height="205" /> 04.08.2014, the first day, I am double jumping on farmville![/caption]

First day was a bit crazy because I was so excited about the idea to implement physics and I was learning the SFML library. I already had the hilarious animated Rambo sprite and the FarmVille background from my previous topdown game. I simply coded the running, jumping and double jumping.

[caption id="" align="aligncenter" width="389"]<img class="" src="http://s6.postimg.org/m7aud5nhd/oqw_IEYc.gif" alt="" width="389" height="330" /> 04.08.2014 at night, the first Grappling Hook test[/caption]

I was just enjoying what's getting produced and I worked a lot that day, because it was fun. So I implemented the first grappling hook, which grabs a fixed position and simply pulls the character to that position. But that was not what I wanted, I wanted to swing, this thing was working like some rubber band!

<!--more-->

[caption id="" align="aligncenter" width="389"]<img class="" src="http://s6.postimg.org/fw5mwqm8x/a_RRn2s_M.gif" alt="" width="389" height="330" /> 05.08.2014, Finally swinging...[/caption]

At last, we're swinging! That's cool already but however, it slows me down at the position I should accelerate, that's weird. The solution I had in my mind was the fixing the hook range, make it work like a solid bar which does not shorten or extend. That could keep my momentum same so I could accelerate more and more.

[caption id="" align="aligncenter" width="389"]<img class="" src="http://s6.postimg.org/ddjxw20ip/t_LPXy_Bh.gif" alt="" width="389" height="330" /> 06.08.2014, Swinging looks smooth![/caption]

And I implemented the "solid bar", it worked just as I thought. Then I made the hook a real object which flies in the air when character throws it. It was looking like a game already, wasn't it?

[caption id="" align="aligncenter" width="389"]<img class="" src="http://s6.postimg.org/w0wn3pezj/glx_Wh3_B.gif" alt="" width="389" height="330" /> 09.08.2014, SPEEDRUN![/caption]

I made a huuuge map on Tiled and put a timer on it. Then I started sharing it with my friends. It was already a competitive game, we were racing to finish the level as fast as possible. Some of them was finishing it in 14 freaking seconds while some "gamers" finish it in 100-130 seconds. I like competition!

[caption id="" align="aligncenter" width="389"]<img class="" src="http://s6.postimg.org/6gucx9tlt/Yk_Isbh_Q.gif" alt="" width="389" height="330" /> 10.11.2014, Dash, electric hook and 1:2 sized character[/caption]

After the start of the university, I could not spend so much time on the project, It slowed down after summer but I still had full motivation, I really wanted to make a good, enjoyable product. I was thinking about adding one more mechanic and I thought dash could be a good combo with the grappling hook, I added that. I made the character 32x64 but I could not find any free and decent sprite for it. Then I found some good electric animation on SFML Examples and tweaked it to be a beam for the hook.

As I told in previous posts, I had a graphic artist friend who accepted to work together, I was continuously asking that friend to work a bit, at least draw some character sprites, I was working with a 32x64 rectangle which is terrible. At the end of third month, she did not even draw a line, not a single line. I was wasting my whole time searching free and decent graphics on internet. So I decided to split our ways because that would not work that way and I did not want to ruin our friendship. I was alone in that project, since the beginning.

After wasting my weeks searching tiles and character sprites, I finally found some good looking place-holders, found a decent tileset on <a href="http://www.opengameart.org" target="_blank">opengameart.org</a>, I am still using that. And I turned the character size back to 32x32 because it was impossible to find 32x64. Then I found tons of 32x32 cute RPG character sprites which have got only 3 frames of walking animation and thats all. It was still better than the ugly 32x64 blue rectangle. I lost so much motivation those days.

[caption id="" align="aligncenter" width="300"]<img class="" src="http://s6.postimg.org/3lh9qeplt/y_X0lv2_L.gif" alt="" width="300" height="100" /> 10.12.2014, The coin system, dash breaks blocks[/caption]

I wanted to try some different stuff, since every game developer should do prototypes. Risk of Rain impressed me about coins and stuff. I thought collectible coins would be a good idea. So I added coin blocks. Character could break them by dashing onto them and the coin inside will fly directly to the character. It was fun but it was so pointless, I did not like it but I spent so much time trying different stuff with those coins.

[caption id="" align="aligncenter" width="304"]<img class="" src="http://s6.postimg.org/9xwf08so1/d8aizv_X.gif" alt="" width="304" height="161" /> 23.01.2015, Throwable and kickable people![/caption]

I removed those coins and I was discussing the game idea with a friend, instantly we created an idea, KICK PEOPLE IN THE FACE! Yeah why not, it's fun. Grab them and throw around or dash onto them to kick them. After implementing it I realized it is REALLY lots of fun. It felt like the "final idea", I tried to build the whole game onto that idea.

After spending tons of time on those people, first I put a timer and 7 people on the map. The objective was to kill all the people in minimal time. When I implemented these stuff, I watched my friends play the game, most of them did not even use the grappling hook, which is the main thing in the game. At that moment I realized the people system was removing the grappling hook or dramaticly reducing the use of it.

After removing the people, game felt quite empty. I started to lose motivation again. And I started adding blood effects, levitating particles, electric particles to keep myself working and motivated. I wanted to make it juicy so I can enjoy it.

Then my buddy <a href="http://steamcommunity.com/id/Boneslark/" target="_blank">Boneslark </a>came up with amazingly epic and creative ideas which put the game in some direction. One of the idea is to have a graphical but not functional second hook. So character will have two hooks and he will use them simultaneously, but both hooks will never land at the same time. If character throws one of them, other one comes back and it waits for it's queue. Character swings the inactive hook in a cool looking way, just like the Thresh in League of Legends. Character throws the available hook and pulls the busy one back. Hooks started feeling like a real objects, they don't disappear.

[caption id="" align="aligncenter" width="600"]<img class="" src="http://s6.postimg.org/tkutpuwwx/f1_RFrh_Z.png" alt="" width="600" height="288" /> Twin Claws of Naezith, the thunder dragon.[/caption]

I just threw myself into GIMP and tried to draw some pixels, and bam, I made a cool and weird looking hook, then I put some green on it, it really looked like something special! Saved it and recolored it to blue, so I could have two hooks. I also was looking for a theme, a story, something like that.

After playing with them a bit, I randomly imagined those hooks as some "claws", I don't really know if it's the right word but the german word for it is "kralle", each nail of the big claw. Yeah I liked that idea, that sounded so cool to me. Magical claws of some dragon or monster. Since I had no idea about the theme and story, it felt so good to imagine something like this. So I kept discussing this with my friend <a href="http://steamcommunity.com/id/Boneslark/" target="_blank">Boneslark </a>and even wrote a story for it. I will talk about his later but it's basicly like "dragon's soul gets into the man" after the interaction/touch of those claws. Claws binds to our hero.

And then, I added sh!tload of juicyness to the game, 20.03.2015

http://zippy.gfycat.com/BlackandwhiteHalfKitty.webm

Now I am super-motivated, created this website and started sharing my work and ideas so we can improve it together with people who likes the idea.

Continue : http://naezith.com/dude-youre-doing-it-wrong-summary-of-4-5-months/