---
{"dg-publish":true,"permalink":"/cairn/witchcairn/core-rules/"}
---


This is a custom ruleset with elements taken from the following 'Marked by the Odd' systems:
- Cairn, by Yochai Gal
- Mythic Bastionland, by Chris McDowall
- Mausritter, by Isaac Williams

# What's on the Character Sheet
### Attributes
There are three attributes: **Vigour** (VIG), **Clarity** (CLA), and **Spirit** (SPI).
- Vigour encompasses your physical strength, fortitude, and stamina. If you take physical damage, it lowers your Vigour.
- Clarity encompasses your agility, quick-thinking, and keen instincts. If you are met with disorienting attacks or mind-muddling situations, it lowers your Clarity.
- Spirit encompasses your willpower, hope, and heart. If you are demoralized, intimidated, or otherwise disheartened, it lowers your Spirit.

Each attribute is ranked between 3 and 18, and you determine your starting score by rolling 3d6.
Whenever you perform a risky action, you roll a Save with the appropriate attribute. Your attributes can also decrease during play, lowering your chance of successful Saves and thereby increasing the risks you take with your actions. When an attribute reaches 0, you are either dead (VIG), unable to react to the world around you (CLA), or utterly hopeless (SPI).

### Guard
**Guard** (GD) represents your ability and capacity to avoid actual harm. When you are attacked - either physically, magically, or mentally - and you are in a position where you could defend yourself, damage gets taken off your Guard before it lowers the appropriate Attribute. If the damage is fully absorbed by your Guard, you've not taken any actual wounds: you've managed to protect yourself against it.

You determine your max GD by rolling 1d6. GD is recovered quickly: resting for a short time restores it back to full.

### Inventory
Your Inventory is a key aspect of the game. The items you carry define the actions you can take. Everyone has 10 Inventory Slots. 1 Slot for each hand, 2 Slots on your body, and 6 Slots in a pack. Items in At Hand or on your Body are readily available for use, items in your Pack require time to recover in stressful situations.

You can carry a reasonable number of items beyond your Inventory Slots, but you become **Exposed** if you do so.

Items come in 3 varieties:
- **Normal** items occupy 1 slot. Some items have a restricted amount of uses before they're spent, for example a Torch can be lit 3 times before it expires.
- **Bulky** items occupy 2 slots
- **Petty** items occupy no slots, but a bunch of them can be bundled to occupy 1 slot. For example: 3 uses of Rations occupies one slot.

### Strain
Certain aspects of the game can cause your to take **Strain**. Strain is a condition that takes up 1 Inventory Slot. You can't use that Slot for carrying items, and if you have to take Strain when you're at full Inventory, you either become **Exposed** or you have to drop an item.

Strain stacks, occupying one Slot for each instance. You remove one instance of Strain after a night's rest.


### Armor
Armor represents physical gear that blocks damage from incoming attacks. When you get attacked with a physical attack, you deduct your Armor score from the damage before applying it to your GD.

Armor from Shields only functions if the Shield is worn in an At Hand slot.
Armor from helmets or body armor only functions if it is worn on a Body slot.


---
# The Rules of the Game
The rules of the game are straightforward. The GM describes the environment and your situation, and the player characters react to it. Characters can do anything they can be reasonably assumed to be capable of, keeping in mind their background and prior achievements. There are no rolls to see if you can do an activity, only rolls to avoid harm when you do risky things.

There are no Knowledge- or Perception-type rolls. The GM gives any information a character would likely know/see with regards to their background or situation. Neither are there Persuasion-type rolls: you interact with an NPC as you would with a normal person, and they react according to their personality/motivations/beliefs.

### Taking Action
Whenever you want to take an action, you - and the GM - should keep in mind the following list:
1. **Intent** - What is it you are trying to achieve?
2. **Leverage** - What do you have, or what can you do, that makes this possibe?
3. **Cost** - Is there a cost to your action, either in resource, personal harm, or unwanted side-effects?
4. **Risk** - What's at risk with this action? If there is no risk, there is no roll.
5. **Impact** - The consequences of the action, honoring the intent, cost, and risks.

This sequence of events can be shorted to **ILCRI**. You can easily remember this with the following mnemonic: 'Intent, Leverage, Cost, Risk, Impact.'

### Saves
The main roll in the game is the Save. You don't make a Save to see if you can do something, you make a Save **to avoid risk or harm** when you do something. If you take an action that doesn't have any risk involved, you don't need to roll a Save - you can just do it. Saves are made with one of the three attributes: VIG, CLA, or SPI.

If you have to roll a Save, you roll a d20 and compare the result to the relevant attribute. If the result is equal to or lower than your attribute, you succeed. If it's greater than your attribute, you fail.

If it's unclear if an action is risky enough to warrant a Save, the GM can check three factors: **Time**, **Gear**, and **Skill**.

- The factor of Time checks whether there is anything that requires you to succeed quickly. If you are unhurried and can take as long as you need to get ready, you have Time.
- The factor of Gear checks whether you have the items - if any - or circumstances required to perform your task. Climbing a wall might require a rope, but a sufficiently rough and cracked wall with enough handholds might also check the box.
- The factor of Skill checks whether your character would be the kind of person who would be able to do the thing you want to do. A meek wizard might be hard pressed to climb a steep wall, but a deft rogue might not.

After checking these factors, the GM decides:
- If you have zero or one, you can't do it
- If you have all three, you can do it
- If you have two, you can probably do it but you need to roll a Save to avoid a negative outcome

If two sides are in a contest, the individual that is **most at risk as a result of failure** has to make the Save.


### Conditions
There are three Conditions that influence your character's capacities:
- **Exposed**: You are Exposed if you are encumbered (carrying more items than you have slots for) or otherwise unable to defend yourself. While you are Exposed, your Guard is treated as 0 and you can't recover it when resting.
- **Strain**: Strain can be gained in various ways, such as failed Saves, strenuous activities, casting magic spells, or staying up too late. Each instance of Strain occupies one Inventory Slot. A full night's rest removes one instance of Strain.
- **Deprived**: You're Deprived if you haven't had sufficient food, drink, or rest for 24 hours. When you're Deprived, you can't recover your Guard in a short rest. If you are Deprived for more than 24 hours, you take one instance of Strain for every day you're Deprived thereafter. As soon as you cure the source of your deprivation, you lose the condition.

---
# Combat
Combat is fast and dangerous. Any good hit could wound you, and death is lurking around every corner. Choose your fights carefully!

### Distance and Range
Everyone's distance to each other in combat is expressed in relative terms.
- **Engaged**: At arm's length. You need to be Engaged with an opponent in order to make a Melee Attack against them. You can't make a Ranged Attack if you start your turn Engaged with an enemy.
- **Nearby**: Within movement's distance. 'Across the room.' You can make a Melee Attack against a Nearby target if your weapon has Reach.
- **Far Away**: More than a single movement away. 'Across the field.'
- **Distant**: So far away that you can't make out details. Ranged Attacks at Distant targets are Impaired.

Using your movement in your turn can shift your relative distance up or down one category (so from Nearby to Engaged for example, or from Far Away to Distant). Using your action for extra movement allows you to shift an additional step.

### Initiative
Combat rounds are around 10 seconds long, and every character on the same side takes their actions simultaneously. When it's your side's turn, everyone needs to declare what their character is going to do before any dice are rolled. After everyone has declared their actions, they all get resolved simultaneously.

If one of the sides surprises the other, they get a full round before the other side gets to act. If neither are surprised, follow this order:

1. Each player characters makes a CLA Save.
2. All characters who succeed on this Save get to act before the enemies.
3. Afterwards, the enemies will take their turn.
4. The first round ends, and the second one starts with all player characters taking their turn.

### Your Turn
Whenever you have your turn, you can declare movement and an action. You take your movement either before or after your action, you can't split it up around your action.
Switching At Hand and Body items doesn't count as an action and can be done freely.

Actions include:
- Making an attack and/or Gambit
- Aid an ally in their action
- Use an At Hand or Body item
- Switching an At Hand/Body item with a Pack item, or giving an item to an ally
- Moving further than you would normally be able to
- Flee
- Parley
- Anything else that would reasonably fit in this list

You can also specify holding a specific action until a specific trigger occurs in the enemy's turn. You need to specify your action and the trigger on which you will unleash that action. You can't hold your action if you have moved in your turn.

### Attacking
There are no separate to-hit rolls. Each attack results in the roll of your attack die, and varying levels of effect on your target. When you declare an attack, you roll the attack die associated with the weapon you use. The number on the attack die gets deducted from the opponent's Guard and Vigour. If your attack didn't deplete your enemy's Guard, you didn't wound your enemy but you did lower its ability to defend itself.

Attack dice range from d4 for unarmed or Impaired attacks to d10 for big two-handed weapons.

Observe the following rules:
- You can't make a Ranged Attack if you start your turn *Engaged* with an opponent.
- Ranged Attacks made against targets that are *Distant* are Impaired.
- Ammunition is not tracked, unless otherwise specified.
- If more than one character attacks the same opponent, everyone rolls their attack dice. The single highest value is applied as damage to the opponent.
- If you attack with two weapons at the same time, you roll both your weapons' attack dice and keep the single highest value. For example:
	- You attack with two Light weapons. You roll a d6 two times and keep the highest value.
	- You attack with a spear and bash with your shield. You roll a d8 and a d4 and keep the highest value.

There are several modifiers that affect your attacks:
- **Impaired**: If you make an attack from a position of weakness or disadvantage, your attack is Impaired. You roll only a single d4 for this attack, regardless of the weapons you use. Ranged Attacks made against Distant enemies are Impaired, and attacks made with Reach weapons in confined spaces may also be Impaired.
- **Bonus Dice**: If a particular circumstance works in your benefit, you can get a bonus attack die on your attack. Usually this is *+d8*, which means you roll a d8 in addition to your normal attack dice and keep the single highest value. Depending on the circumstances, you might get to roll a bigger die for bonus damage. The **Frenzy** Feat can apply a *+d12* bonus die, for example.
- **Blast**: A Blast attack affects multiple targets close together. Roll the attack dice for each target separately. If it's unsure how many targets a Blast would affect, roll the relevant attack die to determine the number of targets.

### Gambits
Gambits are maneuvers you can make to apply a temporary effect on your target. After you've rolled your attack dice and before damage is applied, you can expend any die of 4 or higher to perform a Gambit. The affected target of the Gambit must be the target of the attack. Targets get to make a VIG Save to avoid the effect of a Gambit - with the exception of the Bolster and Move Gambit. If multiple characters perform a Gambit against the same opponent at the same time, they can't perform the same Gambit. Gambits can never do something that would outright end combat, they only give a temporary advantage.

If the die expended to perform a Gambit is an 8 or higher, the target doesn't get to make a Save, or the Gambit has a greater and/or longer lasting effect at the GM's discretion. 

The Gambits are:
- **Bolster**: Add +1 to the attack's total damage.
- **Move**: Move after your attack, even if you have already moved or are unable to move.
- **Repel**: Force an opponent away from you. 
- **Stop**: Prevent an opponent from moving on their next turn.
- **Impair**: Impair a weapon, or weaken an attacking power of an opponent on their next turn.
- **Expose**: Negate the opponent's sources of Armor for the round.
- **Dismount**: Dismount a mounted opponent.
- **Something else** that would reasonably fit in the above list.

### Feats
Every character can perform the following 3 Feats in combat. You can only apply one Feat per character per attack. After you perform a Feat, roll the appropriate Save. On a failed Save you can't perform anymore Feats until you've had a rest that recovered your Guard.

- **Frenzy**: You declare to Frenzy *when you declare your attack, before the dice have been rolled*. When you Frenzy, you choose to enhance your attack with either 
	- *+d12* bonus damage
	- the *Blast* property
	- or you leave a specific mark on your enemy. 
	After you've rolled your attack dice, you roll a VIG Save.
- **Focus**: You declare to Focus *after you've rolled your attack dice, but before damage is applied*. When you Focus, you can perform a Gambit against your opponent without expending an attack die. After you've performed your Gambit, you roll a CLA Save.
- **Deflect**: You declare to Deflect *when you or an ally at arm's length are hit with an attack*. When you Deflect, you can choose to discard one of the attacker's attack dice. After you've removed the die, you roll a SPI Save.


---
# Getting Hurt
When enemies attack you, follow this procedure:
- Consider the attack dice rolled by the opponents
- Choose whether you (or one of your ally's) wants to **Deflect**
- Deduct your Armor value from the damage.
- Apply the remaining to your Guard. 
	- If you have at least 1 GD remaining, you have evaded the attack.
	- If this brings your GD exactly to 0, you take a **Scar**.
	- If this exceeds your GD, any excess damage is applied to your Vigour
- If you take damage to your Vigour, immediately make a VIG Save using your new score. 
	- If you succeed you are **Wounded** but still in the game.
	- If you fail, you are **Mortally Wounded** - you're down and dying, and if untended to you die within the hour. An ally applying first aid to you can stabilize you and bring your from Mortally Wounded to simply Wounded.
- If damage reduces your Vigour to 0, you die. 

Note that GD only protects you from damage that you could *reasonably prevent*. Damage from other sources, such as falling from a great height or ingesting poison, is applied directly to your Vigour but does not per se trigger a VIG Save.


### Scars
When an attack in combat reduces your GD to exactly 0, you take a Scar. The amount of GD you lost in the attack that gave you the Scar determines the effect. Consult the table below.

| GD Lost | Effect                                                                                                                                                                                                                                                                                                               |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 GD    | **Lasting Scar**: Roll 1d6 to determine the location - 1: Neck, 2: Hands, 3: Eye, 4: Chest, 5: Legs, 6: Ear. Then, roll 1d6: if the result is higher than your max GD, take the new result.                                                                                                                          |
| 2 GD    | **Rattling Blow**: You’re disoriented and shaken. Describe how you refocus. Roll 1d6. If the total is higher than your max GD, take the new result.                                                                                                                                                                  |
| 3 GD    | **Walloped**: You’re sent flying and land flat on your face, winded. You are **Deprived** until you rest for a few hours. Then, roll 1d6. Add that amount to your max GD.                                                                                                                                            |
| 4 GD    | **Broken Limb**: Roll 1d6 to determine the bone - 1-2: Leg, 3-4: Arm, 5: Rib, 6: Skull. Once mended,roll 2d6. If the total is higher than your max GD, take the new result.                                                                                                                                          |
| 5 GD    | **Disease**: Your wound gets afflicted with a gross, uncomfortable infection. When you get over it, roll 2d6. If the total is higher than your max GD, take the new result.                                                                                                                                          |
| 6 GD    | **Reorienting Head Wound**: Roll 1d6 \| 1-2: VIG, 3-4: CLA, 5-6: SPI. Roll 3d6. If the total is higher than your current attribute, take the new result.                                                                                                                                                             |
| 7 GD    | **Hamstrung**: You can barely move until you get serious help and rest. After recovery, roll 3d6. If the total is higher than your max CLA, take the new result.                                                                                                                                                     |
| 8 GD    | **Deafened**: You cannot hear anything until you find extraordinary aid. Regardless, make a SPI save. If you pass, increase your max SPI by 1d4.                                                                                                                                                                     |
| 9 GD    | **Re-brained**: Some hidden part of your psyche is knocked loose. Roll 3d6. If the total is higher than your max SPI, take the new result.                                                                                                                                                                           |
| 10 GD   | **Sundered**: An appendage is torn off, crippled, or useless (the GM will tell you which.) Then make a SPI save. If you pass, increase your max SPI by 1d6.                                                                                                                                                          |
| 11 GD   | **Mortal Wound**: You are **Deprived** and out of action. You die in one hour unless healed. Upon recovery, roll 2d6. Take the new result as your max GD.                                                                                                                                                            |
| 12 GD   | **Doomed**: Death seemed ever so close, but somehow you survived. You are out of action until you've had a day to recover. Afterwards, your next VIG Save from a Wound determines your fate. If it is a fail, you die horribly. If you pass, roll 3d6. If the total is higher than your max GD, take the new result. |

### Recovering
To recover your GD, you need to rest for around 10 minutes and consume a Ration. Afterwards, your GD is fully recovered. If you failed a Save after performing a Feat earlier, you also regain the ability to perform Feats again.

Attribute Damage is recovered at one point per day's rest. If multiple attributes are damaged, choose which one to recover a point in each day.

All Attribute Damage is fully recovered after a full week's dedicated rest.


---
# The Armory
### Weapons
**Light Weapons** (*d6*): Weapons that are small and can be easily dual wielded or concealed
- Dagger, Club, Handaxe, etc
**Hefty Weapons** (*d8*): Weapons that require balance. They can be combined with a Shield or Light Weapon, but not with another Hefty weapon
- Swords, Spears, Mace, Axe, etc
**Big Weapons** (*d10, Bulky, Reach*): Weapons that require both hands to use. May be Impaired in confined spaces.
- Greatsword, Glaive, Halberd
**Ranged Weapons**:
- Sling (*d4*, *Light*), Javelin (*d6, Hefty*), Bow (*d6, Bulky*), Crossbow (*d8, Bulky*, must be reloaded after an attack)

### Armor
- **Shield**: +1 Armor, At Hand slot, can be used to Shield Bash for d4, but you lose the Armor value until your next turn.
- **Helmet**: +1 Armor, Body slot
- **Gambeson**: +1 Armor, Body slot
- **Chain Shirt**: +1 Armor, Body slot, Bulky
- **Chain Mail**: +2 Armor, Body slot, Bulky


---
# Optional Reads
### Dungeon Exploration
When your character or group is crawling through a dungeon or dungeon-like environment, you go through Dungeon Cycles. One Dungeon Cycle takes around 10 minutes and consists of the following sequence of events:

1. The GM describes the environment and rehashes the current situation, giving any pertinent information that is immediately noticeable to the characters.
2. The players each declare which (one) action their characters will take during the cycle. Examples of common actions are:
    - Moving to a different area
    - Searching an area (particularly large locations might require you to state a specific area to search)
    - Keeping an eye out for dangers to avoid being surprised by anything unexpected
    - Overcome an obstacle in your way such as a locked door or blocking debris
3. Everyones' actions resolve simultaneously
4. The GM determines whether to Tick the **Voidclock**, and resolves any Events.
5. Any resources are checked against their duration, the GM's tools and tables are updated, and the Cycle repeats.

In dark environment, you need at least one Torch per three persons to see comfortable. A Torch usually lasts an hour (or: 6 Dungeon Cylces) and can be lit 3 times before being fully burned out. Certain events in the dungeon might cause your Torch to blow out sooner.

### The Event Die
Whenever it feels appropriate, the GM may roll the Event Die to see if something unexpected happens. The GM may roll the Event Die if the characters:
- Travel to a new location
- Traverse a sequence of previously explored locations
- Linger in a unsafe location
- Rest in an unsafe location
- Make a disturbance or cause a ruckus

Depending on the characters' actions, the Dungeon might become Alerted or Alarmed. When rolling the Event Die, the GM will instead roll 2 (Alerted) or 3 (Alarmed) and take the lowest result.


| Event Die | Effect                                                                                                                                                                                                                                             |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1         | Wandering Encounter. If more than one 1 is rolled, the party is surprised.                                                                                                                                                                         |
| 2         | Signs or Omens of a nearby danger or Encounter. If unresolved, the party will encounter it next Cycle.                                                                                                                                             |
| 3         | Altered Circumstances: something changes in the circumstances, indirectly hindering the party. The Environment may change in a meaningful way, the party may be confronted with a Choice going forward, or an unfortunate Setback may befall them. |
| 4-6       | Quiet.                                                                                                                                                                                                                                             |

### Wilderness Exploration



Etc:
- Magic = Runestones, 