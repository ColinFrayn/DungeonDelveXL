# An Introduction to DungeonDelveXL


## Introduction

DungeonDelveXL is a fully-featured role-playing game written entirely inside Excel, using VBA (Visual Basic for Applications) - the macro language that Microsoft bundles with its Office suite. I have used only internal Excel functions to handle all the graphics, and have not imported any external artwork. Which is good, because I suck at art.  DungeonDelveXL contains all the features that you would expect of any other role-playing game: customisable characters; a large explorable world map; randomised dungeons and encounters; a wide range of monsters, spells and skills; a huge selection of items to collect; a detailed crafting system; and much more besides.


## Playing the Game

DungeonDelveXL is built inside Excel, and as you open the workbook, you will be presented with a single sheet – the Main Form – which contains three options. You can either start a new game, save the current game (if you have one running) or open a saved game. Please note – the game data are stored in memory, and not on the sheet, so if you want to save your progress, YOU MUST SAVE YOUR GAME FROM THE MAIN FORM AND NOT THROUGH THE EXCEL MENUS otherwise the progress will be entirely lost.

Loading and saving games is all pretty self-explanatory. However, since we don’t have anything to load or save yet, let’s start a new game.

Anyone familiar with RPGs will recognise the character creation process in DDXL. There is a fairly wide range of options to tweak, but they're a little bit different to what you might have seen before. I'm experimenting with a slightly different model for tracking your character's strengths and weaknesses. I think it works quite well. You can also (obviously) set your Name and Symbol. The Symbol is a one- or two-character identifier for your character that will be used to identify him/her in battles. I deliberately didn't include gender on the character screen, so feel free to pick whatever name you want and customise your character further using the skills and attributes below.

## The Races

There are seven races in DDXL: Human, Elf, Dwarf, Orc, Goblin, Halfling or Sprite.  The choice of race affects the various modifiers applied to your primary abilities. For example, Orcs are much stronger than other races, but less intelligent. Elves are more intelligent and nimble, but less tough. Etc. I set this up so that all the racial bonuses add up to a net overall benefit of zero, so choosing the race you want to play is entirely a matter of your playing style. However some races also have extra benefits (elves and goblins can see further in the dark, dwarves are resistant to poison damage, orcs travel faster).

You might think that this makes certain races only suitable for certain roles, but because of the way I have set up the abilities in DDXL, that is not necessarily the case. For example, Orcs may be strong and dumb, but they can still make passable magic users because they have decent toughness, giving them resilience to enemy attacks (and balancing the tendency for magic users to be a bit squishy). A higher strength means that they can also wear more armour (also counteracting the squishiness) without getting as heavily encumbered.  Elves can make good fighters, because a higher agility corresponds to a better defence skill. Also, at high level the ability differences tend to even out once you have significantly better magical armour and weapons to boost your skills much higher.


## The Abilities

The five major abilities are each related to many in-game skills and values. Primarily, however, these skills contribute in a few specific areas. They all start with a skill of ten, plus or minus the appropriate modifier from your race. Here's a list:

-	Strength - Increases physical attack skill and carrying capacity.
-	Toughness - Increases maximum health.
-	Endurance - Increases maximum stamina and stamina regeneration.
-	Agility - Increases physical defence, and also slightly increases magical attack and defence.
-	Intelligence - Increases magical attack and defence.

You can choose to rebalance the points in these abilities as you see fit, though in the character creator the total must always sum to the same value. So in order to increase one stat, you must first reduce another. You can increase the stats beyond this limit later on in the game, so these choices are not completely permanent.

These stats are also used to measure your character's ability at some of the non-combat skills that they will learn over time. For example, weapon-smithing requires high strength.


## The Classes

Choosing a class is also important as it will determine the skills and abilities that your character will gain as he or she gains levels. The classes available are:

-	Warrior   – A strong fighter, with excellent physical attack and defence skills.
-	Barbarian – A reckless fighter with an Enrage skill. Stronger attack than the warrior, but weaker defence.
-	Priest    – A magic user with a range of spells balanced towards defensive/support roles. Weak at physical combat.
-	Wizard    – A magic user with a range of spells balanced towards offensive roles. Weak at physical combat.
-	Paladin   – Half way between a priest and a warrior – some magic abilities but with passable fighting skills.
-	Warlock   – Half way between a wizard and a warrior – some magic abilities but with passable fighting skills.
-	Thief     – A nimble character with decent close combat ability, and a load of extra skills to help you through the toughest dungeons. The Thief is also better than other classes at finding hidden doors, traps and treasure and has the ability to enter stealth and attack creatures from the shadows.
-	Ranger    – A long-range warrior, able to call a tame hunting wolf to fight as a companion. Moderately strong in close combat but excellent at range (does not suffer from hit penalty due to range, unlike other classes).

Classes don’t affect your base abilities, but they may offer new skills that you can master. As opposed to most RPGs, the class you choose doesn’t affect the armour you can wear, the skills you can learn (except a few class-specific ones) or the weapons you can wield. It does affect the way in which your attack, defence, magic attack and magic defence scale with level (although not your stamina or hit points). Classes also alter the number of skills of each type (combat skills and non-combat skills) you learn per level, and which spells you can learn (if any).


## The Primary Abilities

I do things a bit differently to other RPGs in this regard. Hit points (HP) are fairly standard – a measure of how much health you have remaining. If this drops to zero then you’re dead (sorry - no resurrection!).  But Stamina is a bit different - it is a measure of how much stuff you can do in a single turn. And that applies to movement, skills, attacking and spellcasting.

The stamina cost of certain actions is also affected by the degree of encumbrance that your character is suffering, with heavily encumbered characters forced to spend up to twice as much stamina per action as unencumbered characters. So heavily armoured characters may take less damage, but can probably do less per turn, too - unless they have a very high strength skill to avoid the encumbrance.

Characters moving under stealth also require twice as much stamina per action. Stamina regeneration, and the amount of stamina required to perform actions, can also be affected by spell effects on your character, such as Haste/Slow and being entangled/frozen.

Experience is a measure of how much your character has learned so far. As experience climbs, it will eventually reach a certain value at which your character progresses to the next level. The amount required to reach each level increases with that level, making higher levels harder to achieve than lower levels. Gaining a level gives you more HP, more Stamina and more skill points. It also affects the attack and defence skills, with the number of points you gain being determined by your class.


## The Character Sheet

Once you are happy with your character, you can start your new campaign. Click the button to generate your character, and you will find yourself in your home town, right at the north end of the continent in which DDXL takes place. You will have a party sheet open, in which you can check the characters in your group (just you for now) and the group's location and cash reserves. Each character can be active or inactive. You can have up to four active players at any one time. These are the players that will be taken on any mission with you. The rest will be left safely behind. There is also a button to open the crafting interface, if you are safely in a town. Any characters that have crafting abilities will have their available recipes listed here, and you will be able to make items of the relevant types, if you have the required materials.
Later on you will also get enough money to hire a pack mule, which can carry some of your excess equipment for you. That button can be found at the top of the screen, but those things are expensive, so you’ll have to wait a few levels!

Clicking on the "Character Sheet" button will show you the detailed character sheet for each character, in which you can modify the character's equipment, learn skills and explore the statistics that this character has built up.

The character sheet functions are mostly accessed by the various buttons scattered around in the relevant locations. For example, to learn a new skill, click on the "+" button next to a blank row. (There are a fixed number of rows for skills, so you can't learn every skill in the game - choose carefully).  To increase the level of an existing skill, click on the "Plus" next to it, if you are not at maximum level and you have spare points to spend. Warning - neither of these actions can be undone later, so choose carefully!

Spells (if you have any) are learned separately in special buildings - see below. You can learn a maximum of one spell per level, though they can be cast as many times as you like, provided you have sufficient stamina. You can also choose to spend one of your spare spell slots on improving your skill with an existing spell. Specialised and Master level spells do more damage (20%,40%), have longer durations (50%,100%), confer more resistance (20%,40%), have longer light range (+1,+2), and summon stronger creatures, depending on spell type. You can learn specialist and master versions in exactly the same way as normal versions, but as if they were (4, 8) levels higher. Again, all of this can only be done at specialist buildings, not through the character sheet.

For all skills and spells, you can find out more about them by clicking the "?" button at the top of each list. For spells, this also allows you to unlearn the spell, and free up the slot(s) that it was using, though you do lose the money you spent on learning that spell.

You will notice that the character sheet displays the currently equipped items in one location, and then at the bottom of the sheet is found the rest of your inventory. You will start the game with a few bits of low-quality beginner equipment, but that's it. You can use the buttons beside the items in both locations to wear/remove armour, equip/unequip weapons/shields and to destroy items you don't want. Unwanted items may also be sellable in local merchants' shops.  If you have any other members in your party, you will also be able to transfer items between characters from here.

The main skills here worth noting are:
-	Attack (Att): Ability to hit with weapons, and do more damage per hit.
-	Defence (Def): Ability to avoid being hit by weapons, and dodge/deflect/parry some of the damage done.
- Magic Attack (MAtt): Ability to hit with spells, and do more damage per hit.
-	Magic Defence (MDef): Ability to avoid being hit with spells, and avoid some of the damage dealt.
-	Protection (Prot): Damage reduction thanks to the armour you're wearing (applies to all damage types).

Note that, in each case, the contributions from the various abilities, equipment, magic effects etc. are listed alongside or beneath the stats themselves.

On the character sheet are also shown your current HP and Stamina. Stamina rebuilds quickly, but HP does not - you need to rest, or rely on magic or first aid to heal.  You can also see your current experience. When you reach the target value shown then you will gain a level. When gaining a level, you will get some new skill points, your base Att/Def/MAtt/MDef will increase and your maximum stamina and HP will go up. Every four levels, you also get the choice of a primary ability to increase by one point free of charge.


## The Town Map

The Town Map appears only when your party is in a town, and not in a mission. You can see a map of the current town, and the buildings that it contains. Towns are of differing sizes, with some towns containing many different shops, and others just a few. The town you start in is a small-to-medium sized town right at the northern end of the continent. 

Many of these buildings are numbered, with a key on the right hand side showing what each building represents. These can be of several types:

-	Town Hall where you can take on new missions.
-	Mercenary Guild where you can hire extra members for your party.
-	Magisterium / Temple where you can gain services from wizards or priests, and learn new spells of those types. You may also be able to enchant equipment and increase stats.
-	Merchants where you can buy and sell items of specific types.
-	Inns/Hotels where you can rest from your adventures and recover from fatigue.

Click on the building icon to visit that location and trade/interact with the owners. You will also notice on the Town Map screen an indication of your party's reputation within this town. Your reputation starts off as "Unknown" and gradually rises through levels of "Familiar", "Renowned", "Famous", "Heroic" and "Legendary". Some options in the town's various merchants are not available until your party is of sufficiently high reputation (especially in the Temple and Magisterium). Reputation also gives you a discount to the prices in shops, with 2% better prices for each level above "Unknown". Also, once you reach “Famous” reputation, new “Heroic” missions will open up. There will only ever be one heroic mission at a time, but it will be significantly more difficult and also more rewarding than the other missions available.

At the top right of the map is a button allowing you to zoom/unzoom the view.

When you move out of the town, the Town Map will vanish so you won't be able to interact with merchants again until your party returns to a town. Which brings us to the world map...


## The World Map

The World Map shows you where you currently are in the world, and the bits of it that you can currently see. As you will notice, most of it is currently black, indicating that you haven't visited those places yet. You will see an icon for your party located on top of the town in which you started out (an orange rectangle). Squares will either be empty (sea or land, depending on colour) or they may have icons in them indicating the terrain type. These are Forests ("^"), Rocks ("o"), Farmland ("#") and Marshes ("~"). Different creatures are found in different areas, and different materials can be found by exploring there.

As you switch to this page, the map control dialog will also pop up. This gives you a direction control, allowing you to move your party North, South, East or West (provided that route is possible), plus a "?" button in the centre, which lets you search the current area for anything that can be gathered.  Be warned, though - as you wander around there is a chance that you will be ambushed by creatures or bandits native to the area. Searching the area makes that even more likely. So you must balance risk and reward.

Every square you move (and every time you search) takes one day.  If you’re moving over more complex terrain like marshes then it takes longer.  As time moves on, the stock available in the shops in each town will change - some items will disappear and new ones will appear, so make sure you check back at your favourite stores to get their latest kit. The same goes for available mercenaries and missions.

Also on the map control is a button allowing you to build a road in a certain location. You can build roads on any square which is not already a town or farmland. Building roads can be quite expensive, and takes at least 5 days, with more complex terrain taking longer and costing more. During the road building process, events may occur to delay or even abandon the construction. However, once your road is built, moving makes you much less fatigued and you are significantly less at risk of being ambushed.

As you travel (and as you complete missions - see below), your party will become increasingly fatigued. The only way to cancel that out is to pay to sleep the night in an Inn or a Hotel (the latter will rest you much more, but will cost more per night). If you rest for long enough, you will gain the "Well Rested" bonus in your next mission, which provides bonuses to stamina and attack/defence. Being tired instead penalises the same statistics and also weakens you physically.

If you find a town, you can move into it safely and the Town Map will appear again. In a town you won't get attacked by creatures (but you can't search either). The farmland around towns is also much safer than the wilderness outside, but won't get you as many resources.

Warning - as you travel further south, monsters get increasingly tougher. So take care! You might want to stay near the north coast until you have built up a bit of strength. Of course, further south the rewards are higher, too, and shops stock items that are much more awesome. And reassuringly more expensive. Also, temples and magisteria are able to teach higher-level spells, once your reputation is high enough with each town.


## Missions 

Sooner or later you will end up involved in a mission, either by choosing one at a town hall, or by being ambushed in the wild. There are two types of mission, but the general idea is identical in each case. Indoors missions (caves and dungeons) are discovered from the town hall, whereas wilderness encounters are always outside. If you choose a mission from the town hall, you can abort at any time by returning to the entrance, and return home (admittedly without any rewards). However, if you are ambushed, there is no escape - you must fight or die!

The mission screen looks superficially like the world map or town map. There is a map area in the centre that shows your current location (and those of your party, if any are with you), together with everything you have explored (covered with a "fog of war" if you cannot currently see in that location). Monsters, treasure, doors and traps etc. are also displayed in here.  For tiny maps, this will show the entire map, but for any larger maps, you will only see a portion of the entire map, and must scroll around it either using the Zoom buttons next to your characters, or by choosing a character (or square) and hitting "Centre Map". If you have a larger monitor then you can expand/reduce the size of the mission map using the “>” and “<” buttons at the top.

Along the right hand side are the statistics for the characters currently active in this mission. You will also see buttons to end the current mission if you have achieved the objectives, to centre the screen and to transition between levels - when your party is all standing on either an entrance/exit zone or stairs up or down. The mission begins with everyone on the entrance area (marked in yellow with “X”s). Stairs up and down are similar, marked with "+" and "-" respectively.

As with the world map, the MissionControl dialog will appear automatically whenever you select a character (by hitting "Zoom" or by clicking on them in the map). The MissionControl dialog gives you the option to move around, to attack creatures, to cast spells and use skills, and to check your inventory. You can also search (using the “?” button). Searching can uncover secret doors, or even hidden treasure. Most of this should be obvious, I hope. The "Use" button allows you to interact with items in the world, such as opening doors or disarming traps.  Thief class characters are better at all of this, of course. They are also better at sneaking around without being spotted. The chance of a creature attacking is related to the distance between you and it, the difference in levels, the armour you are wearing (metal is noisy!) and the Stealth skill, if you have it. Creatures can't see through doors, but once you open a door and make your presence known, even if you close it, certain creatures are able to open those doors and chase after you.

Note that the distance you can see is rather long - not quite infinite, but certainly more than the visible map area. However, in caves and dungeons, you are limited by the extent of your light sources. You start off with a basic torch, which isn't very powerful (and which isn’t equipped by default). You can upgrade that later, or use spells to create light sources. Even if one character doesn't have a light source, he or she can rely on those of the other party members. Managing light range is a key skill at lower levels.

You will occasionally find treasure (either by searching, or by killing creatures that drop it). This will be displayed in a square with a “$” symbol. You can interact with this by moving to the same square, and opening the Inventory. This view allows you to pick up or drop items, to use certain items that have magic properties, and also to skin corpses for creatures that allow it (provided you have the “skinning” skill). Remember that your characters can only carry a certain amount - illustrated by the encumbrance indicator at the top of the Inventory screen.

That's pretty much it for the Mission screen, which means that it's pretty much it for the game. There are other things to learn, of course, but you'll discover those as you play. That's part of the fun.

If you want to know a bit more about the background to the game, please read on. Otherwise, dive in and enjoy DungeonDelveXL!



## Background Details

### Why?

Well, that’s a good question. I could have written this project in a more sensible language and it would look better, it would be easier to debug, it would be faster and it would have taken a fraction of the time to write. But that’s not really the point – there are already loads of great RPGs written that I could play if that’s all I wanted. The idea for this project was to learn how to write code for Excel (using VBA), and what better way to do that than to write a game that I enjoyed?  I was also inspired by the excellent Arena RPG, also written in Excel, which was released in spring 2013. That project uses a lot of external artwork and has a detailed story running through it – I enjoyed Arena, but decided that I wanted to go a different route.  It is well worth checking out at http://carywalkin.ca/2013/03/17/arena-xlsm-released/


### About Me

I have been writing computer code since I was 9 years old, having had a long fascination with computer games. I currently work as a professional developer and team manager within a large financial services company.  We use Excel heavily at work, though I hadn’t written any VBA before this project (except for one or two trivial macros).  Consequently, if you are a VBA expert, you can probably see from the code that this project was very much a learning process – I made a lot of poor choices early on that, with hindsight, I shouldn’t have made and have caused some of the later development to be harder than it should be. I’ve fixed some of these choices as I progressed through the project, but some remain. There are also some other choices that I’m fully aware are sub-optimal, but I did it that way because it was easier and, frankly, it didn’t matter. There is a bit too much copy-and-paste (though, in my defence, there is no good IDE for refactoring, and the woefully poor implementation of OOP in VBA makes good design pretty-much impossible.)


### About the Project

Role-playing games have been around for decades, and for many of us they provided some of our most enjoyable memories, growing up with the first generation of popular computer games in the early-mid 1980s. I was a huge Dungeons and Dragons fan in the late 1980s and throughout much of the 1990s, and this translated for me into online Multi-User Dungeons (MUDs), the precursors to the modern-day blockbuster MMO such as the Ultima series, Everquest and World of Warcraft (amongst many others).  Being a rather anti-social sort of person (and a very bitter loser) I always preferred the single-player stories that were available in games such as Eye of the Beholder, and later in the genre-rejuvenating Baldur’s Gate series and its many spin-offs. To me, the joy of exploring an entirely new world was the most enjoyable component of these games, and as my character(s) gained in power, wielding shiny new razor-sharp swords of relentless smiting, it was always fun to return to the lowly place where my story began and mercilessly pummel a few of those smug goblin raiders that caused me so much pain in the early days.

It seems to me that there is still a huge community of gamers who hearken for those early, simpler days of RPG joy. I’m not convinced that it is anything particularly special about those games – perhaps it is merely that those games happened to be created during the most formative years of my life – but whatever the reason, it is in the simpler, exploratory RPGs that I still derive a great deal of enjoyment. The only sadness was that the game worlds were usually finite, and once I had explored everywhere and defeated every enemy, the game was over and my character’s story would reach its end.

The idea for DungeonDelveXL came to me many months ago, mainly triggered by playing Arena.xlsm (as mentioned above). I wanted to build a fantasy game world that would offer potentially infinite variation, with procedurally-generated worlds and procedurally-generated dungeons within them; a world with random encounters, scores of different creatures with all manner of variations, and a huge range of crafting, gathering and enchanting to be done.  And I wanted to do the whole thing in VBA for, well, a laugh.  The project began in June of 2013, and the first playable version appeared in late September. All in all, the best part of four months, and a thoroughly enjoyable experience it was, too. Mostly. Except for VBA, which is a horrible language with which to build anything sizeable. But that’s another story. Since 2013 I’ve added a few extra features and fixed loads of bugs, of course.


## Development / Contacts

### Bugs and Development

After launch, I will be putting far fewer resources into continued development, though I will endeavour to fix bugs discovered by the community.  I do have a ToDo list of features that I may add in future versions, but it's not obvious when I will get around to doing that.

DDXL has been tested on Microsoft Office 2007, 2010, 2013 and 2016, and on Windows XP, 7, 8.1 and 10. I'm sure other people have tested it on other configurations, but I haven't and I'm sure there will be issues - especially if you use a very old version of Office. No, I don't have any plans to fix those issues - there just isn't the time and I don't have access to those old versions against which to test. I have heard that it doesn’t work on Office 365. If you have access to that version, and you know how to debug VBA, then please let me know what you find. There have been some issues running on computers with different regional settings (which affect how Excel reads numeric values). I fixed a few of these, but there may be more.

I haven't tested this on a Mac and I'm pretty sure it won't work.  And no, it won't work on OpenOffice. I have no plans to port this to Unix for much the same reason that I have no plans to remove my own eyeballs with a rusty spoon.

If you want to work on extending and improving DDXL then please contact me. I'm always keen to see new community developments. Merging the codebase might be tough, though, so please don't be offended if I don't include your changes into the main branch. Still, feel free to release your own version of the game provided it is properly attributed to me as the original and primary author, together with a link to my home page (www.frayn.net) and the DDXL web page (www.frayn.net/games/ddxl).


### Contact

If you find a bug, then please contact me. My contact details are available on my website at www.frayn.net. Have patience though - I may not have the time to respond to your query, and I may not have the time to fix the bug for a while. But I am committed to fixing any bug that looks like it will reduce anyone's enjoyment of my game. Just maybe not immediately...


### Legal

DungeonDelveXL - An Excel-based role Playing Game.
Copyright (C) 2013-2025 Colin M Frayn

This program is free software: you can redistribute it and/or modify it under the terms of version 3 of the GNU General Public License as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

See <http://www.gnu.org/licenses/> for the licence details.



Thanks for reading. Enjoy the game!


Colin Frayn
London, UK,
December 2020


