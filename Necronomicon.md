<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Necronomicon](#necronomicon)
  - [The Basics](#the-basics)
    - [What stats affect Minions on the tree?](#what-stats-affect-minions-on-the-tree)
    - [How does support gems interact with minions?](#how-does-support-gems-interact-with-minions)
    - [How do I create Corpses?](#how-do-i-create-corpses)
    - [How do I target Corpses?](#how-do-i-target-corpses)
    - [How do I turn on minion life bars?](#how-do-i-turn-on-minion-life-bars)
    - [How do I heal my minions?](#how-do-i-heal-my-minions)
    - [Minion ToolTip](#minion-tooltip)
    - [Does Stats like Dex, Int, and Str affect minions?](#does-stats-like-dex-int-and-str-affect-minions)
    - [What are minions Resistances?](#what-are-minions-resistances)
    - [Can Minions Crit?](#can-minions-crit)
    - [Minion Accuracy?](#minion-accuracy)
  - [Passive Nodes](#passive-nodes)
    - [Minion Instability](#minion-instability)
    - [Necromantic Aegis](#necromantic-aegis)
    - [Conduit](#conduit)
    - [Elemental Equilibrium](#elemental-equilibrium)
  - [Ascendancy Notables](#ascendancy-notables)
    - [Commander of Darkness](#commander-of-darkness)
    - [Beacon of Corruption](#beacon-of-corruption)
    - [Mistress of Sacrifice](#mistress-of-sacrifice)
    - [Soul Weaver](#soul-weaver)
    - [Flesh Binder](#flesh-binder)
    - [Spirit Eater](#spirit-eater)
  - [Minion Mechanics](#minion-mechanics)
    - [Minions and Support Gem Swapping](#minions-and-support-gem-swapping)
    - [On Raise Spectre Zone level scaling](#on-raise-spectre-zone-level-scaling)
    - [Monster's and their AI and Mana use](#monsters-and-their-ai-and-mana-use)
    - [Minions and On-Kill effects](#minions-and-on-kill-effects)
    - [Frenzy, Power, Endurance Charges](#frenzy-power-endurance-charges)
    - [Soul Eater and Minions(Unending Hunger Jewel)](#soul-eater-and-minionsunending-hunger-jewel)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

[TOC]

# Necronomicon

---

## The Basics

---

### What stats affect Minions on the tree?

On the tree itself only the **nodes** that are labeled `minions  ` will effect minions. Period. There are special cases like SRS and Summon Skeletons where grabbing increased duration nodes will make them last longer since they are labeled with the "duration" tag.

---

### How does support gems interact with minions?

When it comes to support gem linking you will need to **observe what that minion does**. 

For example a zombie can be considered a melee toon who uses default attacks. Using a Multistrike gem will make him attack 3 times in quick succession. Using added fire gem will give him extra damage as fire. 

Raise Spectre is where things get more interesting. Take the flame sentinel for example. Upon observing its characteristic you come to realize that these guys has fork and lmp already "linked" to them. You then can surmise that any support links that work on the fireball skill gem will work on flame sentinels.

---

###  How do I create Corpses?

Use the **desecrate gem** and it will summon corpses of the base type of monsters u find in that zone. Keep in mind a level 20 Desecrate gem will allow you to create monsters of the highest base level for the zone you are in. The highest level zone as of [3.0.1] is level 84, the shaper zone.

<img src="https://i.gyazo.com/24a3834e4f04eb7136be7b3a9ce5943d.png" height="500">

---

### How do I target Corpses?

The default key is "A", you can change this in the hotkey settings. Hover over the corspe hold A, then u can raise spectre

---

### How do I turn on minion life bars?

Go to options -> Ui -> Allies health bar

---

### How do I heal my minions?

• You can roll "of animation" on your life flasks for 40-60% effect provided to them. This can be buffed by flask or life flask effectiveness stat
• Using the Convocation Gem gives them a small heal over time
• Using a Rejuvenation Totem
• Any instance of heal on block
• Minion life regen
• Minion Life leech and life leech support gem
• Severed in Sleep gain 20% maximum life on killing a poisoned enemy
• Vitality Aura
• If you are running the Immortalis Belt you can use any flasks that heals for zombies and spectres

---

### Minion ToolTip

For the most part the tooltip is **WRONG**. The Life values might be right but the dps values are definitely wrong. We can't rely on the tool tip to see how much damage our minions are doing you will need to calculate that manually unfortunately.

There is a 3rd party tool out there called Path of Building. 

https://github.com/Openarl/PathOfBuilding/releases

There you can select the minion you are using and can observe its dps and defense values.

---

### Does Stats like Dex, Int, and Str affect minions?

Minions have a starting Base attributes of 0. They can gain stats from necro aegis and uniques such as the baron unique helmet. Minions do gain the same stat scaling player does

**Int:**

-   Every 10 intelligence grants an additional 5 [mana](https://pathofexile.gamepedia.com/Mana).
-   Every 10 intelligence grants 2% increased maximum [energy shield](https://pathofexile.gamepedia.com/Energy_shield).

**Str:**

-   Every 10 strength grants an additional 5 maximum [life](https://pathofexile.gamepedia.com/Life).
-   Every 10 strength grants 2% increased melee [physical damage](https://pathofexile.gamepedia.com/Physical_damage).

**Dex:**

-   Every 10 dexterity grants an additional 20 [accuracy](https://pathofexile.gamepedia.com/Accuracy) rating.
-   Every 10 dexterity grants 2% increased [evasion](https://pathofexile.gamepedia.com/Evasion) rating.

---

### What are minions Resistances?

By Default most minions(AW, srs, skele, zombros, anything summoned like spectral wolves) now have 40% ele res and 20% chaos resistances . Spectre's will have +30% naturally giving them 70% all res. Golems have 70% by default from their respective elements while chaos/stone will have 40%.

This means with the necromancer ascendancy that give +20% all res and the 16% you get from the tree will cap any kind of minion to 75%(they all get 76%). You can run purity to cap in situations where they get cursed it also makes it a lot easier to overcap with the tri purity auras for all minions.
What this means is minions in general are much tankier now in all situations.

**Sources of Minion Elemental Resistances:**

-   Herd of the Flock +16% to all elemental resistances
-   Commander of Darkness +20% to all Elemental Resistances (aura radius)
-   Purity of Elements (aura radius)
-   Purity of Fire (aura radius)
-   Purity of Lightning (aura radius)
-   Purity of Ice (aura radius)
-   Sources of + minion elemental resistances on jewels (suffix)
-   Liege of the Primordial (Elementalist node that makes golems immune to elemental damage)
-   Necro Aegis and elemental resistance on shields

**Sources of Minion Chaos Resistances:**

-   Grave Intentions
-   Minion Life and Chaos Resistances
-   Necro Aegis and chaos resistance on shield

**Relevant patch notes:**
• Raise Spectre now grants +30% elemental resistances to its minions.
• Fire, Cold, and Lightning Golems now have 70% resistance to their respective element. Chaos Golems now have 60% resistance to Chaos.
• Totems and all other minions now have 40% elemental resistance and 20% chaos resistance. This also includes minions that didn't have resistances previously, like wolves

---

### Can Minions Crit?

Most minions will have a base crit chance of 5% with a 130% crit multiplier. Certain monsters raised with raise spectre may have more then the base. Other minion types may range from 5-7% base crit chance.

---

### Minion Accuracy?

Although minions base accuracy is mostly unknown. They should follow the same rules as players do. Spell hits 100% of the time. And attacks are based off of an unknown base accuracy value. It could be minions follows the same accuracy formula that players use. Is it to be noted that attack based minions do have accuracy. 

If there is a level difference between the monster and your minions they will either have reduced accuracy against monsters with higher level(b/c they have more evasion) and your minions will have increased accuracy against monsters with lower level(b/c their accuracy value will be greater then the impact of the mob's evasion)

At higher levels of content accuracy becomes a larger factor, getting your SRS to levels above gem level 20 is important. Better yet if your build can incorporate a [Lycosidae](https://pathofexile.gamepedia.com/Lycosidae) with Necromantic Aegis. It can result in a 50% increase in dps. Do not underestimate the importance of accuracy.

---

## Passive Nodes

---

### Minion Instability

<img src="https://i.gyazo.com/640eb1d7b3a05692312130bdd7bcfd5d.png" height="300"/>

Low life means when minions fall below 35% life. With this node they will explode for 33% of their maximum life as fire damage. And yes this damage is boosted by your minion damage stat and related support gems linked to said minion who blew up. The general consensuses by most veteran summoners and myself included is that this is a terrible keystone. You effectively cut your minion life pool by 35% with a small explosion in return. Your minions will do way more damage alive. However you can build a niche spec around this notable.

http://pathofexile.gamepedia.com/Minion_Instability

---

### Necromantic Aegis

<img src="https://i.gyazo.com/7f855082e3d41e61be0203bed97524f1.png" height="300" />

This makes it so ALL of your shield stats. Yes, every stat listed. Will affect your minions and your own character will no longer gain those stats. They will also gain the unique mechanics from the shields as well. A good example is the Victario's Charity it will grant minions the ability to generate their own charges something they cannot do by default.

http://pathofexile.gamepedia.com/Necromantic_Aegis

---

### Conduit

<img src="https://i.gyazo.com/59f6a4fea7af072b183bd679188e9df9.png" height="300"/>

Minions count as "allies" This is a very important key term. "Allies" are NOT "Party members" this means anything that says it effects party members will not effect allies. So conduit does not work. You will need to supply charges in other ways, for example warlords mark, assassin mark, poacher's mark, Frenzy Gorilla spectre, and Victario's Charity on Necromantic Aegis.

http://pathofexile.gamepedia.com/Conduit

---

### Elemental Equilibrium

<img src="https://i.gyazo.com/158d213d1e8e2eebbf3ab965cbd3bc34.png" height="300" />

You see this keystone picked up a lot in Summoner builds. Normally referred to as "EE" any elemental damage type your character deals will +25% that element and -50% the resistances of the other two elements. Your minions will not trigger EE themselves which makes it a free dmg boost for elemental dmg minions.

http://pathofexile.gamepedia.com/Elemental_Equilibrium

---

## Ascendancy Notables

<img src="https://i.gyazo.com/09d035395f50a044b30024914e388ca1.png" />

---

### Commander of Darkness

<img src="https://i.gyazo.com/2c5441b9f9ddb7ca2c1383d2aa3df6bc.png" height="300" />

This ascendancy node grants 20% resistances for any allies affected by your auras including yourself. A 30% increased Damage, and each aura granting cast and attack speed to your allies. A great point to pick up for the extra resistances.

http://pathofexile.gamepedia.com/Commander_of_Darkness

---

### Beacon of Corruption

<img src="https://i.gyazo.com/106001334e0e7f76099542138d37ad52.png" height="300"/>

Beacon of corruption leaves a cloud of poison much like caustic arrow. It triggers either on minion death or minion timeout or summoning the minion over your current cap. It has the tags of AOE, Duration, Chaos, Minion.



---

### Mistress of Sacrifice

<img src="https://i.gyazo.com/e088bbc2f766ac725d6e81d2db5c6c86.png" height="200" />

Mistress of Sacrifice allows you to use minion specific active buffs on your own character. Giving you stats that are hard to find else where like movement speed, block, physical to chaos, ect

---

### Soul Weaver

<img src="https://i.gyazo.com/f73363ceb99910163bf45486098cbd41.png" height="250" />

A noticeable power booster for Spectre builds. This is a extremely large damage booster as sources of minion damage is not as easy to obtain compared to other damage types. The Life boost effectively makes spectre immune to death in most situations.

---

### Flesh Binder

<img src="https://i.gyazo.com/94f1e0bcbaaa78050203b89e9b4a93ff.png" height="225" />

As far as Ascendancy nodes go this is pretty lack luster but typically a summoner build will have very little physical mitigation any bit helps.

---

### Spirit Eater

<img src="https://i.gyazo.com/76b8428ef0fc33725329863deb9c0c98.png" height="300" />

This ascendancy node is typically picked up for non-summons focused build but someone who still wants to utilize the Necromancer ascendancy.

---

## Minion Mechanics

---

### Minions and Support Gem Swapping

Minions will gain the effects of the support gem while it is summoned. So you can swap out support gems in and out on the fly. 

A tip for people low on mana is to take out support gems and summon minions with a lower mana cost then re-equip the gem. 

Same goes for Spell Echo. If you don't want the first part of the skill to echo(The summoning of the spectre itself for example) you can remove it then reequip it later. After re-equipping the spell echo it will be "added" to the currently raised spectres much like how **any other active skill works**.

---

### On Raise Spectre Zone level scaling

When you use Raise Spectre on a corpse. The monster summoned will be equal to the level of that zone. If you raise a level 50 monster it will be a level 50 monster. Spectre's will zone down but NOT up. What I mean by this is if you take that level 50 monster and bring it to a level 1 zone it will be level 1. However, if you bring that level 50 monster to a level 100 zone it will have the stats of a level 50.

This is why getting a high level spectre is so important for high level map content. They have vastly higher stats like damage and life.

---

### Monster's and their AI and Mana use

> [![Completed 1 Challenge](https://web.poecdn.com/image/icons/achievements/1.png?v=12)Mark_GGG](https://www.pathofexile.com/account/view-profile/Mark_GGG) wrote:
>
> Regarding the points on use of skills, Spectres have exactly the same AI as when not spectres. They use skills in the same situations. Yes, monsters use mana, and there are plenty of monsters where that's the primary timing mechanic - we know how much mana they have and how fast it regenerates, so set them to use skills when they can (and in some cases their AI specifically uses other skills when their mana is low, for example). For others mana consumption isn't a big issue, and it's based on the situation they're in - things such as numbers and positions of allies/enemies, which may well be different when they're minions compared to when they're monsters, because they'll mostly be expecting to fight a few strong enemies, not swarms of them.

What this means is that Mana use can be some spectre type's limiting factor. Using the blood magic gem produces some interesting results like monkey chieftains spamming their frenzy skill.

---

### Minions and On-Kill effects

If a minion does the kill, the on kill effect will not be attributed to you. However, if the minion Ignites or Poisons and either Ignite or Poison does the kill, the on kill effect will be attributed to you.

There is an exception with Head Hunter. It appears that minion kills count towards the effect.

---

### Frenzy, Power, Endurance Charges

[![Completed 1 Challenge](https://web.poecdn.com/image/icons/achievements/1.png?v=12)Mark_GGG](https://www.pathofexile.com/account/view-profile/Mark_GGG) wrote:

> - Monsters, Including minions, have the following stat values (unless overridden for specific monster types - I'm not aware of any current cases of this, though):
>
>   **Frenzy Charge**
>
> - 15% increased attack speed per frenzy charge
>
> - 15% increased cast speed per frenzy charge
>
> - 5% increased movement speed per frenzy charge
>
> - 4% more damage per frenzy charge
>
>   **Endurance Charge**
>
> - 15% physical damage per endurance charge
>
> - +15% to all elemental resistances per endurance charge
>
>   **Power Charge**
>
> - 200% increased critical strike chance per power charge

*Please note that minions has 3 charges max by default unless overridden by a specific mechanic*

---

### Soul Eater and Minions(Unending Hunger Jewel)

- Spectre only gains souls when they kill other monsters and must be in range, something like a circle half of the screen from the spectre
- The fact that spectre needs to be so close, spectre types that are more mid range or melee will take much more advantage of the jewel. Things like flame sentinels needs to be micromanage into place with convocation. 
- Spectre CANNOT gain souls from expiring or dying allied minions 
- The 50% chance can stack up to 100%, the aoe stacks to 2 x jewel sockets, the 30s duration will not stack
- Since spectre eats souls, you can NO longer can gain vaal souls reliably, this also interferes with master missions that involve soul feeding.
- once that 30s is up the spectre loses all stacks and must start over
- one soul goes to one spectre at a time, with multiple spectre's the souls gets spread out between the spectre's that has the buff
- Each stack of soul eater grants:
  - 5% attack/cast speed
  - 5% phys reduction
  - 5% resists
  - ??% character size




























