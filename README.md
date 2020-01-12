# Configs for Desktop and Laptop installations of CSGO

Laptop (Linux) launch options:
`mesa_glthread=true SDL_VIDEO_MINIMIZE_ON_FOCUS_LOSS=0 gamemoderun ionice -c2 nice -n -3 %command% -high -noforce -noforcemaccel -noforcemspd -noforcercemspd -fullscreen -novid -noheap -noaafonts -noipx -w 1024 -h 768 -disable_d3d9ex -nod3d9ex -tickrate 128 +mat_queue_mode 2 +exec autoexec.cfg -threads 4 -cpuCount=8 -exThreads=1`

Desktop (Windows 10) launch options:
`-novid -nojoy -d3d9ex -tickrate 128 +exec autoexec.cfg`
