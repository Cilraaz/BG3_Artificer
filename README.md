# Baldur's Gate 3 Artificer
Collaborative effort to bring Artificer and its subclasses to Baldur's Gate 3

## TODO List
### Base Class
- [ ] Make class icon and push it to ImprovedUI
- [ ] Implement Spell Slot progression up to level 12 (get from here: http://dnd5e.wikidot.com/artificer)
- [x] Implement Infusion Slot resource
- [ ] Implement Infusion Slot progression up to level 12 (get from here: http://dnd5e.wikidot.com/artificer)
- [ ] Implement Infusion learning progression
- [ ] Implement cantrip progression up to level 12 (get from here: http://dnd5e.wikidot.com/artificer)
- [x] Implement base proficiencies
- [ ] Optional Rule: Implement firearms proficiency
- [ ] Implement starting equipment
- [ ] Find a way to implement Magical Tinkering (could be just Light Cantrip and Minor Illusion Cantrip)
- [ ] Implement Infusions themselves (get from http://dnd5e.wikidot.com/artificer:infusions). Infusion are learned but **must be prepared.** Not all infusions are interesting. Most of them can be skills copied from Pact of the Blade. 
  - [ ] Arcane Propulsion Armor -> infuse armor with an effect that increases speed by 5feet.
  - [ ] Armor of Magical Strength -> infuse armor with passive that gives Prone immunity and advantage on Strength checks.
  - [ ] Boots of the Winding Path -> infuse boots with Misty Step skill unlock.
  - [ ] Enhanced Arcane Focus -> infuse weapon to get +1 to spell attack rolls.
  - [ ] Enhanced Defense -> shield or armor give +1 to AC, +2 after level 10.
  - [ ] Enhanced Weapon -> weapon gives +1 to attack and damage, +2 after level 10.
  - [ ] Homunculus Servant -> fast way would be Find Familiar, custom models in the future.
  - [ ] Radiant Weapon -> like Enhanced Weapon (except the +2) but also unlocks Light cantrip.
  - [ ] Repeating Shot -> +1d4 force damage to ranged weapon.
  - [ ] Replicate Magic Item -> oh boy.
    - [ ] Bag of Holding: unclear if the game allows for the fixed weight "regardless of contents" and it's not really useful in BG3. I'd just replace it with a spell that costs 2 infusion and replicates Gale's explosion, just for the lol (it's what happens if you put a Bag of Holding inside another).
    - [ ] Other magic items we might want to make. 
- [ ] Implement Flash of Genius (similar to Guidance Cantrip)
- [ ] Implement Magic Item Adept (create a magic item once per long rest using Gold or a Magic Item resource)
- [ ] Implement Spell-Storing Item (create a spell scroll)

### Battle Smith
- [ ] Implement Always Prepared spell progression up to level 9 (get from http://dnd5e.wikidot.com/artificer:battle-smith)
- [ ] Add proficiency with Martial Weapons
- [ ] Implement Battle Ready (magic weapons use Intelligence instead of Strength or Dexterity, see Pact of the Blade)
- [ ] Implement Steel Defender (can initially copy Beast Master pet and go from there, a custom model would be great in the future)
- [ ] Add Extra Attack at level 5
- [ ] Add Arcane Jolt (2d6 force damage added to weapon attacks and Steel Defender -> unlocks a temporary spell to heal a target, see Storm Sorcerer fly after spell)

### Alchemist 
- [ ] Implement Always Prepared spell progression up to level 9 (get from http://dnd5e.wikidot.com/artificer:alchemist)
- [ ] Implement Experimental Elixir resource
- [ ] Implement Experimental Elixir (random effect similar to Wild Magic or selected via spell container)
- [ ] Implement Alchemical Savant (an easy way could be to get passive damage buff on spells and expend Experimental Elixir to heal)
- [ ] Implement Restorative Reagents (an easy way could be to simply add more powerful elixirs to Experimental Elixir + add lesser Restoration using Experimental Elixir resources instead of Spell Slots)

### Armorer 
- [ ] Implement Always Prepared spell progression up to level 9 (get from http://dnd5e.wikidot.com/artificer:armorer)
- [ ] Implement Arcane Armor (could be a magically crafted armor or a status to an existing equipped armor, similar to Pact of the Blade). Container should allow selection of 2 effects:
  - [ ] Guardian Armor gives 2 skills: Thunder Gauntlets and Defensive Field. Thunder Gauntlets is an unarmed strike attack that's basically 1d8 Thunder Distracting Strike. Defensive Field is just temp hit points passive added to the armor. 
  - [ ] Infiltrator Armor gives 3 skills/passives: Lightning Launcher, Powered Steps and Dampening Field. Lightning Launcher is similar to Which Bolt, but the extra cast doesn't cost an action, Powered Steps and Dampening Field are easy passive bonuses.
- [ ] Add Extra Attack at level 5
- [ ] Armor Modifications makes no sense in BG3, an easy rebalance could be to simply add 2 more Infusion Slots. Or we can scrap it and give Perfected Armor

### Artillerist 
- [ ] Implement Always Prepared spell progression up to level 9 (get from http://dnd5e.wikidot.com/artificer:artillerist)
- [ ] Implement Eldritch Cannon (easy way: conjure a cannon ranged weapon that gives skills equivalent to Flaming Hands, Eldritch Blast and False Life, hard way: make a pet that looks like a cannon)
- [ ] Implement Arcane Firearm (similar to Pact Weapon, gives 1 extra d8 damage to spells passive)
- [ ] Implement Explosive Cannon (better version of whatever we used as Eldritch Cannon)
