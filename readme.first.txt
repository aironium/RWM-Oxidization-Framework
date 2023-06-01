Welcome to the [Oxidization Framework] v0.0

This includes a lot of features that are easily implemented on to your units, projectiles, turrets, etc. via copyFrom and @copyFromSection as well as @define and @global.

You install this into your mod by taking the Oxidization Framework folder and placing it directly into your mod folder, and then you can copyFrom as you need.

Since things present in this is not at base loaded by the game, it will have little to no effect on performance or loading, so you wont have to delete features you aren't using.

Browse around the folders to find the features you want to use, each folder will contain a readme.txt, this will explain how to use the feature in your mod, with a step-by-step guide to do so.

[Contributer Notes]
1) Does not contain graphics, sounds, or similar files, to keep filesize down. They may include pre-configuration standard graphics from the "SHARED:" folder.

2) Each Feature needs a separate sub-folder. If a feature has more "plug-ins" to extend it, they'll have to be sub-folders in the sub-folder.

3) If a feature wants to use @global and @define, they need a unique prefix. For example a feature called "Artillery" could have the prefix "ART".

4) All [template_X] needs to include a pre-fix for the mod, the same as used for @global and @define. So would be [template_ART_turret] for example)

5) All template files that you need to copyFrom needs to have the extension ".copyFrom". Any other template file you use (for organizational purposes) needs to be named .template

6 Each feature needs a step-by-step guide written so a 5 year old could follow it in a file called "readme.txt"