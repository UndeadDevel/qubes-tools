# Qubes tools

Various scripts for more efficient qubesing.
Find the SHA256 hash of the Gist zip file beneath each section.


## [Run in focused qube](https://gist.github.com/UndeadDevel/82e5f61c9a5065ab9fc5d23a74ae5045)
QubesOS DVM caching mechanism + all sorts of useful functions to run on the qube in focus:
  - open file manager & terminal in focused qube
  - easy screenshots (copies to qube in focus, can open file manager containing the screenshot)
  - restart focused qube and reopen app on origin workspace
  - run other commands on qube in focus
  - count number of open windows of a qube across workspaces

SHA256: 020a5ba5b0623178aacce11604977968bb061b5aa21c2f9d3d64bc18555ad7f0

## [NetVM toggle](https://gist.github.com/UndeadDevel/0a9e238db4fe58055eb8b1a40515f3b6)
Toggle whether the qube in focus has the default NetVM or not.  
For qubes with the `anon-vm` tag `sys-whonix` is considered to be the default NetVM.

SHA256: 6240224c4a7e2a60924fdfcda4b6aff6fe1c309cf9cd386ad1666f3f4fd79cbb

## [WiFi toggle](https://gist.github.com/UndeadDevel/3ffeb19d66eee72c85d9c5a94ea2b60d)
Toggle WiFi via the command line from dom0 (can be set up with a keyboard shortcut).  
The Gist also includes instructions to keep WiFi off by default when `sys-net` starts.

SHA256: b7f1c94b966f1c70da5de49d79332159f59e24b51ed0e90f9846a672f8001d8a

## [CPU governors toggle](https://gist.github.com/UndeadDevel/6847c10f091dd05f4d70f436070daf22)
Toggle between performance, balanced and power saving governors if using HWP.

SHA256: 2a7a22a6cbea9e25f0cc20cd0479811e6842c23a2d1b391d42a72a8ac976559b

## [Trigger Qubes widgets](https://gist.github.com/UndeadDevel/ef7d86118b83ae4bab68243fc38c51f6)
Trigger the keyboard-navigable Devices and Domains widgets with a keyboard shortcut.

SHA256: 8c90ec9644fad8d2096f0d27a4a5187120f6d98b45451f71d7d1595c06108132

## [Trigger App Menu](https://gist.github.com/UndeadDevel/8501e82a534e5daa2ac60e36945167b9)
Open the new App Menu via a keyboard shortcut and move the mouse out of the way if necessary.

SHA256: ff84ca35089d016e03b43df2266f685c8aa38b3a14a187c3a8784334265e5bb4
