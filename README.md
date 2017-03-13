# Tap-Titans-2-Progress-Bot
A HiroMacro script for Tap Titans game

## Features
 - Auto leveling
 - Autoprestige after X minutes
 - Random Hits
 - Autostart fireblade/midas/crit/sc on full mana
 - Autostart boss fights with individual skills
 - Boss detection (no actions while fighting vs a boss)
 - Autofight ClanQuest every hour
 - Autobuy skills (need a rework at curr state)
 - Autolevel heroes with scroll detection & spam
 - Autostart skills every X minutes
 
## Coming Soon
 - Autostart tournament
 - Multiple ClanBoss Attacks (with dia drain)
 

## Basic Requirements:
 - Android Device or Emulator
 - Resolution 480x800 (you can change it maybe if your device is different)
 - Root for HiroMacro

## Install
 - Download NoxPlayer, MEmu, ...
 - Enable root
 - Set screen size to: 480x800
 - Settings -> SuperUser -> disable notifications
 - Install HiroMacro + Tap Titans 2
 - Insert downloaded script by C+P
 - HiroMacro Settings -> Color Access Method -> ScreenCapture
 - Start HiroMacro Service
 - Start Tap Titans 2
 - Click on volume down to start the script
 - again to stop
 
## Optional for better performance:
 - Set ScreenCapture delay in HiroMakro settings to 0
 - Increase ram to 1500 or more.
 - Increase used cores to 2 or more.


## Settings available:
 - enableFairies: 1|0 (enable if you bought Premium and disable Ads, otherwise the bot stuck with the Ad PopUp)
 - enableSkills: 1|0
 - enableClanQuest 1|0
 - enableHeroes: 1|0
 - enableAutoprestige: 1|0
 - fullManaSkill: 2|3|4|5|6
 - prestigeAfterXMinutes: 1-300
 - intervalCrit: 0-n (set an interval to 1 if you want to use this skill every minute)
 - intervalFireBlade: 0-n
 - intervalMidas: 0-n
 - intervalShadowClone: 0-n
 - intervalHeroes: 0-n
 - runActionsOnStart: 1|0
 - startBossSkill: 0|2|3|4|5|6 (If the boss fight fails, the bot will wait for this skill before the next boss start)
 - startBossSecondarySkill: 0|2|3|4|5|6 (The bot press this skill on boss fight start, but without an readyup check)
 - skillIntensity: 1-n (increase this value if you want more taps on the level up buttons per scroll)
 - checkBossFight: 0|1 (enable this in the late game, bot skipps actions while fighting with the boss)
 - hatchEggs 0|1
 - enableTapping 0|1
