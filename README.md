# Qubes tools

Various scripts for more efficient qubesing:


## [Run in focused qube](https://gist.github.com/UndeadDevel/82e5f61c9a5065ab9fc5d23a74ae5045)
QubesOS DVM caching mechanism + all sorts of useful functions to run on the qube in focus:
  - open file manager & terminal in focused qube
  - easy screenshots (copies to qube in focus, can open file manager containing the screenshot)
  - restart focused qube and reopen app on origin workspace
  - run other commands on qube in focus
  - count number of open windows of a qube across workspaces

## [NetVM toggle](https://gist.github.com/UndeadDevel/0a9e238db4fe58055eb8b1a40515f3b6)
Toggle whether the qube in focus has the default NetVM or not.  
For qubes with the `anon-vm` tag `sys-whonix` is considered to be the default NetVM.

## [WiFi toggle](https://gist.github.com/UndeadDevel/3ffeb19d66eee72c85d9c5a94ea2b60d)
Toggle WiFi via the command line from dom0 (can be set up with a keyboard shortcut).  
The Gist also includes instructions to keep WiFi off by default when `sys-net` starts.

## [CPU governors toggle](https://gist.github.com/UndeadDevel/6847c10f091dd05f4d70f436070daf22)
Toggle between performance, balanced and power saving governors if using HWP.

## [Trigger Qubes widgets](https://gist.github.com/UndeadDevel/ef7d86118b83ae4bab68243fc38c51f6)
Trigger the keyboard-navigable Devices and Domains widgets with a keyboard shortcut.

## [Trigger App Menu](https://gist.github.com/UndeadDevel/8501e82a534e5daa2ac60e36945167b9)
Open the new App Menu via a keyboard shortcut and move the mouse out of the way if necessary.
