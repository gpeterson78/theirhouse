# theirhouse
raspberry pi and openvpn based backup solution

## current status: completely broken

this is my hacked together, cheap backup system for important crap.  Runs on a raspberry pi, nails up an openvpn connection back to your home base (I suggest, and will try to put together instructions for OPNsense) to act as an rsync and/or smb target for backing up stuff, and things, and junk, and shit, and crap...

oh, the name, it's because all my infrastructure at home has been named after The Office for like, ever now..  I wanted to call it the warehouse but that was just too generic.  theirhouse just kinda fits the project and stays in the right spirit.

- for some reason, currently has ubuntu instead of rasbian or debian, that's gotta be job 1.
- I apparently trashed the old documentation I had for this so might as well start from scratch.
	- did at least find the openvpn config, so that should be easy.
- old lego case fell and broke, replaced it with a 3d-printed one.
    - used [this one](https://www.printables.com/model/336576-terrapi-extreme-duo-open-frame-case-for-raspberry-). 
    - probably should have used [this one](https://www.printables.com/model/355311-terrapi-evo-dual-ssd-case-for-raspberry-pi-3-4).
    - kinda like it though, larger frame makes for easier cable hiding.  I was also able to flip the pi and mount it 'inside' the case but I did wind up drilling some new holes and snipping away some material.  might just have to remix that model or create a new one of my own.