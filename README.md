## BGT Spawn Tweak
This little mod for Baldur's Gate Trilogy allows you to tweak the parameters of the area spawn points to change the difficulty of the encounters.

### Installation steps
1. Install [Baldur's Gate Trilogy](https://github.com/SpellholdStudios/BGT-WeiDU) (v1.21 or higher required).
2. Copy **setup-spawntweak.exe** and the folder **spawntweak** to your game directory.
3. Open **spawntweak/config.ini**, read the descriptions and tweak the parameters to your liking.
4. Run **setup-spawntweak.exe** to install the mod with the configured parameters.

### Compatibility notes
BGT Spawn Tweak is fundamentally incompatible with other BGT spawn mods, such as BGSpawn or BGT Tweak Pack component "Altered Spawns".

### Available tweaks
* Spawn difficulty modifier
* Maximum number of creatures per spawn point
* Delay between entering an area and spawning
* Spawn probability
* Deactivate the spawn point after spawning once
* Disable all spawns

### Difficulty calculator
To calculate the desired spawn difficulty, use the spawning formula and the creature power level list below.

```
No. spawns = (Spawn Difficulty * Avg. Party Lvl * Party Size) / Creature Power Lvl (rounded down)
```
```
CRE: KOBOLA_A  LVL:  3  HP:  4  XP:    7
CRE: KOBOLA_B  LVL:  3  HP:  4  XP:    7
CRE: KOBOLA_C  LVL:  3  HP:  4  XP:    7
CRE: KOBOLA_D  LVL:  3  HP:  4  XP:    7
CRE: KOBOLA_E  LVL:  3  HP:  4  XP:    7
CRE: KOBOLDA   LVL:  3  HP:  4  XP:    7
CRE: KOBOLD_A  LVL:  3  HP:  4  XP:    7
CRE: KOBOLD_B  LVL:  3  HP:  4  XP:    7
CRE: KOBOLD_C  LVL:  3  HP:  4  XP:    7
CRE: KOBOLD_D  LVL:  3  HP:  4  XP:    7
CRE: KOBOLD_E  LVL:  3  HP:  4  XP:    7
```
```
CRE: XVART_A   LVL:  4  HP:  7  XP:   15
CRE: XVART_B   LVL:  4  HP:  7  XP:   15
CRE: XVART_C   LVL:  4  HP:  7  XP:   15
CRE: GIBBER2   LVL:  4  HP:  4  XP:   35
CRE: GIBBER    LVL:  4  HP:  8  XP:   35
CRE: TASLOI    LVL:  4  HP:  8  XP:   35
CRE: DOGWI     LVL:  4  HP:  9  XP:   35
```
```
CRE: SKELET03  LVL:  5  HP:  8  XP:   65
CRE: SKELETS   LVL:  5  HP:  8  XP:   65
CRE: SKELET_A  LVL:  5  HP:  8  XP:   65
CRE: SKELET_B  LVL:  5  HP:  8  XP:   65
CRE: SKELET_C  LVL:  5  HP:  8  XP:   65
CRE: ZOMBIE_A  LVL:  5  HP: 15  XP:   65
CRE: ZOMBIE_B  LVL:  5  HP: 15  XP:   65
CRE: ZOMBIE_C  LVL:  5  HP: 15  XP:   65
CRE: ZOMBIE_D  LVL:  5  HP: 15  XP:   65
CRE: ZOMBIE_E  LVL:  5  HP: 15  XP:   65
```
```
CRE: HOBGOA_A  LVL:  6  HP:  8  XP:   35
CRE: HOBGOA_B  LVL:  6  HP:  8  XP:   35
CRE: HOBGOA_C  LVL:  6  HP:  8  XP:   35
CRE: HOBGOA_D  LVL:  6  HP:  8  XP:   35
CRE: HOBGOA_E  LVL:  6  HP:  8  XP:   35
CRE: HOBGOB_A  LVL:  6  HP:  8  XP:   35
CRE: HOBGOB_B  LVL:  6  HP:  8  XP:   35
CRE: HOBGOB_C  LVL:  6  HP:  8  XP:   35
CRE: HOBGOB_D  LVL:  6  HP:  8  XP:   35
CRE: HOBGOB_E  LVL:  6  HP:  8  XP:   35
CRE: BANDIT    LVL:  6  HP:  8  XP:   65
```
```
CRE: BGWOLF    LVL:  7  HP: 24  XP:   65
```
```
CRE: GNOLL     LVL:  8  HP: 15  XP:   35
CRE: GNOLL_B   LVL:  8  HP: 15  XP:   35
CRE: GNOLL_D   LVL:  8  HP: 15  XP:   65
CRE: GNOLL_A   LVL:  8  HP: 18  XP:   65
CRE: GNOLL_E   LVL:  8  HP: 22  XP:   65
CRE: DOGWA     LVL:  8  HP: 17  XP:   65
CRE: FLIND     LVL:  8  HP: 19  XP:  120
```
```
CRE: IRONGU    LVL: 10  HP: 23  XP:  120
CRE: WORG      LVL: 10  HP: 26  XP:  120
```
```
CRE: BEARBL    LVL: 12  HP: 25  XP:  175
CRE: OGREGR    LVL: 12  HP: 19  XP:  175
CRE: IRONELIT  LVL: 12  HP: 26  XP:  240
```
```
CRE: WOLFDI    LVL: 14  HP: 33  XP:  125
CRE: GHOUL     LVL: 14  HP: 15  XP:  175
CRE: SPIDHU    LVL: 14  HP: 18  XP:  270
```
```
CRE: KOBCOMM   LVL: 20  HP:  7  XP:   35
CRE: JELLYGR   LVL: 20  HP: 16  XP:   65
CRE: HOBELITE  LVL: 20  HP: 16  XP:   95
CRE: JELLGR    LVL: 20  HP: 25  XP:  275
CRE: WOLFDR    LVL: 20  HP: 33  XP:  650
CRE: OGREBERZ  LVL: 20  HP: 50  XP:  650
```
```
CRE: CARRIO    LVL: 25  HP: 22  XP:  420
CRE: BEARBR    LVL: 25  HP: 41  XP:  420
CRE: WOLFWI    LVL: 25  HP: 45  XP:  975
CRE: ANKHEG    LVL: 25  HP: 52  XP:  975
```
```
CRE: GHAST     LVL: 28  HP: 29  XP:  650
```
```
CRE: GHOULLOR  LVL: 30  HP: 48  XP: 1000
CRE: WOLFVA    LVL: 30  HP: 50  XP: 2000
```
```
CRE: DOPPLE    LVL: 35  HP: 31  XP:  420
CRE: ETTERC    LVL: 35  HP: 40  XP:  650
```
```
CRE: WEREWO    LVL: 40  HP: 35  XP:  420
CRE: SPIDGI    LVL: 40  HP: 35  XP:  450
CRE: BEARCA    LVL: 40  HP: 50  XP:  650
CRE: SPIDWR    LVL: 40  HP: 27  XP: 1400
```
```
CRE: OGREMA    LVL: 50  HP: 41  XP:  650
CRE: SPIDPH    LVL: 50  HP: 44  XP: 1400
CRE: WOLFWEGL  LVL: 50  HP: 51  XP: 1800
CRE: FGOLEM    LVL: 50  HP: 40  XP: 2000
CRE: SPIDSW    LVL: 50  HP: 45  XP: 2000
```
```
CRE: JELLOC    LVL: 60  HP: 41  XP:  270
CRE: JELLMU    LVL: 60  HP: 65  XP: 2000
CRE: JELLYMU   LVL: 60  HP: 65  XP: 2000
```
```
CRE: BATTHO    LVL: 80  HP: 58  XP: 4000
CRE: DOPPGR    LVL: 80  HP: 65  XP: 4000
```
