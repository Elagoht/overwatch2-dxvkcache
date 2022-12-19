# Overwatch 2 Lutris Installer DXVK Cache

![Discontinued](https://shields.io/badge/Discontinued-red?logo=nutanix&logoColor=white&style=for-the-badge)
![Vulkan](https://shields.io/badge/DXVK_Cache-AC162C?logo=vulkan&logoColor=white&style=for-the-badge)

This file is required to play Overwatch 2 properly. Some updates may require
more cache process. Your computer needs that cache file to run graphics
faster. It compiles shader caches itself and this is a very long and exhausting
work for your hardware. So that pre-compiled shaders caches may help you in
this case.

I installed Overwatch 2 via Lutris and I publish that file for Lutris. You can
use this file with other installer scripts. I just wanted to share this as
one-liner command to apply.

Before running the command below, be sure you launched the game at least once.
Then you can download the cache file.

```bash
curl https://github.com/Elagoht/overwatch2-dxvkcache/raw/master/Overwatch.dxvk-cache -o ~/Games/overwatch-2/Overwatch.dxvk-cache
```

Then you can start to play Overwatch 2. 

# Low Graphics Results Better Gameplay

Please consider that. My GPU runs the game stable 144 FPS. But on the maps that
have complete shader caches. Lower Graphs results better FPS and lesser
shuttering. 

# Maps Tested and Passed

* Ilios
* Circuit Royal
* Havana
* Route 66
* Paraiso
* Colosseo
* Horizon Lunar Colony
* King's Row
* Petra 
* New Queen Streeet

# Maps That Not Bad 

* Busan

# Maps That Not Good

* Dorad
* Oasis 
* Junkertown
* lijiang tower
* Hollywood


# Characters

There are no charachters or animation that causes any shuttering. 

# Contributing 

You can create Pull Requests to update that file when needed.
But you must use <https://github.com/DarkTigrus/dxvk-cache-tool> to merge your
cache file with the cache file in this repo. Generated cache file must be
higher file size than this cache file.
