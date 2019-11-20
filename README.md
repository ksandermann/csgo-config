# CS:GO config
This repository holds an exemplary config template for CS:GO configs.

## How to use
- Delete (or move for backup purposes) all contents from *Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg*
- Delete (or move for backup purposes) all contents from *...\Steam\userdata\\<YOURSTEAMTRADEID>\730\local\cfg*
- Copy the whole content of this repository to *...\Steam\userdata\<YOURSTEAMTRADEID>\730\local\cfg*

## How it works
CS:GO automatically executes config.cfg on startup. All the settings you change in the game's UI will be written to *config.cfg*. As we do not want the *config.cfg* to be overwritten from any ingame settings, the file is read-only. Therefore, if you want to change any settings, do not change them ingame but rather put them in the config files provided.

An exception for this is the videosettings, which you can simply change ingame as they are placed in a separate config, *video.txt*.

*config.cfg* executes autoexec.cfg, which then executes all the other configs.

## Screensettings
I'm using a 165 hz screen with gsync enabled.
1920x1440 stretched on native wqhd.

## Mousesettings
- 1000 dpi
- 6/11 windows
- win cursor acceleration on
- usb refreshrate 500hz

## Startoptions
CS:GO startoptions (may be outdated):
*-novid +exec autoexec -threads 4 -high -noforcemaccel -noforcemspd -noforcemparms -32bp -tickrate 128*
