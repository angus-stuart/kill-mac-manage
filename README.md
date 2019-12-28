# kill-mac-manage

Welcome. If you're here, you probably hate MacManage. MacManage is an app from Addigy that will not *freaking* stop adding itself to the Dock in Mac. 

This AppleScript will run every 5 minutes in the background and remove MacManage from your Dock.

## How to set it up:

1. Go into `killMacManage.plist` and edit line 11 to your Mac's username instead of `USERNAME`
2. Add `killMacManage.plist` to Users/USERNAME/Library/LaunchAgents
3. Add `killMacManage.scpt` to Users/USERNAME

Enjoy.
