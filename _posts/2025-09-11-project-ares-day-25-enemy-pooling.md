---
title: Project Ares Day 25 - Enemy pooling
date: 2025-09-08T10:20:05.049Z
image: /assets/uploads/day-25.jpg
---
## W﻿hat’s been happening since last time?

I﻿ have been working on Enemy Pooling. Enemy pooling is where you make a pool for your enemies in the game so that when you begin the game they are already instanced and are ready to go whenever you need them. The idea is that we need around 300 enemies on the screen at all times in the end game. Instead of making a new enemy every time it dies, it's better to use a reuseable enemies that we can use again and again every time they die. That way we save on memory and should in theory make the game more stable

## W﻿hat have I learned?

M﻿emory Effciency and Reduced Lag was the whole idea behind making it less laggy, I created a problem and now the game is lagging more then ever, and i'm not entirely sure why but that's what I will be looking at in the future

## What challenges did I face

W﻿ell I had some things that annoyed me when it came to the Enemy pool because at the same time I also had to change the enemy spawn script. So when I had something running another thing would break so it took me a lot of time to figure out the specific things for now the spawning works on a timer based system. The system checks every 1 sec to see if there is something new. But this is how it looks so far. (I will most likely change it soon again)

_schedule.Enqueue(new SpawnEvent { Time = 1f, EnemyScene = GD.Load<PackedScene>("res://Scenes/Enemies/RedMushroom.tscn"), Count = 2 });
_schedule.Enqueue(new SpawnEvent { Time = 10f, EnemyScene = GD.Load<PackedScene>("res://Scenes/Enemies/RedMushroom.tscn"), Count = 4 });
_schedule.Enqueue(new SpawnEvent { Time = 25f, EnemyScene = GD.Load<PackedScene>("res://Scenes/Enemies/ToxicGreenFrog.tscn"), Count = 2 });

## How have I contributed to the project?

I﻿ have made a enemy pool that can be used to reuse enemies that have died, I have a also updated a few of the scripts

## U﻿I / UX and Gamification

I﻿ haven't worked specifically at any of this.

## W﻿hat I plan to do next:

F﻿or the next week or so I expect to be rather busy as I will be going on a quick trip till tomorrow evening so I won't be able to do much this week as i'm also moving Sunday. But I expect to I will be working on fixing the lagging next time I update this and I will have made the scripts a little better

## R﻿eflections:

I﻿ should have made the enemy pool and not changed the spawn script as well at the same time so that I could easier find out what the problems I have now are

## L﻿inks and Sources:

https://forum.godotengine.org/t/issue-with-enemy-object-pool-and-on-body-entered/114772/2\
https://www.youtube.com/watch?v=79TVbTAkmIg\
https://learn.microsoft.com/en-us/aspnet/core/performance/objectpool?view=aspnetcore-9.0

https://gameprogrammingpatterns.com/object-pool.html

![](/assets/uploads/day-25.jpg)