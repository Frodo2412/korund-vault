```statblock
layout: Basic 5e Layout
name: Ferrin Quickscale
size: Medium
type: humanoid
subtype: dragonborn
alignment: lawful neutral
ac: 17
hp: 66
hit_dice: 12d8 + 12
speed: "30 ft."
stats: [12, 18, 12, 14, 11, 15]
senses: "passive Perception 10"
languages: "Common, Draconic"
damage_resistances: fire
cr: 4
traits:
  - name: "Suave Defense"
    desc: "While wearing light or no armor and no shield, Ferrin's AC includes his Charisma modifier."
  - name: Opportunistic
    desc: "Ferrin doesn't provoke opportunity attacks when moving out of a creature's reach, provided he ends that movement at least 10 feet from that creature."
actions:
  - name: Multiattack
    desc: "Ferrin makes one Brass Fang (dagger) attack and two Brass Fang (rapier) attacks."
  - name: "Brass Fang (Dagger)"
    desc: "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft. Hit: 6 (1d4 + 4) piercing damage."
  - name: "Brass Fang (Rapier)"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft. Hit: 8 (1d8 + 4) piercing damage plus 3 (1d6) fire damage."
  - name: "Sleeping Ember Breath (Recharge 5-6)"
    desc: "Each creature in a 15-foot cone must make a DC 13 Constitution saving throw. First Failure: the target has the incapacitated condition until the end of its next turn, when it repeats the save. Second Failure: the target has the unconscious condition for 1 minute. This ends if the target takes damage or an ally within 5 feet uses an action to wake it."
bonus_actions:
  - name: Lightfooted
    desc: "Ferrin takes the Dash or Disengage action."
```