```statblock
layout: Basic 5e Layout
name: Ossandir the Warded
size: Medium
type: humanoid
subtype: dragonborn
alignment: lawful neutral
ac: 16
hp: 112
hit_dice: 15d8 + 45
speed: "30 ft."
stats: [18, 15, 16, 10, 12, 15]
saves:
  - strength: 7
  - dexterity: 5
  - constitution: 6
  - wisdom: 4
skillsaves:
  - athletics: 10
  - performance: 5
senses: "passive Perception 11"
languages: "Common, Draconic"
damage_resistances: lightning
cr: 5
actions:
  - name: Multiattack
    desc: "Ossandir makes three Halberd attacks. He can replace one attack with a use of Shield Bash."
  - name: Halberd
    desc: "Melee or Ranged Attack Roll: +7, reach 5 ft. or range 20/60 ft. Hit: 11 (2d6 + 4) piercing damage."
  - name: "Shield Bash"
    desc: "Strength Saving Throw: DC 15, one creature within 5 feet Ossandir can see. Failure: 9 (2d4 + 4) bludgeoning damage. If the target is Medium or smaller, it also has the Prone condition."
  - name: "Thunderous Rebuke (Recharge 5-6)"
    desc: "Ossandir releases a crackling shockwave in a 30-foot cone. Each creature in that area must make a DC 14 Strength saving throw, taking 14 (4d6) lightning damage and being pushed 30 feet away and knocked prone on a failed save, or half as much damage and no other effect on a successful one."
reactions:
  - name: Parry
    desc: "Trigger: Ossandir is hit by a melee attack roll while holding a weapon. Response: he adds 3 to his AC against that attack, possibly causing it to miss."
```
