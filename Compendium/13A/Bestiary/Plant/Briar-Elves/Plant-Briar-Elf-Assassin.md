---
aliases: [Plant Briar Elf Assassin]
created: 2023-05-30
level: 11
publish: 
role: archer
statblock: inline
strength: normal
tags: ["13A/Bestiary/Plant", "13A/Monsters/Factions/Briar-Elves", "13A/Monsters/Type/archer"]
type: plant
updated: 2023-05-31
---

```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Plant Briar Elf Assassin"
size: "normal"
level: "11"
levelOrdinal: "11th"
role: "archer"
type: "plant"
initiative: "16"
actions:
    - name: "Whip of thorns +17 vs. AC"
      desc: "40 damage"
      traits:
          - name: "Miss"
            desc: "20 damage."
          - name: "Natural 16+ hit"
            desc: "10 ongoing damage."
    - name: "R: Barbed arrows +17 vs. AC"
      desc: "50 damage"
      traits:
          - name: "Miss"
            desc: "20 damage."
          - name: "Natural even hit or miss"
            desc: "The briar elf assassin can _green walk_ as a move action instead of a standard action this turn."
traits:
    - name: "Green walk"
      desc: "Provided the briar elf assassin is next to a tree, as a standard action they can step into the tree and disappear. At the start of their next turn they reappear next to another nearby tree, and hit or miss their attack does double damage.<br/>Choose one"
    - name: "Humanoid"
      desc: "Twice per battle make a _barbed arrows_ attack as a quick action."
    - name: "Plant"
      desc: "This monster’s type is [PLANT]. Once per battle when this monster reappears after its _green walk_ it does triple damage instead of double damage."
    - name: "Undead"
      desc: "This monster’s type is [UNDEAD]. Once per battle when the escalation die is 4+ and this monster _green walks_ it immediately gets another turn."
nastier_traits:
    - name: "Strength of the forest"
      desc: "When this monster green walks it heals 1d4 × 20 hit points."
    - name: "Fear aura"
      desc: "Enemies engaged with this briar elf who have fewer than 96 hp are dazed (–4 attack) and can’t use the escalation die."
ac: "27"
pd: "24"
md: "23"
hp: "280"
```
