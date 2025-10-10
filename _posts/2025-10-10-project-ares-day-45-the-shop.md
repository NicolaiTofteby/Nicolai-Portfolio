---
title: Project Ares Day 53 - The Shop
date: 2025-10-03T08:04:29.581Z
image: /assets/uploads/day-53.jpg
---
## W﻿hat’s been happening since last time?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#whats-been-happening-since-last-time "Permalink")

Since last time, I have continued working on improving the shop system in the Tavern, I have updated the UI structure moving from Panels to Containers for better layout control. I have also implemented a new upgrade feature. I fixed some scripts and data errors related to the PlayerData file and improved how gold and upgrade levels are displayed in the shop. It's not fully operational yet. But I will get back to it in a few weeks as there are more pressing matters atm.

## W﻿hat have I learned?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-have-i-learned "Permalink")

I﻿ learned how to manage player data using the .tres files, how the debugging worked, we often run into encoding problems and script instantiation errors, which could be a couple of reasons, sometimes when we push it to the main branch we didn't merch it correctly or Godot and C# doesn't speak well with each other, mostly our fault but I like to think that we aren't always the problem. I also got a better understanding on how containers such as the VBoxContainer and GrindContainer handle layout automatically. I like using manual positioning with Panels but I understand the practicality

## What challenges did I face[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-challenges-did-i-face "Permalink")

I had a few problems with the UI paths didn't match accordingly, there was also a few problems with the naming for the shop feature, some of them overlapped a little so I had to tweak a few things. There was a few small typos in node names that caused several ''Node not found'' errors, and at one point all our scenes just went out the window. But easy enough to recover on my on.

## U﻿I / UX and Gamification[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#ui--ux-and-gamification "Permalink")

From a UI/UX perspective then I worked on making the shop menu and made it informative for the player. I added a visable gold counter and level indicator, for each upgrade. And after having asked around a little I got some feedback that some of the icons could be better so I went back and changed those.

When it comes to gamification which should create as sense of reward and motivation for the player. They can now spend the gold they earn buying upgrades, which should drastically improve their overall stats and help them through some of the early game and make them far stronger in the late game.

![](/assets/uploads/day-53.jpg)

## W﻿hat I plan to do next:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-i-plan-to-do-next "Permalink")

Next week I imagine myself spending a lot of time on internship applications. After that I plan on revisting some of the older designs and systems we worked on earlier in the project. I want to redesign and polish certain UI screens to make them more consistent and readable.

## R﻿eflections:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#reflections "Permalink")

Overall I feel more confident in bombining the programming and design, I understand how technical the structure and visual design a little better.

DThe debugging process while frustrating at times helped me improve my solution I came up with at the end and a toll I should use a lot more instead of bruteforcing my solution. 

## L﻿inks and Sources:

https://docs.godotengine.org/en/stable/tutorials/scripting/c_sharp/index.html

https://docs.godotengine.org/en/stable/tutorials/ui/index.html

https://gamedevacademy.org/game-ui-design-principles/