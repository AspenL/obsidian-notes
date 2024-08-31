---
aliases: [anemo construct, cryo construct, dendro construct, electro construct, geo construct, hydro construct, pyro construct]
tags: [magic, object, elemental]
---

An elemental construct is an inanimate magical object.
It is constantly under it's element status effect, though simply touching it doesn't necessarily transfer the status to the creature.

It radiates a moderate conjuration aura.

```statblock
name: Elemental Construct
size: Small/Medium/Large
type: object
ac: 10 + Proficiency
hp: roll
hit_dice: Skill/Burst Dice + Proficiency
speed: 0
stats: [0, 0, 0, 0, 0, 0]
damage_vulnerabilities: Same as caster
damage_immunities: Same as caster
condition_immunities: all
cr: Same as caster
traits:
	- [Disclaimer, The construct can have either a trait or an action, and only of the associated element]
    - [Anemo, Creatures of the caster's choice pass through the construct as if it didn't exist]
    - [Cryo, Creatures moving within 10 ft of the construct must make a Dex Save or fall prone]
    - [Dendro, Creatures adjacent to the construct must make a Dex save or take Dendro reaction damage]
    - [Electro, Creatures have their movement halved while within 10 ft of the construct and cannot take reactions]
    - [Geo, If summoned in an occupied space, the creature is lifted up to the top of the construct]
    - [Hydro, Creatures of the caster's choice pass through the construct as if it didn't exist]
    - [Pyro, Creatures of the caster's choice are charmed/aggro'd by the construct until hit by an attack]
actions:
	- [Disclaimer, The construct can have either a trait or an action, and only of the associated element]
    - [Anemo, Creature of the caster's choice makes a Str Save or is moved 10 ft in a direction the caster chooses]
    - [Cryo, Hostile creatures starting their turn within 10 ft of the construct must make a Con save or take (skill/burst dice) cold damage]
    - [Dendro, Targets within 10 ft must make a Con save or be affected by the _Slow_ spell]
    - [Electro, Deal (skill/burst dice) lightning damage to a target within 10 ft.]
    - [Geo, Inflict a condition to creatures of the caster's choice within 10 ft of the construct, unless they suceed on an appropriate Save]
    - [Hydro, Force a creature of the caster's choice to make a Dex Save or be restrained in a bubble for (1d4) rounds]
    - [Pyro, Explodes dealing (skill/burst dice) fire damage to creatures within 10 ft of the construct, flammable objects in the area are ignited]
````