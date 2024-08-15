# TDatD-Episode-List-Toggle
A custom setting where you can easily access and track the grades of test episodes, and any custom episodes of The Devils and the Details you wish to make in the future. I probably won't be uploading my own Devils episode, as there are a lot of miscellaneous things to upload and replace when importing a custom Devils episode. However, I still encourage you to create your own Devils episode!

### What does this do?
This mod allows you to switch what episodes are displayed on the progress widget, and selectable from the lobby as a VIP. However, it does so in a very simple manner.
All this mod checks for is the episode's .eds file respective "CHOOSABLE" tag. (e.g SET CHOOSABLE TRUE, SET CHOOSABLE FALSE). When CHOOSABLE is set to TRUE, the episode will appear in the shipping episode list, AKA the official episode list. When CHOOSABLE is set to FALSE, the episode will appear on the test/debug list. It's a very simple inclusion that doesn't require much effort to mod. Though, this does come at a cost.

### The limits of this mod
While this mod is all very simple in nature, you must be aware of this fact to keep this mod functioning properly.
The progress widget will max out of entries at 30 episodes. No more than that. Meaning that adding/loading in more episodes under the .eds tag SET CHOOSABLE TRUE will cause the progress widget to cap out. The episode select function in the lobby remains unchanged however.
Since there are nine test/debug episodes, it would take 21 additional loaded episodes with SET CHOOSABLE to FALSE to cap out the debug/test episode list in the progress widget. That really shouldn't be a problem unless you are a custom Devil's madman.
Another thing to note is that regardless of what episode list is currently active, every episode is loaded upon start up. Meaning that dev-console commands 'forceEpisodeId(param1:String):void' and 'forceEpisodeIdWithEpisodeIntro(param1:String):void' will continue to force the inputted episode no matter what episode list is active. These dev-console commands can still be used freely.

### Thanks for checking out this simple mod!
While this is a very niche mod concept for a very select few people, I still hope you find use in it! Be sure to check out my Youtube channel, if you haven't already, and thanks for taking a look at this mod!

## v.1.01 Hotfix with The Jackbox Megapicker support
So, with the pack updates surrounding support for The Jackbox Megapicker, many swf mods created before this update before this update became defunct. This hotfix ports the mod over to the update and is now supported by The Jackbox Party Pack 7 and The Jackbox Megapicker
