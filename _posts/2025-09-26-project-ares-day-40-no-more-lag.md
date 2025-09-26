---
title: Project Ares Day 40 - No more lag
date: 2025-09-18T11:40:20.875Z
image: /assets/uploads/day-40.jpg
---
## W﻿hat’s been happening since last time?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#whats-been-happening-since-last-time "Permalink")

This time I have fixed the problem with the enemy pathing and made it more stable and now it doesn't lag at all even with 200 enemies on the screen. We have discussed it in the team, and we have decided that our Enemies should be able to clip across object if they spawn in a location that is outside of our view or if the object is taking too much memory to calculate, it just makes it easier for us and the game to code and to play the game

## W﻿hat have I learned?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-have-i-learned "Permalink")

I have learned how to fix pathing in the game and what some best use could be.

## What challenges did I face[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-challenges-did-i-face "Permalink")

F﻿or me the problem was that I didn't understand how the pathing worked or why it took so much energy to find the player and walk towards him, but the problem was simply that it pinged the players location every frame and took up a lot of memory trying to figure out the best and fastest route to the player.

## U﻿I / UX and Gamification[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#ui--ux-and-gamification "Permalink")

I have updated the Healthbar, XP/Gold drops and Damage Area, which all in all contributes to the experience of the game, wioth the little coin sounds

A﻿s for UX the game of course has become a lot less laggy and my team has made it more visible when you get XP and Gold so it's easier for the player to see what they earn

![](/assets/uploads/day-40.jpg)

## W﻿hat I plan to do next:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-i-plan-to-do-next "Permalink")

N﻿ow that this is fixed I have plans on working on the XP progression curve so instead of always needing 100exp you need 100 then 150, 250 and so on. I have watched a few videos on the subject and the correct curve seems to be something like Level x 1.5 or something along those lines

## R﻿eflections:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#reflections "Permalink")

I﻿ still don't know if everything is clear enough when it comes to the UI and as for the User experience I imagine it will become better when we move closer to the finish line

## L﻿inks and Sources:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#links-and-sources "Permalink")

https://docs.godotengine.org/en/stable/tutorials/performance/general_optimization.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/4.4/tutorials/performance/index.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/latest/tutorials/navigation/navigation_optimizing_performance.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/latest/tutorials/navigation/navigation_using_navigationagents.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/4.4/classes/class_visibleonscreennotifier2d.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/4.4/tutorials/performance/cpu_optimization.html?utm_source=chatgpt.com

https://docs.godotengine.org/en/4.4/classes/class_performance.html

https://www.reddit.com/r/godot/comments/1i2zn5j/poor_performance_in_complex_navigationagent2d/?utm_source=chatgpt.com

https://www.reddit.com/r/godot/comments/c1nuya/visibilitynotifier2d_isnt_very_accurate_is_there/?utm_source=chatgpt.com