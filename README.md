# Baldur's Gate 3 Artificer
Collaborative effort to bring Artificer and its subclasses to Baldur's Gate 3

## TODO List
https://github.com/Kidel/BG3_Artificer/issues

## Changes from 5e
Like Larian, we had to make some changes to Artificer due to the nature of the medium. There is also the fact that we had to adapt to Larian's pre-existing design choices.
Some of the core functionalities of Artificer are already in the game available to any class, so we had to get creative. 

- Spell slots in multiclassing: normally Artificer would give spell slots equal to half your levels **rounded up**. Unfortunately BG3 just uses the result of the `MulticlassSpellcasterModifier` and doesn't allow us to pick between rounding up and rounding down the result. To compensate for this we gave the class a 0.67 multiplier instead of 0.5. This is the closest we can get and just gives a free extra slot at level 1(fullcaster)/11(artificer) and 1 less in 11(fullcaster)/1(artificer), but should be correct at intermediate levels, at least odd ones. 
- Arcane Focus related abilities in general: BG3 has no spellcasting focus, so we made those as a buff you can apply to the character. This also applies to Arcane Firearm and infusions on a spellcasting focus. Unfortunately this also means that abilities like Armorer using the armor as focus don't really apply. We compensated for that.  
- Repeating Shot: most of the qualities of this infusion have been included by Larian by default on crossbow and bows (no ammunition expended, no reload action), so we made it as a buff on the crossbow that unlocks a skill to use 2 force type projectiles per attack and changes the damage type to Force.
- Bag of Holding: again Larian made every character backpack in the game invisible and able carry items of any size, plus made the magic "shared inventory" that kind of works like something linked through the Astral Plane. But this infusion is iconic, so we still wanted to include it somehow. We made it as a "bag infusion" instead of "replicate magic item", and it unlocks infinite carry capacity. We also added the effect for double Bag of Holding at the cost of 2 Infusion Slots (but nerfed it a bit, forcing the character to die in the process, as you can't remove your inventory). We also made sure that the infusion stopped working in the Astral Plane (it stays with no effect if it was applied in advance).
- Boots of the Winding Path: in 5e they allow a "rewind" action, having you teleport to a space you've been previously. Since there is no such mechanic implemented in the game yet, we initially decided to just have them unlock Misty Step once per short rest. Then we changed perspective and thought about the original usage. Basically what the original boots allowed was to go melee, make an attack and then go back without provoking opportunity attacks, so we removed Misty Step (which is already on a ton of accessories and boots) and instead increased movement speed by 3m and the wearer doesn't provoke opportunity attacks.
- Magic Item Adept: not really interesting with the effect described in the manual, we decided to split it into 2 skills. The first one is simply called Magic Item Adept and gives a +1 bonus if you attack with a Magical weapon (only weapons can be magical in bg3). THe second one comes from Alchemical Mastery (more on that later) from Alchemist and make a weaker version for base Artificer with Chemical Adept. This one was super fun to make and use. Allows the Artificer to magically extract chemicals from medium size objects and bodies. Extracted chemicals can be used to craft base ingredients for potions and explosives. 
- Alchemical Mastery: new level 10 skill for Alchemist, tied to Alchemical Adept / Alchemical Extraction skill of the base class, allows to create rare ingredients for the in-game Alchemy system. We won't be adding other effects from Chemical Mastery as that would be unfair to other subclasses, but helps the feeling of the Subclass as a master of alchemy, so better than all other classes with the in-game Alchemy system.
- Chemical Mastery: originally replaced by Alchemical Mastery, it's now identical to 5e but doesn't require a focus. 
- Battle Smith and Artillerist pets: stronger overall and scale better with the base class.
- Spell-storing Item: even if we developed a system to add effects to items and have those effects unlock skills on the caster, the system is complex and convoluted and wouldn't be wise to use it for a wide variety of spells. Instead we decided to take advantage of scrolls. We made it onto a skill that can create {IntModifier} scrolls per day storing spells that the Artificer knows. Scrolls disappear at long rest, but you're not limited to {IntModifier} uses of 1 spell, you can craft different ones and give them to friends. This way you can have your Fighter cast stuff like Heat Metal or Web, also without having to pass a weapon back and forth. 
- Replicate Magic Item: BG3 throws crazy powerful items at you every 5 minutes. We didn't want learned infusions to be wasted when you find a better item, so we made this a lv10 unlock, and it unlocks 5 really powerful items you can create at will targeting the Artificer or a companion.
- Arcane Armor: none of these effect have any consequences on BG3. We changed it in Larian Ranger style and make it give Heavy Armor proficiency. Armor Models are unchanged. 
- Armor Modifications: kind of useless, has been replaced by Perfected Armor. Only difference is that the light effect from Infiltrator doesn't also give advantage (just the disadvantage) and the reaction from guardian is on attack on an ally and pulls 6m instead of 9m.
- Perfected Armor: since a simpler version of this one has been given at level 9, this one got replaced by Perfected Armor MkII, which is more similar to the TT version of Perfected Armor and gives 1 extra d6 on Lightning Launcher, disadvantage after being hit by the aforementioned skill and finally deals damage when Thunder Gauntlets interrupt the enemy and pull. 