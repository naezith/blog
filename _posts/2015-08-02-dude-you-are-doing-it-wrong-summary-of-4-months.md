---
layout: post
title: "Dude you are doing it wrong! Summary of 4.5 months"
date: 2015-08-02
---

Ehh, I know... last post is posted in March (4.5 months older than this post), I KNOW THAT. This truth kills me, I know I am doing devblogging so wrong. Now I will list some excuses if you accept... I had to take like 2-3 months of break for the university and the development was pretty slow because I wasn't able to spend much time on it. But now it's holiday, so I continue and I can work a lot more. There was another reason that after the writing last post, I started using Zero sprites from Megaman series. I've read people saying "You would not want to post much prototype graphics until you get your graphics", that's because Google Image Search never forgets and it will show up like 2 years later when you search the game, kinda disturbing right? At least the idea disturbed me so I didn't feel like posting any new stuff. And a bit lazyness ofcourse (I mean, spending more time on the code) ;DD. 

I thought like a small gif with the Zero sprite won't hurt, soooooooo here is a quick and smooth run: 

(Camera view is cropped, normally you see all the obstacles) http://fat.gfycat.com/WebbedAdmirableAlabamamapturtle.webm 

**Edit (03.08.2015 14:20):** I cropped the view to get a smaller GIF. Many people got confused by the camera view, that's my bad that I did not mention, height of the character sprite is like 1.8x of the tile size and you always see 23 tiles in vertical, so actually you see more than you need.   

Like my other post ["Past 7.5 months as a time-line"](http://naezith.com/past-7-5-months-as-a-time-line/ "Past 7.5 months as a time-line") (I recommend you to check that if you did not), I will do a very similar thing like "Past 4.5 months as a time-line", sounds cool in my opinion. Maybe that is my blogging style. But this time we won't have many gifs because I did not save builds so often. Whatever... lets start! 

![](http://s6.postimg.org/tkutpuwwx/f1_RFrh_Z.png) Twin Claws of Naezith, the thunder dragon. 

The Two hooks idea was pretty new and that really pumped me the awesome motivation. I wanted to finish the character design/story/theme so I spent time on thinking, also discussing with friends about those stuff. And I completed those stuff, ofcourse there might be changes but it is like:

> There lived a magical, **Thunder Dragon named Naezith**. He was so mighty and egomaniac. His powers came from the thunders. Like the every living being he died, long long time ago. There passed so much time that the remnants of his body are spread around the globe. His magical remnants might give supernatural powers to people who interact with them. Even if he is dead, his soul still lingers. He wants to find a proper living body to get rid of his remnants because he doesn't want **ANYONE** to have his powers and act a god. 

Our main character is some treasure hunter, he explores underground to find stuff and he uses his rope with a rusty hook to pass the big pits. One day he fails to land his hook on the ledge and he falls down to the pit. When he sobers up, he finds two dragon claws attached to his hands. He gets crazy and he immidiately tries to drop those claws from his hands. But it does not really work then he swings his hands so fast, the claw flies and stucks to the wall. He sees his hand is linked to the claw on the wall with a glowing energy beam with electricity on it. Naezith slowly takes control of him.

Aaaaaand enough spoilers! But it is like two souls in one body, double personality, so they will talk to each other and the guy will gain the dragon's agility and some supernatural abilities. I haven't find a name for my character yet so I call him "the guy" for now. 

I play my game a lot, I enjoy moving around. Swinging and pulling with the hook, dash, everthing feels fine but I change the movement constants so often to discover some new feeling. So I tweaked them to become less floaty, more responsive. It feels like you have got full control on the character that you can stop or turn or achieve blazing fast speeds anytime you want. I really spend a lot of time on this because this is more important than anything ingame. The controls and feeling of the character are the core. 

After that, I added tons of map elements and obstacles, you can see couple of them in the video on top but here is the big list: 

**Map Elements:**
*   A tile that you can't grapple the hook more than x seconds
*   A tile that you can't wall-jump on
*   A tile that will bounce the grappling hook and it won't land on it
*   A tile that mixes last two like no-walljump and no-grapplinghook
*   A jump-pad sends you with a fixed speed and fixed direction
*   A jump-pad that keeps your speed and adds vertical speed onto it
*   A magnetic field that accelerates you pretty fast in some direction
*   A circular magnetic field that pulls you to the center
*   A circular magnetic field that pushes you to outside from the center
*   A rectangle-shaped straight magnetic field that changes gravity or pulls you in some direction

**Obstacles (All of these kills on one touch):**
*   An object that doesn't move and (spikes, acid, lava, blades w/e)
*   An object that moves fixed up-down or left-right
*   An object that doesn't move and rotates in circular motion from a range (a swinging blade)
*   An object that shoots a projectile which goes straight in some direction
*   A really fast moving but hard turning homing object (some flying energything)
*   A slow moving but easily turning homing object
*   A turret that tracks the player and rapidly shoots super-fast projectiles
*   A laser or energy thing that toggles on-off in some fixed seconds
*   A laser or energy that rotates in a fixed direction without caring the player's position
*   A laser or energy turret that tracks the player and rotates slowly

I really love the leaderboards in the Dustforce game. It adds challenge and replayability. And I love challenge so I implemented replay system first, then the leaderboards that anyone can watch any other's gameplay, so noone says like "omg how can he finish the level in 45 secs, bloody cheater!", he can simply watch, learn and beat that #1 guy. There are still bugs around, I am trying to fix them when I find any. 

I had to implement a login system to have profiles for leaderboard. When game is on Steam, there won't be need for this. 

I made a minimalist, cool GUI and it is enough for now. 

![settings](http://s6.postimg.org/glt0muc69/vqu9x9_O.png) 

I already implemented gamepad support before but after implementing replay system, I added bindable buttons for both keyboard and gamepad. 

![controls](http://s6.postimg.org/dcelgdo2p/U6_QBAx_L.png) 

I met an artist 8 months ago, he is a great guy, and he is very talented. I was sharing every update with him and at last, we started working on assets of my game! It will take time but I am pretty sure that assets will be really great. There is still a lot of stuff to develop so I've got plenty of time for graphics. 

I had almost nothing about how character should look like but I knew he must look super cool and badass because that's who I would like to control. I inspected many games, many characters and wrote down the elements I really like at them. And I spent most of my childhood gaming time with Prince of Persia series, I am a big fan of PoP, maybe because he was really cool, also the mechanics ofcourse. I was enjoying playing as prince when I was a kid, because he was pretty cool. So I searched more about PoP and thought of a character in my mind but at the end, it is looking very similar to him. I told artist about the character and also gave him this picture: 

![Prince of Persia](http://s6.postimg.org/jvc171pnl/Sua_Blzd.png) 

and bam, he came back with this: 

![Boneslark's concept art](http://s6.postimg.org/xii3f9jq9/c_S5_DHAZ.png)   

Awesome right? I know, badass and cool! But yeah I am kidding that's from my friend [Boneslark](http://steamcommunity.com/id/Boneslark/), as you can see, he is also very talented at drawing. Here is the awesome artist's awesome work: 

![Main character's rough drawings](http://s6.postimg.org/6d0jh0o4h/7_Vx3_Zq2.jpg) 

And my jaw dropped because he looks exactly same as the one I thought in my mind. Still looks like PoP but I love PoP so that is not a problem. I loved the middle one a lot, others look more agile but that one is my favorite. And at the bottom, there are smaller versions, he said it will be hard to have the same proportion with the something like 32x64 pixels sized sprite. Anyways, I LOVED IT! 

Every bit of these stuff pumps me motivation and motivation is like my fuel. So I started working harder when I saw those. 

Since I had the replay system implemented, I modified that a bit and added extra stuff and I made the ghost that you can race against. The best thing about this is you can race with anyone on the leaderboards, no matter if he is the guy #1 or guy #125473. But then it is optional so I put it in options. I made a config file and player binds and settings get saved. And couple days ago amazing artist sent a new art: 

![Detailed concept](http://s6.postimg.org/b9468po9t/pq_Jvqej.jpg) 

My brain melted when I saw this... **A M A Z I N G!** I mean I don't know how you see it but I find it fucking awesome, like 20x awesome, his face looks like Invoker from Dota 2. I also loved how the artist added some element like the glove without asking me. It just looks fantastic to me like I can't describe, my english knowledge is not enough for that! I'm sure he also make the sprite version pretty good, since he is this good. It looks so professional, it looks like some concept art of those AAA games. 

I improved the security of leaderboard but I think it is impossible to make it 100% secure so I won't spend my all time on it for now. I can work on it if I see anyone sending false time records and replays. 

And for last 3 days, I am working on a patcher that automaticly updates if there is new version. My buddy [Yengas](https://github.com/Yengas "GitHub - Yengas") helped me by coding the server-side while I was making the client-side. We did a good job and it is almost done! And again, when game is on Steam, there won't be need for this too. 

I still don't want to share the demo any soon because any little change ingame like slightly increasing the jump height would break all the old replays and time records, thats why I have to clear all the leaderboard and you guys won't like that. I really want to make sure replay system, leaderboards don't have any game-breaking bugs. And also I wait for the game assets, I like Zero from Megaman series but going public with that? No thanks. 

I will also regularly update my followers about the current status and my insights on game development through [@naezith](https://twitter.com/naezith) 