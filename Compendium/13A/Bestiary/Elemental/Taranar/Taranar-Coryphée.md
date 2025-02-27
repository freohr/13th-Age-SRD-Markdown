---
aliases: [Taranar Coryphée]
created: 2023-05-29
level: 3
publish: 
role: blocker
statblock: inline
strength: large
tags: ["13A/Bestiary/Elemental", "13A/Monsters/Factions/Taranar", "13A/Monsters/Type/Blocker"]
type: elemental
updated: 2023-05-31
---

```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Taranar Coryphée"
size: "large"
level: "3"
levelOrdinal: "3rd"
role: "blocker"
type: "elemental"
initiative: "5"
vulnerability: "cold, fire"
actions:
    - name: "Sparking clogs +7 vs. AC (2 attacks)"
      desc: "10 damage"
      traits:
          - name: "Natural even hit"
            desc: "The target takes 5 lightning damage from the electrical discharge caused by the impact of crystal-laced stone feet on their person."
    - name: "C: Stoneshoe shuffle +8 vs. PD (1d4 nearby enemies)"
      desc: "18 damage"
      traits:
          - name: "Natural roll over target’s Dexterity"
            desc: "The target is hampered as the localized earth tremors generated by the dancing stones causes them to struggle to maintain their balance (save ends)."
          - name: "Limited use"
            desc: "The coryphée can use this ability only when the escalation die is even."
ac: "20"
pd: "18"
md: "13"
hp: "66"
```
