# CrossCode Extra Expressions Pack (EX2)
This mod adds additional expressions for CrossCode characters and was intended to be used as a resource package by other mods. 

It does not require a New Home DLC, nor will it cause any errors if it's not installed.

There are no plans for it's further expansion due to burnout and lack of demand.

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
External preview of all new expressions and parts, along with their names for quick reference **is not going to be added**.
  
You can still look through added spritesheets [here](https://github.com/Paradragon/cc-extra-expressions-pack/tree/main/assets/media/face) or check parts and expressions names [in patchsteps](https://github.com/Paradragon/cc-extra-expressions-pack/tree/main/assets/data/characters), but this is less than ideal. At this point in time, we suggest using in-game method, described below.

## In-game

You can preview all new expressions with their names by interacting with the console in the internal test area, accessed by the following command `ig.game.teleport("ex2_testarea")`.  

**By default, there is no other way to access test area without console.**
