# Overwatch 2 Lutris Installer DXVK Cache

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

# Contributing 

You can create Pull Requests to update that file when needed.
