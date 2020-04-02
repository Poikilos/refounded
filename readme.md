# refounded
This project has been in the planning stage for a long time, but may
become an engine that runs JASS2, a language that is usually called
JASS (which is actually the name of the first version of the language).

See the "JASS projects" sections below for more information.

JASS2 could be considered a substandard and deprecated language:
- https://sc2mapster.gamepedia.com/Language_Overview
- https://github.com/fullmetal-a/cjass2lua

However, many full games are written in JASS2, though they are
unfortunately called "maps" due to the way they were used in
Warcraft III's online "Custom Maps" system. Some full games include:
- DoTA "Defense of the Ancients" and many DoTA clones and other tower
  offense games.
  - DoTA led to DoTA 2 and League of Legends.
- Hardcore/survival games (games with detailed gameplay and character
  and world attributes) such as [Bug Evolution](https://www.epicwar.com/maps/4043/), [Ice Troll Tribe
  Wars](https://www.epicwar.com/maps/19469/), Real Life (and easier
  versions such as [Real Life [for Morons](https://www.epicwar.com/maps/1252/) and
  [Spellcraft](https://www.epicwar.com/maps/487/)
- Hero arenas such as [Angel Arena X](https://www.epicwar.com/maps/8346/)
  [MonstAr.Arena](https://www.epicwar.com/maps/139667/)
- OpenRPG and other large RPGs such as [Fantasy
  Life](https://www.epicwar.com/maps/91725/), [Mystica
  ORPG](https://www.epicwar.com/maps/7577/), [Legends Open RPG](https://www.epicwar.com/maps/130439/) and [Ragnarok RPG](https://www.epicwar.com/maps/80733/)
- Single-goal "party games" such as Assassins,
  [Pyramid Escape](https://www.epicwar.com/maps/165011/) (and other
  "Escape" games), [Kodo Tag](https://www.epicwar.com/maps/103272/)
  [Missile War](https://www.epicwar.com/maps/58603/), [I
  Wolves vs Sheep (and other "vs Sheep" games),
  [Vampirism](https://www.epicwar.com/maps/51266/).
- Tower Defense (and various variations, which seem to have spawned or
  popularized the tower defense genre itself).
- Many clone games, and others:
  [Maps on Epic War sorted by
  rating](https://www.epicwar.com/maps/?order=desc&sort=rating&page=1)

Be aware that using your "maps" (full games) on Warcraft 3: Reforged
transfers all applicable rights to Blizzard as per the Terms of Service!


## Related projects
- jass2 (MIT Licensed) "Jass2 interpreter for exercise purpose"


## JASS projects with license issues
(These projects have licenses that differ from MIT, so changing
this project to match a different license may be the best way forward.)
- JASS Tools (sourceforge project)
  https://sourceforge.net/projects/jass/ is a project that contains some
  "tools for parsing and analyzing the JASS scripting language, which
  used for scripting Maps and AI files in Blizzard Entertainment's (R)
  Warcraft III (R)," notably:
  - pjass (BSD license)
    https://sourceforge.net/projects/jass/files/a%20pjass/
    "currently the best JASS syntax checker" according to
    http://jass.sourceforge.net/ (October 26, 2005).
    "To test this program:
    `pjass common.j common.ai Blizzard.j`"


### JASS projects with incompatible functions
(These projects may be too far from the design goals to become
dependencies.)
- cjass2lua
  - This translator does not allow inheritance, classes, structures,
    scopes, modules, preprocessor directives, cJass `for` loops, or
    macros ("Macroses are translated into global variables" [sic]).
    Also note that Lua array indices start at 1.
  - https://github.com/fullmetal-a/cjass2lua
- c-jasshelper (ZLib/PNG license - OSI approved)
  https://sourceforge.net/projects/c-jasshelper/
  "A proof of concept vJass compiler, vJass is an extension to the Jass
  syntax enabling a bunch of crazy things like libraries, structs and
  textmacros. Also adds the zinc scripting language."
  Compile vJass, a meta language (or something) for JASS.
- JASSEdit (GPLv2) https://sourceforge.net/projects/jassedit/
  "JASSEdit is an editor for the WarCraft 3 WorldEdit Scripting Language
  JASS" with code completion (with function documentation), syntax
  highlighting, multiple script loading, and syntax checking.


## JASS projects without licenses
- pjass-chs
  "A lightweight and fast Jass2 parser for bison/yacc"
  - This could be ported to Python and use PLY (Python Lex-Yacc).
  - [There is no permission to use the
    code](https://github.com/actboy168/pjass-chs/issues/1)
