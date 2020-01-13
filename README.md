# Configs for Desktop and Laptop installations of CSGO

Laptop (Linux) launch options:
`mesa_glthread=true SDL_VIDEO_MINIMIZE_ON_FOCUS_LOSS=0 gamemoderun ionice -c2 nice -n -3 %command% -high -noforce -noforcemaccel -noforcemspd -noforcercemspd -fullscreen -novid -noheap -noaafonts -noipx -w 1024 -h 768 -disable_d3d9ex -nod3d9ex -tickrate 128 +mat_queue_mode 2 +exec autoexec.cfg -threads 4 -cpuCount=8 -exThreads=1`

Laptop (Windows 10) launch options:
`+exec autoexec.cfg -high -fullscreen -nojoy -novid -w 1024 -h 768 -d3d9ex -tickrate 128 +mat_queue_mode 2 -threads 4 -cpuCount=8 -exThreads=1`

Desktop (Windows 10) launch options:
`-novid -nojoy -d3d9ex -tickrate 128 +exec autoexec.cfg`

### Benchmarks

Laptop specs:
```
   CLEVO W740SU (System76 Galago Ultra Pro - galu1)
   CPU: Intel i7-4750HQ @ 3.2GHz
   GPU: Intel Crystal Wel (Intel Iris Pro Graphics 5200)
   Memory: 1645MiB / 11901MiB (12GB ram, Kingston 8GB 1600 MT/s DDR3 + Samsung 4GB 1600 MT/s DDR3)
   Linux SSD: Crucial_CT500MX200SSD1, SATA 3.0, 500GB
   Windows 10 SSD: KINGSTON SUV500MS480G, mSATA 3.0, 480GB
```

Arch Linux latest `mesa-tkg-git` and `lib32-mesa-tkg-git` (`20.0.0_devel.119033.f06be794572-1`) benchmark results for CSGO:
```
   Benchmark finished. 
   Map: de_dust2 
   Tickrate: 128 
   Ran for 49.0781 seconds 
   Average framerate: 68.92
```

Windows 10 benchmark results for CSGO:
```
   Game freezes once a map loads. Could be a config or launch option error. Regardless, it looks 
   like I will be playing csgo on linux on my laptop!
```
