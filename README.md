# Bubberstation config overrides
On the live server these files replace any files of the same name within the config/ subfolder of the repo. 
This is necessary because testing on localhost necessarily requires different configs than the live servers.
To facilitate this this repo is pulled into GameStaticFiles/config/ by TGS at the end of every round(via a helper EventScript).
Actually this is not the case yet, due to difficulties in doing so...

For players: You can make PRs here, but they may be denied without reason.

If you need to add a new config file ideally make a commit with the base config file copied over from the repo & then commit your changes on top of that.
