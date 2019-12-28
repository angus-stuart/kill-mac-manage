# kill-mac-manage

Welcome. If you're here, you probably hate MacManage. What is MacManage? MacManage is an app from Addigy that will not *freaking* stop adding itself to the Dock in Mac. 

This AppleScript will run every 15 minutes, and will remove MacManage from the dock.

To make this work, you'll need to go into `killMacManage.plist` and edit line 11 to your Mac's username.

Then, add `killMacManage.plist` to Users/YOURUSERNAME/Library/LaunchAgents.

Enjoy.
