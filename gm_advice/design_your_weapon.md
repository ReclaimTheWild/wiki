---
layout: default
title: Design Your Weapon
summary:
permalink: /gm_advice/design_your_weapon
parent: GM Advice
tags:
    - gm-advice
    - design-notes
    - weapon
    - official-article
contributors:
    - milly
---

Originally posted on the official website on [July 1st, 2020](https://reclaimthewild.net/index.php/2020/07/01/design-your-weapon/)

# Design Your Weapon {% include labels/v2-01 %}
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

As part of the 2.00 update, we primarily focused on bringing poorer-performing weapons up to the par of the best weapon types, and re-evaluating how useful some weapon attributes were. We also codified weapon behaviors to make them more easily transferable to new weapon types. In fact, one of the goals of our weapon rebalancing efforts was to make it easier overall for you to make whole new types of homebrewed weapons!

A word of warning: the system below is our best estimate on what would be balanced. They assume that the value of Accuracy, Attack, and Durability is about the same, despite many factors such as Rank-based Attack and Durability scaling, player builds, individual situations, or popularity of equipment.

## The System

In this section, the weapon design system will be presented. In the last section, explanations will be offered for why the numbers are what they are.

Weapons are balanced around points. Points are assigned based on how much better or worse a weapon’s qualities are from the baseline.

### Formula

The following formula is the primary engine for all the guidelines that come after this. The point value of “type & hands” is explained in the next chart, while the point value of Keywords are explained in the chart after that.

Type & Hands point value + Keywords point value + Accuracy (minimum 1) + Attack modifier + Durability modifier = 8

| TYPE & HANDS | KEYWORDS GRANTED | POINT VALUE |
|--------------|------------------|-------------|
| 1H Arcane    | Wizardly         | 5           |
| 2H Arcane    | Wizardly         | 4           |
| 1H Melee     |                  | 5           |
| 2H Melee     | Sweeping         | 3           |
| 1H Ranged    |                  | 4           |
| 2H Ranged    |                  | 3           |

Only add the cost of Sweeping and Wizardly below if the keyword is *not* granted by the weapon type and handedness.

| KEYWORD                                                              | POINT VALUE (CONDITION)                                                                                   |
|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Defensive                                                            | 2 (on a weapon with Parry)<br>3 (on a weapon without Parry)                                               |
| [Explosive]({{ "/races/bob-omb" | absolute_url }})                   | 2                                                                                                         |
| [Expressive]({{ "/items/expand_armory/expressive" | absolute_url }}) | 1                                                                                                         |
| [Extending]({{ "/items/expand_armory/extending" | absolute_url }})   | 1 (with a melee basic attack like Punch, Stab, or Strike)<br>2 (without a melee basic attack)             |
| Hands-Free                                                           | 1 (with access to Strike)<br>2 (without access to Strike)                                                 |
| Long                                                         | 1 (with a melee basic attack like Punch, Strike or Whipcrack)<br>2 (without a melee basic attack)                 |
| [Messy]({{ "/races/inkling" | absolute_url }})                       | 1                                                                                                         |
| Returning                                                            | 1                                                                                                         |
| [Summoning]({{ "/items/expand_armory/hw_beyond" | absolute_url }})   | 2                                                                                                         |
| Sweeping                                                   | 0 (with 2H Melee weapons)<br>1 (with a melee basic attack like Strike or Punch)<br>3 (without a melee basic attack) |
| Wizardly                                                             | 0 (with Arcane weapons)<br>1 (with non-Arcane weapons)                                                    |

After adding up the values of keywords, and the type & hands, you must add at least 1 Accuracy, and may provide any modifier to Attack and Durability, as long as the final result is 8 points.

### ines

Accuracy should be between 2 and 5. 2 is the recommended minimum because a weapon with 1 Accuracy is a possibly frustrating and inaccurate weapon, and to ensure that using an Accuracy-reducing Crafting Style actually imposes a penalty.

Attack should be between -2 and +3.

Durability should be between -3 and +3.

Basic attacks should not be changed by weapons or keywords. Instead, leave the changes for Styles, or make up your own keyword that grants a new basic attack.

Defensive and Summoning weapons should likely not have positive Durability, as their main benefits bypass the need for Accuracy and Attack. The one exception is two-handed Defensive weapons, as presumably they are still going to be used for attacking.

Generally speaking, Weapons should have only one Edge type when crafted. A Weapon having one, two, three, or even more Edge types before crafting does not affect its budget at all.

As always, one’s own judgment and experience should also be used when designing weapons – as well as your GM’s permission, if you are a player.

Although you can add or subtract individual elements from a weapon type (such as removing Sweeping or Wizardly, adding Strike or Shoot Arrow), this is generally not recommended. All weapons of a particular type (Arcane, Melee, Ranged) should have particular base functions that allow them to be roughly on par with each other.

If you wish to use a weapon in an unconventional way (such as having a weapon that is a combination of two or three categories), the [feats from the Hyrule Warriors article]({{ "/items/expand_armory/hw_beyond" | absolute_url }}) may be preferable, as they require the spending of tokens rather than using up the weapon budget to get a more versatile, yet weaker, weapon.

However, here are the values if you want to have weapons that fit into multiple types:

| TYPE & HANDS              | KEYWORDS GRANTED   | POINT VALUE |
|---------------------------|--------------------|-------------|
| 1H Arcane & Melee         | Wizardly           | 7           |
| 1H Arcane & Ranged        | Wizardly           | 6           |
| 1H Melee & Ranged         |                    | 6           |
| 2H Arcane & Melee         | Sweeping, Wizardly | 7           |
| 2H Arcane & Ranged        | Wizardly           | 5           |
| 2H Melee & Ranged         | Sweeping           | 6           |
| 1H Arcane, Melee & Ranged | Wizardly           | 8           |
| 2H Arcane, Melee & Ranged | Sweeping, Wizardly | 8           |

Explanations for all values will be placed at the end of the document.

Keywords should mainly add a Weapon-related quality, conditional number boost, or access to new Basic Attacks. Any utility-related benefits – such as letting Long weapons be used for increasing the height of your jumps – should be separate Feats that are attached to a particular Keyword.

Esoteric or conditional effects might even be better off as Enchantments or bespoke Magical Tools.

-------------------

## Examples

Let's take some existing weapons as examples:

| BOW               | POINT VALUE |
|-------------------|-------------|
| 2H Ranged         | 3           |
| Keywords (None)   | 0           |
| Accuracy          | 4           |
| Attack            | 0           |
| Durability        | 1           |
| Total             | 8           |

| RING                            | POINT VALUE |
|---------------------------------|-------------|
| 1H Arcane                       | 5           |
| Keywords (Hands-Free, Wizardly) | 2           |
| Accuracy                        | 5           |
| Attack                          | -2          |
| Durability                      | -2          |
| Total                           | 8           |

| SWORD             | POINT VALUE |
|-------------------|-------------|
| 1H Melee          | 5           |
| Keywords (None)   | 0           |
| Accuracy          | 3           |
| Attack            | 0           |
| Durability        | 0           |
| Total             | 8           |

## New Weapons

This system is intended to be used for homebrewing new Weapons, so here are some new ones!

| Weapon         | ACC | ATK | DUR | Edge  | Hands | Type            | Keywords                                          |
|----------------|-----|-----|-----|-------|-------|-----------------|---------------------------------------------------|
| Gauntlet       | 5   | -2  | -3  | Any   | 1     | Melee           | Defensive, Hands-Free                             |
| Long Gunblade  | 2   | +1  | -1  | Sharp | 2     | Melee & Ranged  | Sweeping                                          |
| Relic Cannon   | 2   | +3  | -2  | Blunt | 2     | Arcane & Ranged | Wizardly                                          |
| Scyte          | 2   | +1  | -2  | Sharp | 2     | Arcane & Melee  | Sweeping, Wizardly                                |
| Short Gunblade | 3   | +0  | -1  | Sharp | 1     | Melee & Ranged  |                                                   |
{: .small-numbers-table}

Here are break downs of the various weapons:

| GAUNTLET                         | POINT VALUE |
|----------------------------------|-------------|
| 1H Melee                         | 5           |
| Keywords (Defensive, Hands-Free) | 3           |
| Accuracy                         | 5           |
| Attack                           | -2          |
| Durability                       | -3          |
| Total                            | 8           |

| SHORT GUNBLADE                   | POINT VALUE |
|----------------------------------|-------------|
| 1H Melee & Ranged                | 6           |
| Keywords (None)                  | 0           |
| Accuracy                         | 3           |
| Attack                           | 0           |
| Durability                       | -1          |
| Total                            | 8           |

| LONG GUNBLADE                    | POINT VALUE |
|----------------------------------|-------------|
| 2H Melee & Ranged                | 6           |
| Keywords (Sweeping)              | 0           |
| Accuracy                         | 2           |
| Attack                           | 1           |
| Durability                       | -1          |
| Total                            | 8           |

| SCYTHE                           | POINT VALUE |
|----------------------------------|-------------|
| 2H Arcane & Melee                | 7           |
| Keywords (Sweeping, Wizardly)    | 0           |
| Accuracy                         | 2           |
| Attack                           | 1           |
| Durability                       | -2          |
| Total                            | 8           |

| RELIC CANNON                     | POINT VALUE |
|----------------------------------|-------------|
| 2H Arcane & Ranged               | 5           |
| Keywords (Wizardly)              | 0           |
| Accuracy                         | 2           |
| Attack                           | 3           |
| Durability                       | -2          |
| Total                            | 8           |

And here is an example of a weapon that probably *shouldn’t* be created or used, despite technically matching most of the criteria of this system:

| Weapon     | ACC | ATK | DUR | Edge | Hands | Type                   | Keywords                                                                         |
|------------|-----|-----|-----|------|-------|------------------------|----------------------------------------------------------------------------------|
| Omni-Glove | 1   | -5  | -5  | Any  | 1     | Arcane, Melee & Ranged | Defensive, Extending, Hands-Free, Long, Returning, Summoning, Sweeping, Wizardly |
{: .small-numbers-table}

Here is the point break-down:

| OMNI-GLOVE                                                                                  | POINT VALUE |
|---------------------------------------------------------------------------------------------|-------------|
| 1H Arcane, Melee & Ranged                                                                   | 8           |
| Keywords (Defensive, Extending, Hands-Free, Long, Returning, Summoning, Sweeping, Wizardly) | 9           |
| Accuracy                                                                                    | 1           |
| Attack                                                                                      | -5          |
| Durability                                                                                  | -5          |
| Total                                                                                       | 8           |

This weapon isn’t a very good weapon because it breaks the guidelines for minimum Accuracy, Attack, and Durability, and so it is unlikely to be used for actually attacking. This means that most of the keywords (Extending, Long, Returning, Sweeping) are either going to be hampered by the poor modifiers, ignored in combat favor of their utility, or are useless.

With the Defensive keyword, the weapon at least provides access to the Deflect basic reaction, even if the Durability penalty will make it an expensive proposition. The Summoning and Wizardly keywords provide the obvious way to bypass most of the poor stats: by using those keywords to summon up an ally to do your fighting for you. However, the Durability penalty makes it slightly more expensive than the Summoning Gate, though with the added benefit of Defensive, and the utility of the other keywords.

## Explanation

Anything in this section should not be combined with the system as it is described in the first section. The point costs for the weapon types & handedness are broken down in this section, so adding, say, “1H Melee weapon”, “Strike”, “Parry”, and “Throw Weapon” together will result in much higher points than what they are really worth.

Generally speaking, the design philosophy for weapons is mostly based upon setting a baseline (worth 0 points) and then granting costs for what goes above that baseline in some way.

Above the baseline is mostly in terms of:

* 1 point for each target above the baseline (1)
* 1 point for every 2 squares in range above the baseline (melee 1, ranged 4)
* Cost of using the attack
* Conditional benefits

Let’s start with the two categories that define a weapon: handedness, and type (arcane, melee, ranged).

### Handedness

Handedness is simple: two-handed weapons are considered the baseline, because only carrying one weapon is the baseline compared to carrying two. If you attack with a greatsword, a staff, or a bow, you will only have that weapon to benefit from.

In contrast, you can hold a 1H weapon in one hand, which can lead to benefits such as holding a shield (to get a use of Deflect), or a different type of weapon (for attacking close and far), or using one hand to cling to a wall or a rope.

As such, 2H weapons start with 0 points, and 1H weapons start with 2.

Arcane, melee, and ranged weapons have different benefits, such as access to certain basic attacks and keywords by default.

### Defensive Basic Attacks

The main factor in defensive basic attacks is how many attack ranges they can be used against.

Parry is the baseline defensive basic attack, because it can only be used against Line, Melee, and Sweep attacks. In contract, Deflect can be used against any attack.

| BASIC ATTACK | FACTORS                        | POINT VALUE |
|--------------|--------------------------------|-------------|
| Deflect      | Unlimited applicability (3 pt) | 3           |
| Parry        | Limited applicability (1 pt)   | 1           |

Keyword connection: The Defensive keyword grants Deflect.

Deflect is worth 2 points for melee weapons because the 3rd point is achieved by removing Parry.

### Melee Basic Attacks

Melee basic attacks are those that have the benefit of attacking enemies in melee without suffering a penalty. The costs of melee basic attacks are based upon the number of possible targets, and the distance of the attacks from the user.

| BASIC ATTACK  | FACTORS                                           | POINT VALUE |
|---------------|---------------------------------------------------|-------------|
| Painful Touch | Distance: 1 square (0 pt)<br>Targets: 1 (1 pt)    | 1           |
| Punch         | Distance: 1 square (0 pt)<br>Targets: 1 (1 pt)    | 1           |
| Stab          | Distance: 2 squares (0.5 pt)<br>Targets: 2 (2 pt) | 2           |
| Strike        | Distance: 1 square (0 pt)<br>Targets: 1 (1 pt)    | 1           |
| Sweep         | Distance: 1 square (0 pt)<br>Targets: 2 (2 pt)    | 2           |
| Whipcrack     | Distance: 3 squares (1 pt)<br>Targets: 1 (1pt)    | 2           |

Keyword connection:

* Extending grants Whipcrack.
* Hands-free grants Painful Touch and Punch.
* Long grants Stab.
* Sweeping grants Sweep.

As you may notice, though Stab is technically worth 2.5 pts, it is rounded down to 2 because the differences between Line 2 and Sweep 2 are not sufficient to be worth 1 point.

If a weapon has access to one melee basic attack, the benefits of the other melee basic attacks are diminished. As such, if a weapon has access to *any* melee basic attack, the value of other attacks (such as Painful Touch, Punch, Stab, Sweeping, and Whipcrack) are decreased by 1.

For example, if a Ranged weapon had the Stab and Sweeping keywords, those keywords would cost 3 points total (2 for Stab, 1 for Sweeping).

Hands-Free weapons are worth 2 points with Arcane and Ranged weapons, due to the benefits that Painful Touch and Punch provide. This is in contrast to Melee weapons, which only derive a slight benefit from Painful Touch (use of Willpower with a melee basic attack instead of Combat) and thus only gains 1 point of value from the Hands-Free keyword.

Charge is not taken into account. This is because it is a basic attack with certain benefits and drawbacks, so it may be roughly considered as worth less than 1 point, and thus subsumed under the benefits of Strike.

Sneak Attack is baseline for all weapon types, so it is worth 0 points.

### Ranged Basic Attacks

Ranged basic attacks have two factors in their cost: their range and their cost.

4 squares are the baseline range, used for Throw Weapon (2H). Every 2 squares above that is worth 1 point.

The baseline cost is the weapon itself. Though the weapon can potentially be retrievable, you will still have one less weapon in that battle unless you give up the non-damage main benefits of making a ranged attack (distance from enemy, not dealing with terrain).

Compared to losing a weapon, ammunition is a step up even though you must spend more Rupees and/or Materials to power your basic attacks. In addition, ammunition provides flexibility in damage type and other benefits. So in the end, ammunition is considered to be worth 1 point.

No cost certainly costs a lot less compared to ammunition, but unfortunately also loses a lot of the flexibility provided by the special ammunition types. So it too is worth 1 point.

As such, costs for ranged basic attacks are as follows:

| BASIC ATTACK      | FACTORS                                                         | POINT VALUE |
|-------------------|-----------------------------------------------------------------|-------------|
| Magic Salvo (1H)  | Cost: None (1 pt)<br>Range: 6 (1 pt)                            | 2           |
| Magic Salvo (2H)  | Cost: None (1 pt)<br>Range: 8 (1 pt)                            | 3           |
| Dross Toss        | Cost: None (1 pt)<br>Damaged: Limited (-2pt)<br>Range: 6 (1 pt) | 0           |
| Shoot Arrow (1H)  | Cost: Ammo (1 pt)<br>Range: 6 (1 pt)                            | 2           |
| Shoot Arrow (2H)  | Cost: Ammo (1 pt)<br>Range: 8 (2 pt)                            | 3           |
| Throw Weapon (1H) | Cost: Weapon (0 pt)<br>Range: 6 (1 pt)                          | 1           |
| Throw Weapon (2H) | Cost: Weapon (0 pt)<br>Range: 4 (0 pt)                          | 0           |

Keyword connection:

* Hands-Free grants Dross Toss.
* The Returning keyword removes the cost of Throw Weapon.

For Arcane and Ranged weapons, which have access to both Throw Weapon and their categorically exclusive basic attack, the better of the basic attacks’ costs are taken. This is mostly because, with few exceptions, few would actually want to use Throw Weapon instead of Magic Salvo, Shoot Arrow, or… just switch out to a different weapon.

Although Dross Toss’s limited damage indicates that it should be the baseline… The reality is that the damage makes Dross Toss a very niche attack, and so Dross Toss is worth 0 points.

Sneak Attack is baseline for all weapon types, so it is worth 0 points.

### Keywords

Keywords are a catch-all term for aspects of weapon design that can be applied to more than one category of weapon. Their costs are detailed near the beginning of this article.

If a keyword provides access to a basic attack, see the sections above for an explanation of their point value.

Any changes to Combat Maneuver ranges by Keywords is not taken into account in the point value. This is because on a general basis no Combat Maneuver effect is as potent as the Helpless or Dead condition caused by damage.

Defensive grants a bonus when using the Defend action, but it is relatively minor compared to the benefits of Deflect.

Explosive grants the use of a reusable mini-bomb linked to a weapon. It has been given a value of 2 points because it’s more significant than most 1 point value keywords.

Expressive grants a scaling bonus to Social Maneuvers for a value of 1 point.

The Hands-Free keyword provides various benefits, some of which are more niche than others, that add up to roughly 1 point. Here is a partial list:

* The scaling bonus to Combat Maneuvers are as useful as Combat Maneuvers tend to be.
* The user can grab an item from their pack and use it in the same turn without keeping their weapon sheathed.
* The user can climb a wall and use a 2H weapon, or two 1H weapons, and can continue moving after attacking.
* The user can use a weapon while grappling with someone the same size as them.

Messy provides a scaling bonus to damage, but it applies on a 1/turn basis that benefits the next person to attack. So it is worth approximately 1 point.

Summoning provides a flexibility to your summoning spell, by automatically applying both the weapon style and the enchantment on your weapon to your summon’s weapon. Although weapon styles are roughly equivalent to each other, this is still a benefit that can provide extra damage, accuracy, or miscellaneous benefits to a potentially powerful summon, in a manner more convenient than handing the summon a weapon from your belt. So each benefit is worth approximately 1 point each, thus leading to Summoning’s total value of 2 points.

Wizardly is worth 1 point, so that Arcane weapons are slightly behind Melee and Ranged weapons with basic attacks, but are on par (or ahead) when casting spells.

### Weapon Types

Weapon Types provides access to basic attacks and certain keywords. Here is the break down for their point values, based upon what was explained up above:

| TYPE      | HANDEDNESS | DEFENSIVE    | MELEE         | RANGED                 | KEYWORD         | TOTAL |
|-----------|------------|--------------|---------------|------------------------|-----------------|-------|
| 1H Arcane | (2 pt)     |              |               | Magic Salvo 1H (2 pt)  | Wizardly (1 pt) | 5     |
| 2H Arcane | (0 pt)     |              |               | Magic Salvo 2H (3 pt)  | Wizardly (1 pt) | 4     |
| 1H Melee  | (2 pt)     | Parry (1 pt) | Strike (1 pt) | Throw Weapon 1H (1 pt) |                 | 5     |
| 2H Melee  | (0 pt)     | Parry (1 pt) | Strike (1 pt) | Throw Weapon 2H (0 pt) | Sweeping (1 pt) | 3     |
| 1H Ranged | (2 pt)     |              |               | Shoot Arrow 1H (2 pt)  |                 | 4     |
| 2H Ranged | (0 pt)     |              |               | Shoot Arrow 2H (3 pt)  |                 | 3     |
{: .small-numbers-table}

This system does not take into account how good Spells or Techniques that require a certain type of weapon can be. This is because the weapons are balanced around the possibility of a person only using the Basic Attacks available to them. In addition, Spells and Techniques are numerous, variable, and have their own boons and drawbacks built in, so the general thought is to consider them all approximately equal as far as Weapon Types go. Finally, tokens are normally required to buy Spells and Techniques, so the benefits do not “count” toward the weapon budget.

For weapon type combinations, the costs are placed together with the following modifications:

* Handedness cost only applies once.
* Throw Weapon’s costs are removed, due to its inferiority compared to Magic Salvo and Shoot Arrow.
* Magic Salvo and Shoot Arrow’s ranged benefits overlap, so the cost of the range of the second ranged attack is removed.

## Changelog

28 July 2020:
* The “[Explosive]({{ "/races/bob-omb" | absolute_url }})” weapon property has been added.

10 October 2020 :
* The “[Expressive]({{ "/items/expand_armory/expressive" | absolute_url }})” weapon property has been added.

17 February 2021 :
* Some text has been changed for grammatical purposes. The main formula has been changed to refer to Attack and Durability modifiers. Added in an explanation for the “Explosive” and “Expressive” keyword values.