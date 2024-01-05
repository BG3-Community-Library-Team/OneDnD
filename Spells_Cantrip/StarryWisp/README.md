# Starry Wisp Cantrip

[![GitHub commits](https://img.shields.io/github/commits-since/BG3-Community-Library-Team/BG3-OneDnD-Modules/ua8.cantrip.sw.1.0.0.0/main)](https://GitHub.com/BG3-Community-Library-Team/BG3-OneDnD-Modules/commit/)  
[Latest Release](https://github.com/BG3-Community-Library-Team/BG3-OneDnD-Modules/releases/tag/ua8.cantrip.sw.1.0.0.0)

---


> [Inspired by OneDnD Player's Handbook Playtest 8](https://www.dndbeyond.com/sources/ua/ph-playtest-8)  
> ## STARRY WISP  
> *Evocation Cantrip (Bard, Druid)*  
> **Casting Time:** Action  
> **Range:** 60 feet  
> **Components:** V, S  
> **Duration:** Instantaneous  
>
> You launch a mote of light at one creature or object within range. Make a ranged spell attack against the target. On a hit, the target takes 1d8 Radiant damage, and until the end of your next turn, it emits Dim Light in a 10-foot radius and can’t benefit from the Invisible condition.  
>
> **Cantrip Upgrade.** This spell’s damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8).


![Spell](https://cdn.discordapp.com/attachments/929511280535015445/1189041366353842246/SHV_StarryWisp.gif)

## Implementation
### Spell
**Spell Type:** Projectile.  
**Range:** 18.  
**Cost:** Action.  
**Target:** Not Self and not Dead.  
**Damage Type:** Radiant.  
**Damage Amount:** D8 Cantrip Progression.  
Status applied to target on damage until end of next turn.

### Status
**Stack ID:** Invisibility  
**Stack Priority:** 9  
**Light Distance:** 3  
**Status Immunity:** SG_Invisible  
**Status Group:** SG_Light  

---

## Downloads

- [Nexusmods](https://www.nexusmods.com/baldursgate3/mods/5355)

## Requirements

- [BG3-Community-Library](https://github.com/BG3-Community-Library-Team/BG3-Community-Library)
- [BG3-Compatibility-Framework](https://github.com/BG3-Community-Library-Team/BG3-Compatibility-Framework)
- [Shivero's VFX Library](https://www.nexusmods.com/baldursgate3/mods/3888)

## Acknowledgements

- Larian Software, for working on Baldur's Gate 3 and bringing 5th Edition to PC.
- The Baldur's Gate 3 Modding Community.
- [ShinyHobo](https://github.com/ShinyHobo) for their work easing the process of creating .pak files.
- Alana for the creation of the Mod Manager Compatibility Images.

---