## I highly recommend becoming semi-comfortable with cheat engine
Obiously, don't use cheat engine in multiplayer because it ruins the fun for other people, but it is a very helpful tool when dealing with problems in mods.
One example is modifying the world state to put the sword back in Gundyr and working around a stuck Gundyr problem. Another one is no-clipping into the Halflight boss
room to deal with Ringed City warps working improperly (see issues). [Igromanru guide/CE table](https://github.com/igromanru/Dark-Souls-III-Cheat-Engine-Guide) makes this easy.

# DS3 Fog Gate Randomizer (Optional DLCs)
Information on program and usage can be found in the description of the [original mod](https://www.nexusmods.com/darksouls3/mods/551?tab=description) (Read this prior to use).
All instruction should be the same for the most part, but ensure the DLC options for other mods reflects the DLCs you have.
Also, keep in mind that the enemy randomizer requires both DLCs to work.  
If you want to use this for the original Dark Souls, use the [upstream version](https://github.com/thefifthmatt/FogMod) to avoid complications.

## Changes in fork
Only minor modifications were done to the original project. I worked around the mandatory DLC problem by deleting (mostly) any references to the DLCs for each version. --- If the program doesn't know a DLC exists, the program doesn't need the DLC.

### Why didn't thefifthmatt do this if this was so easy?
To put it simply, [thefifthmatt](https://github.com/thefifthmatt) appears to believe in sane code that works well and is maintainable. This is a good thing. Should they ever make DLCs optional, they will likely continue to do things in this way, as they should. 

I, on the other hand, quickly and sloppily used horrible practices to make it just work. Having three different version is a testament to that. This is honestly one of the worst ways to implement optional DLCs, but if it works, it works I guess?

## Current Issues
For Ringed City only randomizer, all fog gates leading to Ringed City spawn you in the starting area. I don't know why this is happening.

## Warning
I have done partial in-game testing for the Ringed City only version and out-of-game testing for the others (aka. it didn't give me an error when randomizing). While it should work properly, I don't guarantee that it will.
If you have any issues regarding crashing, infinite load screens, or the DLCs, create an issue here or email me at
[KaranveerPublic+Fog@gmail.com](mailto:KaranveerPublic+Fog@gmail.com).
If you aren't sure whether a bug is from my project or the original, assume it is me first.
If you used any of the versions and they work, please let me know along with which verison you used.

## What about Nexus?
While the Apache 2.0 license permits it, please do not upload this on NexusMods or anywhere else.
Unless thefifthmatt specifically requests it of me, I have no intentions of uploading this anywhere as I've barely done anything and what I did do was badness.
Aside from that, feel free to link this to others as you please.
