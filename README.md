
These [Cheat Engine](http://cheatengine.org/) table files are for Sub Rosa alpha 32.

Work in progress.

# Server notes

This time team spawns and extended commands are a single script called "SRU mod".

SRU mod is currently only meant to be working under game mode 6

and includes following custom admin commands:

```
 /car [id], [color], [player]
 /arm [id], [mags], [player]
 
 /fset team                - set spawn location to your current position
 /fpos team, x, y, z       - set spawn location to specified point
 /fgun id                  - gun to spawn with
 /fmags num                - amount of mags
 /flives num               - how many times people respawn
(teams should be typed as numbers)

 /fs name       - save preset
 /fl name       - load preset
 /flist         - list available presets
(presets are saved in arenas1.bin in the game folder)

 /f0       - disable fire
 /f1       - enable fire
 /rg       - short for /resetgame
 /ready    - force ready up everyone
```

# Client notes


# IDs

```

Teams

0 - Goldmen
1 - Monsota
2 - OXS International
6 - Bots
7 - Spectators

Items

00  0 Auto 5
01  1 AK-47
02  2 AK-47 Magazine
03  3 M-16
04  4 M-16 Magazine
05  5 Magnum
06  6 .45 Bullets
07  7 MP5
08  8 MP5 Magazine
09  9 Uzi
0a 10 Uzi Magazine
0b 11 9mm
0c 12 9mm Magazine
0d 13 Grenade
0e 14 Bandage
0f 15 Briefcase
10 16 Open Briefcase
11 17 Cash
12 18 Cash
13 19 Black disk
14 20 Green disk
15 21 Blue disk
16 22 White disk
17 23 Gold disk
18 24 Red disk
19 25 Cell Phone
1a 26 Key
1b 27 Door
1c 28 Newspaper
1d 29 Burger
1e 30 Desk
1f 31 Lamp
20 32 Pay Phone
21 33 Memo
22 34 Soccer Ball
23 35 Rope


Vehicles

00  0 Town Car
01  1 Town Car 2
02  2 Metro
03  3 Limo
04  4 Turbo
05  5 Turbo S
06  6 Beamer
07  7 Van
08  8 Minivan
09  9 Truck
0a 10 Trailer
0b 11 Heli
0c 12 Train
0d 13 (Train)
0e 14 Hatchback
0f 15 Test

```