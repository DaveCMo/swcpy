---
title: Kubaz Invader (KubazInvader)
category: unit
---

# Kubaz Invader (KubazInvader) — version 1090

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

  * Side: Empire
  * Buildable unit: Yes
  * Type: infantry
  * Armor type: infantry
  * Role: Destroyer
  * Levels available: 1-10
  * Unit capacity: 3
  * Upgrade requirements: 32 data fragments
  * Upgrade time: 0s
  * Shield Health: 0
  * Shield Cooldown: 0s
  * Shield Range: 0

|Level          |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|---------------|------|------|------|------|------|------|------|------|------|------|
|Health         |1350  |1600  |1850  |2100  |2350  |2600  |2850  |3100  |3350  |3600  |
|Damage per shot|2500  |3775  |5050  |6325  |7600  |8875  |10150 |11425 |12700 |13975 |
|Damage*        |4700.0|2545.0|3090.0|3454.0|3818.0|4363.0|4909.0|5272.0|5636.0|6545.0|

* These values are not necessarily accurate and may be inconsistent with other values

## Targeting

  * Target preferences: **Shield (80)**, **Shield generator (80)**, _Storage (60)_, _Ressource generator (60)_, Light vehicle (50), Flying infantry (50), HQ (50), Infantry (50), Droideka (50), Flying vehicle (50), Support troop (50), Other building (50), Heavy vehicle (50), Heavy infantry (50), Turret (40), Vehicle hero (1), Heavy infantry hero (1), Infantry hero (1), Wall (1), Heavy vehicular hero (1), Trap (0)
  * Targeted type: ENEMIES
  * View Range: 12
  * Target preferences strength: 90
  * Retargeting offset: 20
  * Clip retargeting: No
  * Target shield border: No
  * Can shoot over walls: No
  * Self-centered targeting: No

## Recruiting

|Level        |1                                |2                                      |3                                      |4                                      |5                                      |6                                      |7                                      |8                                      |9                                      |10                                      |
|-------------|---------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|----------------------------------------|
|Training cost|1000$                            |1052$                                  |1137$                                  |1242$                                  |1361$                                  |1494$                                  |1638$                                  |1791$                                  |1954$                                  |2125$                                   |
|Training time|2m40s                            |2m48s                                  |3m2s                                   |3m19s                                  |3m38s                                  |3m59s                                  |4m22s                                  |4m47s                                  |5m13s                                  |5m40s                                   |
|Building     |[Barracks 4](empireBarracks.html)|[Research Lab 2](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 10](empireOffenseLab.html)|

## Movement

  * Speed: 45
  * Run speed: 0
  * Run threshold: 0
  * Size: 1x1
  * Flying unit: No
  * Acceleration: 0
  * Crushes walls: No
  * Target locking: No
  * Propensity to go around obstacles: 200

## Attack : KubazInvader

### Basic info

  * Shot count: 2
  * Time between start of clip and first shot: 50ms
  * Time between shots: 200ms
  * Time between last shot and reload: 0s
  * Time between two clips: 2s
  * Salvos per clip: 2
  * Max. Range: 4
  * Min. Range: 0

|Level                       |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|----------------------------|------|------|------|------|------|------|------|------|------|------|
|Damage per shot             |2500  |3775  |5050  |6325  |7600  |8875  |10150 |11425 |12700 |13975 |
|Calculated damage per second|2222  |3355  |4488  |5622  |6755  |7888  |9022  |10155 |11288 |12422 |
|Damage*                     |4700.0|2545.0|3090.0|3454.0|3818.0|4363.0|4909.0|5272.0|5636.0|6545.0|

### Secondary info

  * Gun shooting sequence: 1
  * Salvos per clip: 2
  * Number of cannons: 0
  * Clips period: 2.250s
  * Projectile passes through shields: Yes
  * Projectile deflectable: Yes
  * Projectile speed: 15
  * Projectile is directional: Yes
  * Salvos per gun sequence: 1
  * Cannons shot per gun sequence: 1

### Multipliers

  * HQ: 10%
  * Heavy infantry: 10%
  * Heavy vehicle: 10%
  * Other building: 10%
  * Droideka: 10%
  * Flying infantry: 10%
  * Flying vehicle: 10%
  * Support troop: 10%
  * Heavy infantry hero: 10%
  * Heavy vehicular hero: 10%
  * Infantry hero: 10%
  * Vehicle hero: 10%
  * Infantry: 10%
  * Ressource generator: 60%
  * Shield: 100%
  * Shield generator: 600%
  * Storage: 50%
  * Trap: 0%
  * Turret: 10%
  * Light vehicle: 10%
  * Wall: 50%

### Presentation

These graphical elements shouldn't interfere with gameplay and can be safely ignored.

  * projectilearcs: false
  * projectilehitSpark: fx_blaster_hit_r_sm
  * projectilemuzzleFlash: fx_blaster_flash_r_sm
  * projectilemaxScale: 100
  * projectilespinSpeed: 0

## Presentation stats

These graphical elements shouldn't interfere with gameplay and can be safely ignored.

  * favoriteTargetType: shieldGenerator
  * buffAssetOffset: 
  * eventButtonAction: galaxy
  * gunPosition: 
  * iconCameraPosition: 8.96,11.37,18.33
  * newRotationSpeed: 7854
  * unlockedByEvent: true
  * animationDelay: 0
  * audioDeath: "sfx_death_kubaz_1":50,"sfx_death_kubaz_2":50
  * tooltipHeightOffset: 
  * audioPlacement: "sfx_placement_troop_1":33,"sfx_placement_troop_2":33,"sfx_placement_troop_3":33
  * iconUnlockRotation: 
  * audioImpact: 
  * factoryRotation: 0
  * infoUIType: 
  * factoryScaleFactor: 1
  * eventButtonData: planet1 planet3 planet6 planet8 planet21 planet23
  * unlockPlanet: 
  * deathAnimation: 
  * iconLookatPosition: -0.48,1.32,-0.72
  * iconUnlockScale: 
  * bundleName: kubaz_emp-ani
  * assetName: kubaz_emp-ani
  * audioTrain: 
  * decalSize: 
  * hologramUid: 
  * iconCloseupCameraPosition: 4.16,3.05,10.68
  * eventButtonString: hn_open_galaxy
  * eventFeaturesString: fragment_obtain_gen
  * audioAttack: "sfx_attack_ionblaster_1":25,"sfx_attack_ionblaster_2":25,"sfx_attack_ionblaster_3":25,"sfx_attack_ionblaster_4":25
  * iconCloseupLookatPosition: 0.04,2.7,-0.25
  * upgradeShardUid: shrd_troopKubazInvader
  * rotationSpeed: 7.8539750000000001506350599811412394046783447265625
  * iconUnlockPosition: 
  * shieldAssetName: 

## Uninterpreted stats

  * autoSpawnSpreadingScale: 1
  * projectilestreams: no
  * spawnApplyBuffs: buffPersonalShieldKubaz
  * projectilebullet: fx_blaster_beam_r_sm
  * targetInRangeModifier: 1
  * impactDelay: 250
  * strictCoolDown: false
  * armingDelay: 0
  * maxScale: false
  * autoSpawnRateScale: 1

|Level     |1     |2     |3     |4     |5     |6     |7     |8     |9     |10    |
|----------|------|------|------|------|------|------|------|------|------|------|
|order     |134001|134002|134003|134004|134005|134006|134007|134008|134009|134010|
|pointValue|3.000 |3.600 |4.200 |4.800 |5.400 |6.000 |6.600 |7.200 |7.800 |9.000 |

