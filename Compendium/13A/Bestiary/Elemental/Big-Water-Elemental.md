---
aliases: [Big Water Elemental]
created: 2023-05-23
level: 7
publish: 
role: blocker
statblock: inline
strength: normal
tags: ["13A/Bestiary/Elemental", "13A/Monsters/Type/Blocker"]
type: elemental
updated: 2023-05-31
---

```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Big Water Elemental"
size: "normal"
level: "7"
levelOrdinal: "7th"
role: "blocker"
type: "elemental"
initiative: "11"
actions:
    - name: "Surge +11 vs. AC (up to 2 enemies)"
      desc: "22 damage"
      traits:
          - name: "Miss"
            desc: "The elemental heals 9 hp."
traits:
    - name: "Great wave transformation"
      desc: "Roll a d8 at the start of each of the water elemental’s turns. If you roll less than or equal to the escalation die, it shifts into great wave form until the end of the battle. While in this form, each enemy engaged with the elemental is hampered (and you stop rolling great wave transformation checks)."
    - name: "Liquid empowerment"
      desc: "The water elemental gains a +2 bonus to attacks and all defences while it’s in contact with a body of water, or while it’s nearby a sizeable body of water. A bucket or a bathtub of liquid doesn’t count; it must be at least a pond, creek, or maybe a large fountain. If the water elemental moves far away from the body of water the empowerment ends."
    - name: "Resist weapon damage 16+"
      desc: "When a weapon attack targets this creature, the attacker must roll a natural 16+ on the attack roll or it only deals half damage."
ac: "22"
pd: "20"
md: "16"
hp: "100"
```
