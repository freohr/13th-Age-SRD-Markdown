---
aliases: [Undead Briar Elf Stalker]
created: 2023-05-30
level: 8
publish: 
role: archer
statblock: inline
strength: normal
tags: ["13A/Bestiary/undead", "13A/Monsters/Type/archer"]
type: undead
updated: 2023-05-31
---

```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Undead Briar Elf Stalker"
size: "normal"
level: "8"
levelOrdinal: "8th"
role: "archer"
type: "undead"
initiative: "16"
actions:
    - name: "Whip of thorns +13 vs. AC"
      desc: "20 damage"
      traits:
          - name: "Miss"
            desc: "10 damage."
          - name: "Natural 16+ hit"
            desc: "5 ongoing damage."
    - name: "R: Barbed arrows +14 vs. AC"
      desc: "25 damage"
      traits:
          - name: "Miss"
            desc: "10 damage."
          - name: "Natural even hit or miss"
            desc: "The briar elf can _green walk_ as a move action instead of a standard action this turn."
traits:
    - name: "Green walk"
      desc: "Provided the briar elf stalker is next to a tree, as a standard action they can step into the tree and disappear. At the start of their next turn they reappear next to another nearby tree, and hit or miss their attack does double damage."
    - name: "Undead Nature"
      desc: "This monster’s type is [UNDEAD]. Once per battle when the escalation die is 4+, this monster green walks it immediately gets another turn."
nastier_traits:
    - name: "Strength of the forest"
      desc: "When this monster green walks it heals 1d4 × 10 hit points."
    - name: "Fear aura"
      desc: "Enemies engaged with this briar elf who have fewer than 48 hp are dazed (–4 attack) and can’t use the escalation die."
ac: "24"
pd: "21"
md: "20"
hp: "140"
```