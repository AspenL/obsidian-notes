```statblock
name: Gibbering Mouther
source: 5e SRD
size: Medium
type: aberration
subtype: ""
alignment: neutral
ac: 9
hp: 67
hit_dice: 9d8 + 26
speed: 10 ft., swim 10 ft.
stats:
  - 10
  - 8
  - 16
  - 3
  - 10
  - 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: prone
senses: darkvision 60 ft., passive Perception 10
languages: ""
cr: "2"
bestiary: true
traits:
  - name: Aberrant Ground
    desc: The ground in a 10-foot radius around the mouther is doughlike difficult terrain. Each creature that starts its turn in that area must succeed on a DC 10 Strength saving throw or have its speed reduced to 0 until the start of its next turn.
    attack_bonus: 0
  - name: Gibbering
    desc: The mouther babbles incoherently while it can see any creature and isn't incapacitated. Each creature that starts its turn within 20 feet of the mouther and can hear the gibbering must succeed on a DC 10 Wisdom saving throw. On a failure, the creature can't take reactions until the start of its next turn and rolls a d8 to determine what it does during its turn. On a 1 to 4, the creature does nothing. On a 5 or 6, the creature takes no action or bonus action and uses all its movement to move in a randomly determined direction. On a 7 or 8, the creature makes a melee attack against a randomly determined creature within its reach or does nothing if it can't make such an attack.
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: The gibbering mouther makes one bite attack and, if it can, uses its Blinding Spittle.
    attack_bonus: 0
  - name: Bites
    desc: "Melee Weapon Attack: +2 to hit, reach 5 ft., one creature. Hit: 17 (5d6) piercing damage. If the target is Medium or smaller, it must succeed on a DC 10 Strength saving throw or be knocked prone. If the target is killed by this damage, it is absorbed into the mouther."
    attack_bonus: 2
    damage_dice: 5d6
  - name: Blinding Spittle (Recharge 5-6)
    desc: The mouther spits a chemical glob at a point it can see within 15 feet of it. The glob explodes in a blinding flash of light on impact. Each creature within 5 feet of the flash must succeed on a DC 13 Dexterity saving throw or be blinded until the end of the mouther's next turn.
    attack_bonus: 0

```