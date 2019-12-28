# kill-mac-manage

Welcome. If you're here, MacManage by Addigy is probably continuously pinning itself to your dock every 15 minutes.

This AppleScript will run every 100 seconds in the background and remove MacManage from your Dock (if it is there).

## How to set it up:

1. Go into `killMacManage.plist` and edit line 11 to your Username instead of `USER`
2. Add `killMacManage.plist` to User/Library/LaunchAgents
3. Add `killMacManage.scpt` to User/AppleScripts (you might need to create the AppleScripts folder if you haven't already).
4. Open Terminal, and enter the following command `launchctl load -w ~/Library/LaunchAgents/killMacManage.plist
`
5. Then, enter the following command into Terminal: `launchctl start killMacManage.job` to make sure it started.

Enjoy.
