---
title: Project Ares Day 45 - Experience points
date: 2025-09-23T17:48:36.912Z
image: /assets/uploads/day-45.jpg
---
## W﻿hat’s been happening since last time?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#whats-been-happening-since-last-time "Permalink")

Since last time, I have been working on the enemy spawning system and discovered an issue where unused enemies from the pool appeared at position (0,0). This caused the player to automatically detect and attack them at the start of the game, which also triggered XP drops. I debugged the problem and realized it was connected to the way my spawn pool was set up.

## W﻿hat have I learned?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-have-i-learned "Permalink")

I have gained more insight into how nodes like VisibleOnScreenNotifier2D, NavigationAgent2D, and CollisionShape2D interact within the enemy and player systems

## What challenges did I face[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-challenges-did-i-face "Permalink")

The main issue was finding out why enemies seemed to exist before they were actually spawned. Another challenge was understanding the way Godot handles instances in a pool and making sure they don’t interfere with gameplay before being activated. It required testing, debugging, and looking into how to either move them off-map or disable them until they are needed.

## U﻿I / UX and Gamification[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#ui--ux-and-gamification "Permalink")

In terms of UI/UX, I have been reflecting on how important it is for players to clearly understand feedback from the game. For example, an XP bar or level-up animation makes progression obvious. 

## W﻿hat I plan to do next:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-i-plan-to-do-next "Permalink")

I﻿ plan on updating the Tavern The Golden Goose, Redesign the Death screen, rework the player so Lars isn't so boring to look at. I'm also thinking about creating a Tavern keeper that you can talk to and buy upgrades at. and then perhaps afterwards I will begin testing on the upgrades, we have already made a sheet on what upgrades should be and their % buff

## R﻿eflections:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#reflections "Permalink")

I found out how small techinical issues can have a big impact on the overall game experience. The enemy pooling problem, having random drops from killing enemies that aren't actually in the game and getting rewards wasn't intended and I feel like I slowly get a better understanding on the bigger picture in the whole program. My professor has asked me to create a relational diagram so I'm gonna do that after I have finished writing this

## L﻿inks and Sources:

https://docs.godotengine.org/en/stable/classes/class_node.html\
https://docs.godotengine.org/en/stable/classes/class_characterbody2d.html

https://www.nngroup.com/articles/definition-user-experience/

https://www.interaction-design.org/literature/topics

https://yukaichou.com/gamification-examples/octalysis-complete-gamification-framework/

![](/assets/uploads/day-45.jpg)