# CrossCode Extra Expressions Pack (EX2)
This mod provides additional expressions for CrossCode characters and intended to be used as resource by other mods. 

It does not require a New Home DLC, nor will it cause any errors if it's not installed.

## Installation
This mod requires [CCLoader](https://github.com/CCDirectLink/CCLoader) which you can either install manually or use the [CCLoader installer](https://github.com/CCDirectLink/ccloader-installer).

Once CCLoader is installed, [download a release](https://github.com/Paradragon/cc-extra-expressions-pack/releases) of EX2 and put it into `CrossCode/assets/mods`.

## Mod conflicts
There are no known mod conflicts.  
Although mods that switch playable character or change default expression sprites, naturally, lack proper support.

# What does it do, exactly?
By itself, EX2 has no effect on the game and so is only useful as a resource dependency for other mods. 

This mod adds the following:
- New `media/faces` sprite sheets, prefixed with `ex2-`
- New expression parts (currently, only faces), prefixed with `ex2_`
- New expressions, prefixed with `EX2_`
- Internal test area named `ex2_testarea`, inaccessible without console. 


As mod developer, you can utilize EX2 in following ways:
- Use new expressions in conversations, cutscenes, D-Links or side messages.  
- Use new parts to design your own expression.
- Crop sprites to use as discord emojis.

# What's the point of using EX2?
CrossCode characters have a wide range of expressions, which are quite flexible in their applications. But then, those available in the base game were dictated by the development requirements. And while impressive, by no means do they cover every situation.

It is impossible to convey all human emotions, and we have to make do with whats available. Yet, sometimes, an accurate expression is better than a thousand words. Especially with charaters, who are limited in their ability to speak.

Therefore, the idea of EX2 is to provide a bit more flexibility and color when conveying characters mood or emotion in conversations.

# Where can new expressions be viewed
## External
External preview of all new expressions and parts, along with their names for quick reference is **planned for v1.0 (end of Q4)**.
  
You can still look through added spritesheets [here](https://github.com/Paradragon/cc-extra-expressions-pack/tree/main/assets/media/face) or check parts and expressions names [in patchsteps](https://github.com/Paradragon/cc-extra-expressions-pack/tree/main/assets/data/characters), but this is less than ideal. At this point in time, we suggest using in-game method, described below.

## In-game

You can preview all new expressions with their names by interacting with the console in the internal test area, accessed by the following command `ig.game.teleport("ex2_testarea")`.  

**By default, there is no other way to access test area without console.**

# Moving forward
Life is complicated, so no promises. Overtime, new parts and expressions **may** be added. Most notably this depends on availability of the following: 
- Interesting idea.
- Inspiration to draw.
- Drawing ability to property convey it.
- Free time. 

This mod is intended to have full backward compatibility with it's previous versions. That means if an expression or part is added to **public EX2 release**, their definition in [patchsteps](https://github.com/Paradragon/cc-extra-expressions-pack/tree/main/assets/data/characters) will not be changed afterwards. This allows newer versions of EX2 to be used as dependency even if an older one is required without fear of breaking anything.

The only exception to this rule may be subtle edits of sprite sheets to correct some graphical mistakes or touch up on appearance. Let us be honest, author is as good in pixel art as any other amateur is. Even so, this will be limited to correcting mistakes.

# Feature requests
We don't accept spritework requests for EX2. Not that there will be any, but still...

# Contribution
We are open to pull requests, if you want to include new parts, expressions or anything else, really.