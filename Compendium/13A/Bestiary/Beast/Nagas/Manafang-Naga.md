---
aliases: [Manafang Naga]
created: 2023-05-28
level: 7
publish: 
role: leader
statblock: inline
strength: large
tags: ["13A/Bestiary/Beast", "13A/Monsters/Factions/Nagas", "13A/Monsters/Type/Leader"]
type: beast
updated: 2023-05-31
---

```statblock
layout: Basic 13th Age Monster Layout
columns: 1
name: "Manafang Naga"
size: "large"
level: "7"
levelOrdinal: "7th"
role: "leader"
type: "beast"
initiative: "14"
actions:
    - name: "Bite +12 vs. AC"
      desc: "45 damage"
      traits:
          - name: "Natural 16+"
            desc: "The naga gains resist spell damage 16+ against the target’s spells until the end of the battle."
          - name: "Miss"
            desc: "25 damage."
    - name: "R: Force missiles (1d4 nearby or far away enemies)"
      desc: "25 force damage"
      traits:
          - name: "Limited use"
            desc: "1/battle."
    - name: "C: Ritual movements +12 vs. MD (one nearby enemy, or one nearby enemy per point of esc. die if mystic escalator benefit is active)"
      desc: "40 psychic damage, and the target can’t cast spells or use the activated powers of true magic items (save ends)"
traits:
    - name: "Arcane mirror"
      desc: "When an enemy targets the manafang naga with a spell, the naga regains the use of force missiles if it’s expended. In addition, if that spell is a recharge spell, roll its recharge check immediately after the spell is cast. If the spell is a per-battle or daily spell, roll a hard save (16+) immediately after the spell is cast; on a success, the spellcaster doesn’t expend the spell."
    - name: "Mystic escalator"
      desc: "The naga and each of its nearby allies can use the escalation die unless the naga has been targeted by an enemy’s spell since its last turn."
ac: "23"
pd: "17"
md: "21"
hp: "210"
```
