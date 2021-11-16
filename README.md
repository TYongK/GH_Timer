# GH_Timer
Grasshopper Timer Parameter Development

source: https://discourse.mcneel.com/t/using-system-timers-in-visual-studio-for-simulation-animation/67855/4

I should have add "ExpireSolution(true);" in the Stop() method.

 **blic void Stop()
        {
            aTimer.Stop();
            ExpireSolution(true);
        }**

![insta](https://user-images.githubusercontent.com/93954052/142002813-7f98f1d2-26c8-4f6f-bb23-92f12cea6ade.gif)
