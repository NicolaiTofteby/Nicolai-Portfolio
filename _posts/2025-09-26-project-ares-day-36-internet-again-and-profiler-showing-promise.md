---
title: Project Ares Day 36 - Internet again and profiler showing promise
date: 2025-09-14T13:39:03.826Z
image: /assets/uploads/day-36.png
---
## W﻿hat’s been happening since last time?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#whats-been-happening-since-last-time "Permalink")

Last time I spoke about wanting to work on a profiler so I could figure out where the problems in our code was and narrow down the potential problem. I have made the Profiler and moved in quite nicely in my new building. I have made some great development and I think I have found the problem at last.

## W﻿hat have I learned?[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-have-i-learned "Permalink")

I have learned about profilers and how to set them up in the code, so while I run the game I can see where problems of high memory gets taken from

## What challenges did I face[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-challenges-did-i-face "Permalink")

I﻿ ran into a problem while creating the profiling code where I wasn't really sure where it should and shouldn't be, and without internet it wasn't that easy to create alone and only help from people on discord and AI on my phone. But I ended up creating something while looking on Godots help pages which was by far the biggest help.

I fixed the profiler with this piece of code and I found these problems afterwards

```
        _lastUpdateMs = (Time.GetTicksUsec() - start) / 1000.0;
        if (_lastUpdateMs > 2.0)
            GD.PushWarning($"{Name} UpdateEnemy took {_lastUpdateMs} ms");
```

![](/assets/uploads/day-36.png)

## U﻿I / UX and Gamification[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#ui--ux-and-gamification "Permalink")

I﻿ haven’t worked specifically at any of this.

## W﻿hat I plan to do next:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#what-i-plan-to-do-next "Permalink")

I have plans on fixing the problem with navigation till Monday so I can finally work on something else other then just working on reducing lag for the game

## R﻿eflections:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#reflections "Permalink")

I could probably have spend my time a little more efficent, but with moving and also working on the project it's been difficult to do it 

## L﻿inks and Sources:[](https://nicolaitofteby-portfolio.netlify.app/project-ares-day-25-enemy-pooling/#links-and-sources "Permalink")

https://docs.godotengine.org/en/stable/tutorials/scripting/debug/the_profiler.html

https://www.reddit.com/r/godot/comments/1c2kjax/c_profiling/