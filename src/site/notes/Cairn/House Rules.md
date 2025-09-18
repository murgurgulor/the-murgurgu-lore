---
{"dg-publish":true,"permalink":"/cairn/house-rules/","tags":["TTRPG/Cairn/SRD"]}
---

The following house rules are in addition to the core mechanics of Cairn.

# Doing Things
In Cairn there are no strict rules as to resolving common activities. The following guidelines aid this process.
If something is simply impossible to do, or if there’s no reason why you should fail, no dice are rolled and the action succeeds or fails respectively. 

For actions that are in doubt, evaluate whether you have **Time**, **Gear**, and **Skill**.
- **Time** is an aspect of the in-game fiction. If there's nothing going on that prevents you from taking as long as you need to perform an action, you have Time.
- **Gear** is an aspect of your inventory. If you have the right tools and/or resources to perform your action, or if you're not Encumbered by your inventory's weight (whichever is most relevant), you have Gear.
- **Skill** is an aspect of your character. If your background, in-game experiences, or Attribute scores make it reasonable that you would be able to perform the action, you have Skill.

If you have one or none of these factors, your action fails. If you have all three of these factors, your action succeeds.
If you have two out of the three you can probably still do it, but you have to roll an appropriate Save to avoid an unwanted complication or cost.

---
# Boons and Banes
Cairn doesn't allow for beneficial or detrimental circumstances to modify your chances of succeeding on a Save. This adds the option.
- If you have to make a Save but you're in a position of advantage, you gain a **Boon** to your Save: roll an additional d20 and keep the lowest result.
- If you have to make a Save and you're in a position of disadvantage, you gain a **Bane** to your Save: roll an additional d20 and keep the highest result.

You can have multiple Boons or Banes. Each Boon cancels out a Bane, and you apply the net result to your Save.

---
# Combat
The following is an expansion and replacement of Cairn's combat system.

## Movement and Range
Distance is abstracted. The distance between one character and another is denoted by one of the following ranges:
- **Engaged**: At arm's length. You have to be *Engaged* with an opponent in order to make a melee attack against them. Ranged attacks you make while you're *Engaged* with an enemy are *Impaired*.
- **Nearby**: Within walking distance, across the room.
- **Far Away**: They're further away, requiring dedicated movement to reach.
- **Distant**: Very far away, you can't make out their details. Ranged attacks made at *Distant* targets are *Impaired*.
- If you move during your turn, you shift your range by up to one. If you take two movements in your turn, you can shift your range by up to two.

## The Order of a Round
Combat is measured in Rounds. Each Round lasts for roughly 10 seconds. At the start of the round, all the players declare whether they want to act on the Slow Turn or on the Fast Turn. 
The GM determines the actions for the opponents. If prompted by the players, the GM will telegraph the opponents' intent ("*The large viking grabs his axe and is eyeing up Player 1*").

### Initiative Turns
There are two Initiative Turns in which the actions resolve: a **Fast Turn** and a **Slow Turn**. All the actions in the Fast Turn resolve before moving on to the Slow Turn. After all the actions of the Slow Turn have resolved, the current round ends and a new round begins.

If you have chosen to act on the Fast Turn, you can perform one Fast Action.
If you have chosen to act on the Slow Turn, you can perform two Fast Actions, or one Slow Action.

#### Fast Actions
- Move
- Make a melee attack against an *Engaged* enemy
- Make a ranged attack
- Perform a Gambit
- Use an At Hand item
- Switch At Hand and Body items around
- Focus: Get a Boon on one Save you make after using a Feat this round
- Hold: Wait with declaring a Fast Action until the Fast Turn has resolved

#### Slow Actions
- Cast a Spell
- Switch an At Hand or Body item with a Bag item
- Flee
- Parley

### Order of Action Resolution
At the start of each of the Turns, the players who act on the turn make a DEX Save. Players who succeed on the DEX Save act before the opponents that act on the turn, and players who fail the DEX Save act after the opponents. If multiple players go at the same time, they can take their turns sequentially in an order they choose, or simultaneously.

Actions that occur on the same Initiative Turn resolve basically simultaneously. In circumstances where one action would influence another (for example, the Ogre you attacked might die before having a chance to get its own attack in), keep the following guidelines:
- If a character and an opponent start the turn *Engaged* and both attack, the attacks are resolved in order of weapon type: **Light** (d6) > **Balanced** (d8) > **Heavy** (d10) > **Reach** > **Ranged**.
- If a character and their opponent start the turn at any other distance and they both attack, the attacks are resolved in the reverse order: **Ranged** > **Reach** > **Heavy** (d10) > **Balanced** (d8) > **Light** (d6)
- If you are Dual Wielding two melee weapon of different types, you either only roll an attack with the fastest weapon on its count, or you roll for both weapons on the slowest weapon's count.
- If multiple characters attack the same opponent in the same Turn, all attacks get resolved on the count of the slowest participant.
- If you and an opponent take actions that would resolve at the same time, you go first if you pass a Dexterity Save.

## Attacks and Damage
There are no 'to-hit' rolls: all attacks hit automatically. Roll your weapon's attack die to see how much damage you deal. You subtract the opponent's Armor before applying the damage to their HP. Any excess is applied to their Strength Attribute.

If multiple characters attack the same opponent in the same Turn, roll all attack dice and keep the single highest one. The other participants get to choose whether they:
- Add +1 to the attack's damage, or 
- Use their roll to perform a **Gambit** instead.

**Dual Wielding**: If you attack with two weapons at the same time, roll both Attack dice and keep the highest result.


### Attack Modifiers
**Impaired**: An attack is *Impaired* if it's made from a position of weakness, such as through cover or when restrained. An *Impaired* attack will always only deal d4 damage.
**Enhanced**: An attack is *Enhanced* if it's made from a position of advantage (such as against a helpless enemy, or if you target a particular weakness). An *Enhanced* attack will always deal d12 damage.
**Blast**: A *Blast* attack affects multiple targets close together. If it's unsure how many targets it would affect, roll the attack dice to determine the amount.
**Bonus Damage**: If a particular circumstance gives you bonus damage on an attack, this is denoted as *+dx*, where *x* is the die size of the bonus. Roll the bonus die with your regular Attack dice, and keep the single highest result.
**Multiple Attacks**: If you make more than one attack in the same round, all attacks beyond the first are *Impaired*.
**Ranged Attacks**: Ranged attacks you make when you are *Engaged*, or that are aimed at a *Distant* target, are *Impaired*. Ammunition is not tracked unless otherwise specified.


### Wounds
Whenever someone's HP is reduced to 0, any excess damage is applied to Strength. When you take Strength Damage, you are *Wounded* and you have to make a Strength Save to stay in the fight.
On a successful Save, you keep standing. You have to make a new Save every time you take additional damage.
On a failed Save, you are *Mortally Wounded*. You can't do anything more than crawl and moan weakly. If you are given aid by an ally you stabilize, otherwise you die within the hour.

Unimportant enemies might be routed or fall unconscious as soon as they take Strength Damage.

## Feats
Feats are special maneuvers you can apply during combat. You can only use one Feat per attack. After performing a Feat, you must make a Save with the appropriate Attribute to avoid Fatigue.
- **Frenzy**: You declare you're making a Frenzied attack before rolling your Attack dice. Your Attack either gains *+d12* or *Blast*. Afterwards roll a STR Save.
- **Deflect**: You declare a Deflect before an opponent makes an Attack roll has been made against you or an ally within arm’s reach. The Attack is *Impaired*. Afterwards roll a DEX Save.
- **Follow-up**: You declare a Follow-up after you've rolled an Attack. You can perform a Gambit in addition to dealing damage, but the opponent gets a Save to resist. Afterwards roll a WIL Save.

## Gambits
After you roll your Attack dice, you can choose to use your roll to perform a **Gambit** instead of dealing damage. A Gambit is a maneuver such as stunning, shoving, disarming, disengaging, confusing, taunting, hobbling, breaking armour, et cetera. Describe what you do to the opponent and what your intended result is. The effect of your Gambit is up to the GM, and it lasts until the end of the target's next turn.

If the Attack roll used for the Gambit came up as a **1-3**, the opponent gets to make an appropriate Save to resist your Gambit. 
If the roll came up as **4 or higher** the opponent doesn’t get to make a Save.
If the roll you used for a Gambit came up as an **8 or higher**, you get a greater or longer lasting effect.


## Retreating
You can choose to tactically retreat from an encounter as a Slow Action. To make a Retreat, you need to have a safe location to retreat to, and succeed on a Dexterity Save.

## Detachments
Large groups of similar combatants fighting together are treated as a single Detachment. Attacks against Detachments by individuals are always *Impaired*, unless it's *Blast* damage. Attacks against individuals are always *Enhanced* and deal *Blast* damage.
When a Detachment has 0 HP, any excess damage is dealt to the Detachment's Strength or Will (attacker's choice to either **Decimate** or **Demoralize**) after which it must make a WIL Save. On a failed Save, the Detachment is routed and flees. When a Detachment's Strength is reduced to 0, it's utterly defeated.