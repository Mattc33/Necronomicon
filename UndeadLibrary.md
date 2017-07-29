<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [UnDead Library](#undead-library)
  - [What is Raise Spectre?](#what-is-raise-spectre)
    - [Sources of +1 Spectre?](#sources-of-1-spectre)
    - [Implicit Values of Mobs?](#implicit-values-of-mobs)
    - [Monster Skills?](#monster-skills)
  - [DPS Spectres (Clearing)](#dps-spectres-clearing)
    - [Fire](#fire)
      - [Flame Sentinels](#flame-sentinels)
      - [Undying Incinerators](#undying-incinerators)
      - [Goatman Fire-Raiser](#goatman-fire-raiser)
    - [Ice](#ice)
      - [Undying Grapplers](#undying-grapplers)
      - [Merveil Blessed](#merveil-blessed)
    - [**Lightning**](#lightning)
      - [Stygian Revenant](#stygian-revenant)
    - [**Physical**](#physical)
      - [Knitted Horror](#knitted-horror)
      - [Kitava's Herald](#kitavas-herald)
    - [**Chaos**](#chaos)
  - [DPS Spectres (Single Target)](#dps-spectres-single-target)
    - [**Fire**](#fire)
      - [Cannibal Fire-Eater](#cannibal-fire-eater)
    - [Ice](#ice-1)
    - [**Lightning**](#lightning-1)
    - [**Physical**](#physical-1)
      - [Slashed Miscreation](#slashed-miscreation)
    - [Chaos](#chaos)
  - [Tanks/Utility](#tanksutility)
    - [Fire](#fire-1)
    - [**Ice**](#ice)
    - [**Lightning**](#lightning-2)
    - [**Physical**](#physical-2)
      - [Towering Figment](#towering-figment)
      - [Undying Evangelist](#undying-evangelist)
    - [Chaos](#chaos-1)
  - [**Monster Skills**](#monster-skills)
    - [**Proximity Shield**](#proximity-shield)
    - [**Unrighteous Fire**](#unrighteous-fire)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

[TOC]

# UnDead Library

---

## What is Raise Spectre?

<img src="https://i.gyazo.com/df06052ffcccc2a8352a0f768cf20741.png" height="500" />

This skill raises the corpse of a slain monster or a corpse of a monster that is summoned with desecrate. The monster raised will retain all of the properties of the base monster type. Raising a rare monster will not grant it's rare modifiers. You also cannot raise unique monsters. 

The core dps minion of any classical summoner builds. As of Patch 3.0 you can realistically have as many as 4-5 Spectre at once.

---

>  Table from poe.db

| Level  | Requires Level | Intelligence | Mana Cost | Minions deal 30% less Damage | Minions have 20% less Life | Minions have 20% less Energy Shield | Experience  |
| ------ | -------------- | ------------ | --------- | ---------------------------- | -------------------------- | ----------------------------------- | ----------- |
| 1      | 28             | 66           | 21        | 30                           | 20                         | 20                                  | 199,345     |
| 2      | 31             | 72           | 23        | 25                           | 19                         | 19                                  | 285,815     |
| 3      | 34             | 79           | 24        | 21                           | 18                         | 18                                  | 401,344     |
| 4      | 37             | 85           | 26        | 17                           | 17                         | 17                                  | 554,379     |
| 5      | 40             | 91           | 27        | 14                           | 16                         | 16                                  | 477,437     |
| 6      | 42             | 95           | 28        | 11                           | 15                         | 15                                  | 583,786     |
| 7      | 44             | 100          | 29        | 8                            | 14                         | 14                                  | 710,359     |
| 8      | 46             | 104          | 30        | 6                            | 13                         | 13                                  | 1,355,511   |
| 9      | 48             | 108          | 31        | 4                            | 12                         | 12                                  | 1,138,877   |
| 10     | 50             | 112          | 32        | 2                            | 11                         | 11                                  | 1,368,233   |
| 11     | 52             | 116          | 33        | 0                            | 10                         | 10                                  | 1,638,338   |
| 12     | 54             | 121          | 34        | -1                           | 9                          | 9                                   | 1,956,648   |
| 13     | 56             | 125          | 35        | -2                           | 8                          | 8                                   | 3,655,184   |
| 14     | 58             | 129          | 36        | -3                           | 7                          | 7                                   | 3,017,327   |
| 15     | 60             | 133          | 37        | -4                           | 6                          | 6                                   | 7,759,995   |
| 16     | 62             | 137          | 38        | -5                           | 5                          | 5                                   | 15,138,193  |
| 17     | 64             | 142          | 39        | -6                           | 4                          | 4                                   | 26,083,825  |
| 18     | 66             | 146          | 40        | -7                           | 3                          | 3                                   | 62,620,247  |
| 19     | 68             | 150          | 41        | -8                           | 2                          | 2                                   | 211,708,088 |
| **20** | **70**         | **154**      | **42**    | **-10**                      | **0**                      | **0**                               |             |
| 21     | 72             |              | 43        | -12                          | -2                         | -2                                  |             |
| 22     | 74             |              | 44        | -14                          | -4                         | -4                                  |             |
| 23     | 76             |              | 44        | -16                          | -6                         | -6                                  |             |
| 24     | 78             |              | 45        | -18                          | -8                         | -8                                  |             |
| 25     | 80             |              | 46        | -20                          | -10                        | -10                                 |             |
| 26     | 82             |              | 47        | -22                          | -12                        | -12                                 |             |
| 27     | 84             |              | 48        | -24                          | -14                        | -14                                 |             |
| 28     | 86             |              | 49        | -26                          | -16                        | -16                                 |             |
| 29     | 88             |              | 50        | -28                          | -18                        | -18                                 |             |
| 30     | 90             |              | 51        | -30                          | -20                        | -20                                 |             |

---

### Sources of +1 Spectre?

1. [Midnight Bargain](https://pathofexile.gamepedia.com/Midnight_Bargain) (Up to +2)
2. [Vis Mortis](https://pathofexile.gamepedia.com/Vis_Mortis) (+1)
3. [Bones of Ullr](https://pathofexile.gamepedia.com/Bones_of_Ullr) (+1)
4. [Death Attunement](https://pathofexile.gamepedia.com/Death_Attunement) (+1)
5. [Queen's Decree](https://pathofexile.gamepedia.com/Queen%27s_Decree) (+1)
6. [Queen's Escape](https://pathofexile.gamepedia.com/Queen%27s_Escape) (+1)

---

### Implicit Values of Mobs?

Yes, Your spectre will gain the **Implicit Values** of Mobs. 

For example if the monster has "farshot" by default. The raised spectre will also have farshot. Some unique base abilities can be used and combined with everything else poe offers in interesting ways.

---

### Monster Skills?

First thing to note is Monster Skills **!=(Does not Equal)** Player Skills.

They have their own stats, scaling, art, and even behavior.

Some monsters will introduce entirely new mechanics to your playstyle.

For example any monster that has the implicit "Proximity Shield" will grant a bubble that prevents any damage from the outside from damaging anything inside. The source of damage must be inside. You will tend to be near your own creatures or convocate strategically to prevent damage.

---

## DPS Spectres (Clearing)

> Spectre used most of the time as clearing maps is a large portion of the game.
>
> The suggested links are by far personal opinion(3.0 update). Builds vary so links will vary. 
>
> Please note I am not 100% clear on the Damage and Defense percentages, I believe this is based off their base stat value at whatever level they were raised.

---

### Fire

---

#### Flame Sentinels

| Monster Form | Raise Spectre                            | Stygian Cosmetic                         |
| ------------ | ---------------------------------------- | ---------------------------------------- |
|              | <img src="https://i.gyazo.com/6449170efbac6984f5f640aee44a7d15.png" height="300" /> | <img src="https://i.gyazo.com/af1d46e2c3676cc300a1e69acf587b9f.png" height="300"/> |



The first mentioned Spectre for a reason, these are the tried and true spectre for the longest time. A good balance of damage and tankiness. They come a augmented fire ball which alternates between lmp and fork and regular. They also have an amazing AI and can reach 1-2 screens away. If you are looking for a consistent spectre this is your guy. They also benefit from being able to be desecrated in many high level map zones.

http://poedb.tw/us/mon.php?n=Flame+Sentinel



| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | 3 fireballs with alternating supports. Regular => with LMP => with Fork |
| Tags      | [Minion, Projectile, Spell, AOE, Fire]   |
| Implicit  | Cast Augmented Fireballs                 |
| Damage    | 120%                                     |
| Defense   | 180% \| 0 Fire Res, 75% Cold Res, 0 Lightning Res, 0 Chaos Res |
| Range     | 0~2 screens away                         |
| Videos    | Maze Boss, https://www.youtube.com/watch?v=uLuxvXu7MpQ&t=2m45s |
| Locations | Eternal Laboratory, Ramparts, Racecourse, Quay, Arsenal, Museum, Factory. Plaza, Colonnade, Courtyard |

-   Suggested Links:

    >   Minion Damage => Spell Echo => GMP
    >
    >   Minion Damage => Spell Echo => GMP => Elemental Focus
    >
    >   **Damage:** Minion Damage => Spell Echo => GMP => Elemental Focus => Fire Penetration
    >
    >   **Clear:** Minion Damage => Spell Echo => GMP => Elemental Focus => Faster Projectile
    >
    >   ---
    >
    >   *Swap out GMP for Slower Projectiles on Single Target*
    >
    >   *Fire Penetration is normally better for any target above 15% fire resistance, which is pretty much any monster that matters*

    ​

---

#### Undying Incinerators

<img src="https://i.gyazo.com/1edec8672ae92d2c19e66805e424d762.png" height="300" />

Their fireballs do not have as big of a damage range as flame sentinels but their casting animation and general cast speed is superior. They also throw down firetraps which is a huge burst of damage. These guys scale extremely well with cast speed. There is also an interesting interaction with spell echo and their trap. Causes them to throw two traps down, with cluster trap you will get 6 traps per cast. They do have a huge drawback thou. They are squishy and they explode and die at low life which doesn't help.

- Spell echo and cluster traps will cause them to cast 6 traps at once

http://poedb.tw/us/mon.php?n=Undying+Incinerator

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Fireball, Firetrap and Suicide Explosion(at low life) |
| Tags      | [Minion, Projectile, Spell, AOE, Fire, Trap] |
| Implicit  | Throws Fire Bombs, Explodes when on Low Life, immune_to_lava_damage |
| Damage    | 100%                                     |
| Defense   | 100% \| 75% Fire Res , 0 Cold Res, 0 Lightning Res, 0 Chaos Res |
| Range     | 0~2 screens away                         |
| Videos    |                                          |
| Locations |                                          |

**Suggested Links:**

>   Minion Damage => Spell Echo => GMP
>
>   Minion Damage => Spell Echo => GMP => Elemental Focus
>
>   **Damage:** Minion Damage => Spell Echo => GMP => Elemental Focus => Fire Penetration
>
>   **Clear:** Minion Damage => Spell Echo => GMP => Elemental Focus => Faster Projectile
>
>   ---
>
>   **Traps:**
>
>   Minion Damage => Spell Echo => Cluster Trap 
>
>   Minion Damage => Spell Echo => Cluster Trap ==> Trap and Mine
>
>   Minion Damage => Spell Echo => Cluster Trap ==> Trap and Mine ==> Fire Penetration
>
>   ---
>
>   *Swap out GMP for Slower Projectiles on Single Target*
>
>   *Swap out Cluster Trap for Trap Cool down on Single Target*
>
>   *Fire Penetration is normally better for any target above 15% fire resistance, which is pretty much any monster that matters*

---

#### Goatman Fire-Raiser

<img src="https://i.gyazo.com/117a005196ca5bbf796b0098fc748c14.png" height="300" />

These guys has some of the highest damage potential possible. They have a huge damage range and their implicit of reduced cast speed is mostly countered by spell echo and stacking castspeed on them. They shoot their fireballs at long range and when they enter medium range they shoot their magma orbs. They will also occasionally cast molten shell which gives them massive armor and a huge burst of damage if they are on top of bosses. Due to magma orb mechanics the area between bounces can overlap dealing double the damage to targets with a larger hitbox(kuduku sized or bigger).

- iAOE will increase the damage overlap area between bounces
- Faster projectiles will increase magma orb range
- Slower projectile will cause magma orbs to bounce in a tighter area

http://poedb.tw/us/mon.php?n=Goatman+Fire-raiser

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | fireball, magma orb, molten shell        |
| Tags      | [Minion, Projectile, Spell, AOE, Fire]   |
| Implicit  | 50% reduced Cast Speed                   |
| Damage    | 100%                                     |
| Defense   | 140%                                     |
| Range     | 1~2 screens away                         |
| Videos    | Abyss Kaom, https://www.youtube.com/watch?v=YgwONmsBaJI |
| Locations | Canyon, shaped canyon, Gorge, Plateau, any map that rolls with goatman or animals |

Suggested Links:

>   Minion Damage => Spell Echo => GMP
>
>   Minion Damage => Spell Echo => GMP => Elemental Focus
>
>   **Damage:** Minion Damage => Spell Echo => GMP => Elemental Focus => Fire Penetration
>
>   **Clear:** Minion Damage => Spell Echo => GMP => Elemental Focus => Faster Projectile
>
>   ------
>
>   *Swap out GMP for Slower Projectiles on Single Target*
>
>   *Fire Penetration is normally better for any target above 15% fire resistance, which is pretty much any monster that matters*

---

### Ice

---

#### Undying Grapplers

<img src="https://i.gyazo.com/44f7d928836a3a2ace2b95850efba791.png" height="300" />

These guys are one of the few melee base types that is viable and its only due to their massive discharge damage. They are only usable with the Victario Charity shield with Necro Aegis. You need to combine that with a flood of minions, lots of zombies and srs to generate charges for them to discharge. With the Victario Charity you will most likely get more frenzy charges so our discharge element will be mostly cold.

- As far as I can tell they don't get empowered if your other minions die
- Deals 441 to 1322 Lightning Damage per Power Charge
- Deals 627 to 940 base Fire Damage per Endurance Charge
- Deals 513 to base Cold Damage per Frenzy Charge

http://poedb.tw/us/mon.php?n=Undying+Grappler

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Flicker strike and Discharge             |
| Tags      | [Minion, Spell, AOE, Fire, Ice, Lightning] |
| Implicit  | Empowered as Kin Slain, Uses Flicker Strike, Casts Discharge |
| Damage    | 100%                                     |
| Defense   | 100% \| 20 Fire Res, 20 Cold Res, 20 Lightning Res, 20 Chaos Res |
| Range     | 0~2 screens away                         |
| Videos    |                                          |
| Locations | Vaal Pyramid, Lab(merc), Lab(uber), Residence |

---

#### Merveil Blessed

[Insert Image here]

A viable cold based spectre. Faster proj is needed b/c their projectiles seem to be too short for clearing without them. They consistently freeze rares and even bosses. These would be great general mapping choice due to their damage and increased survivability of freeze/chilling everything . They are rather hard to find naturally.

- Frostbolt pierces 100% by default
- GMP/LMP seems to create overlapping "waves" unsure if the damage stacks

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Frost bolt and sea witch wave            |
| Tags      | [Minion, Projectile, Spell, AOE, Cold]   |
| Implicit  | N/A                                      |
| Damage    | 102%                                     |
| Defense   | 144% \| 0 Fire Res, 75% Cold Res, 0 Lightning Res, 0 Chaos Res |
| Range     | 0~1 screens away, 0-2 screens away if faster projectile support |
| Videos    | https://www.youtube.com/watch?v=uuxqOE2SQN0 |
| Locations | Courtyard, Scriptorium, Beach, Strand,   |

---

### **Lightning**

---

#### Stygian Revenant

<img src="https://i.gyazo.com/0f88487f66abc97a54931035b6acbf36.png" height="250" />

They have an interesting interaction with sire of shards. Putting them in there gives it a free GMP and they fire their spells forward despite the sire of shards nova ability. They have a wonky AI and skitter around a lot but they deal a lot of damage since their base damage on the projectile is high. They have a somewhat narrow field of attack unless the chain support gem is used.

-   chain is necessary for clear
-   Adding projectile will add to the end of the "volley", think barrage

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Monster Projectile Spell (Some kind of lightning barrage projectile), Default Attack |
| Tags      | [Minion, Projectile, Spell, Lightning]   |
| Implicit  | N/A                                      |
| Damage    | 140%                                     |
| Defense   | 182% \| 0 Fire Res, 0 Cold Res, 75 Lightning Res, 0 Chaos Res |
| Range     | 0~2 screens away                         |
| Videos    |                                          |
| Locations | The Harvest,                             |

---

### **Physical**

---

#### Knitted Horror

<img src="https://i.gyazo.com/a12209a99f4dd8c84f42aafc465db06d.png" height="250" />

These mobs are really interesting. They are actually 2 monsters in one. The archers that are on it's back shoot puncture projectiles while the main body can melee independently. They are 100% Pierce already so you cannot chain the projectiles. Their projectile have a fixed length so slower proj will not make it any shorter. 

This spectre is also insanely tanky. 

-   2 mobs in one archers on the back, melee "mount" at the bottom
-   uses puncture with a fixed distance

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Puncture, Default Attack                 |
| Tags      | [Minion, Projectile, Attack, Duration]   |
| Implicit  | Uses Puncture                            |
| Damage    | 98%                                      |
| Defense   | 225% \| 0 Fire Res, 0 Cold Res, 75 Lightning Res, 0 Chaos Res |
| Range     | 0~2 screens away                         |
| Videos    | https://www.youtube.com/watch?v=uvWUTo6sXbM |
| Locations | Dried Lake,                              |

---

#### Kitava's Herald

---

### **Chaos**

---

## DPS Spectres (Single Target)

---

### **Fire**

---

#### Cannibal Fire-Eater

<img src="https://i.gyazo.com/003142bfab6a145fbaffb6a525916065.png" height="250" />

They have their own version of flame totems but centered on their own monster model. It deals tremendous amounts of fire damage focused into a cone.

-   Self cast flame totem that repeats up to 8 times

http://poedb.tw/us/mon.php?n=Cannibal+Fire-eater

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Self Casted Flame Totem                  |
| Tags      | [Minion, Projectile, Spell, Fire]        |
| Implicit  | N/A                                      |
| Damage    | 120%                                     |
| Defense   | 144% \| 0 Fire Res, 0 Cold Res, 0 Lightning Res, 0 Chaos Res |
| Range     | 0~1/2 screens away                       |
| Videos    |                                          |
| Locations | The Coast,                               |



---



### Ice

---

### **Lightning**

---

### **Physical**



---

#### Slashed Miscreation

[insert image here]

Since they use a physical spell we can scale these with extra physical damage. Due to this fact they pair extremely well with spirit offering which grants them a nice extra chaos bonus. The poison paired with multiple blade vortex's going off can stack damage quickly.

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Blade Vortex, Default Attack             |
| Tags      | [Minion,  Spell, AOE, Duration]          |
| Implicit  | Quick                                    |
| Damage    | 100%                                     |
| Defense   | 150% \| 0 Fire Res, 0 Cold Res, 0 Lightning Res, 0 Chaos Res |
| Range     | 1/2 screens away                         |
| Videos    |                                          |
| Locations | Demon Rolled Maps,                       |

---

### Chaos

---

## Tanks/Utility

>   Spectre types that are particularly tanky or has a great utility ability that is useful regardless of their damage potential.

---

### Fire

---

### **Ice**

---

### **Lightning**

---

### **Physical**

---

#### Towering Figment

---

#### Undying Evangelist

<img src="https://i.gyazo.com/b1dded9dfc568a5b7777c742b4c68b82.png" height="250" />

Their proximity shield make these spectre the best defensive utility spectre type in the game. Anything within the shield cannot be damaged by any kind of damage that is fired from outside of the shield. Making you immune you a wide variety of attacks as long as you are standing inside the bubble. They also come with a solid damage type being a physical spell. Monsters naturally have low armor so this damage type cannot miss and cannot be mitigated well. They can also take full advantage of hatred and similar modifiers. The drawback of these spectre types in the relatively low clear speed due to the nature of their delayed skill.

-   iDuration and less duration will impact proximity shield time length

http://poedb.tw/us/mon.php?n=Undying+Evangelist

| Category  | Description                              |
| --------- | ---------------------------------------- |
| Uses      | Delayed Blast, Proximity Shield          |
| Tags      | [Minion, AOE, Spell, Duration]           |
| Implicit  | N/A                                      |
| Damage    | 120%                                     |
| Defense   | 120% \| 37 Fire Res, 37 Cold Res, 37 Lightning Res, 0 Chaos Res |
| Range     | 0~1.5 screens away                       |
| Videos    |                                          |
| Locations | The Sceptre of God, The Upper Sceptre of God, Museum, Courtyard |

---

### Chaos

---

## **Monster Skills**

---

### **Proximity Shield**

---

### **Unrighteous Fire**

---











