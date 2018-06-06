---
layout: post
title: "How did I make a blog?"
date: 2018-06-06
---

I had this urge for a while, to make a blog. The reason I waited too long is the hesitation about the thought that I can't find much to write about. Maybe that's really the case, yet I decided to try. This post is more about an experience about the problems occured to me, instead of straight-forward instructions. I'll still be linking all the guides which you can follow step by step.

First option I thought was to make a WordPress page and host it on my game server. I started installing it but I forgot that the game server actually runs at port 80, which is the HTTP port so I quickly abandoned that idea. A basic solution could be to get another server, which I wouldn't do.

Second option which came to my mind was to use GitHub Pages. It's pretty famous and convenient and I'm already using the main page, naezith.github.io with naezith.com domain, as Remnants of Naezith official website. I headed to github.com and made another repository, called "blog". Then I choose a theme in the repository settings, it automatically initialized the repository with a Jekyll theme. I wanted to have a blog but this theme was a single page demo of the theme. I wanted to set it up quickly so I searched for an already set-up blog theme. There wasn't any that I liked. So I came back to that blank demo page of the Midnight theme which I chose previously. After searching a bit, I found [this marvelous guide by Jonathan McGlone](http://jmcglone.com/guides/github-pages/), about setting up a blog using GitHub Pages and Jekyll. Guide holds your hand and carries you all the way so it's pretty easy. I didn't even need to Google anything during the process. Eventually the page was set-up.

There was one issue though. Since I'm already using my account's the main GitHub page for the game, I wasn't able to use naezith.github.io URL. This blog was set-up as a project page, which means it has the URL, naezith.github.io/blog. My DNS provider, CloudFlare, was not accepting the /blog part obviously. A basic solution here could be to create a new GitHub account but again, I wouldn't do. I still wanted to have a nice URL like blog.naezith.com so I searched about it. Found [this another awesome article by António Monteiro](https://anmonteiro.com/2015/08/custom-subdomains-in-github-project-pages/). It also has pretty basic instructions to follow. It was very helpful. 

Eventually it became a GitHub Page hosted, Jekyll website with beautiful blog.naezith.com URL. While writing this post, I'm also editing the style of the page so I don't know if it turned up well when it's done, you tell me! 