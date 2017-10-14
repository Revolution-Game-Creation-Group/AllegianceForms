<p align="center">
<img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/header_logo.png" />
<br/>
<a href="https://ci.appveyor.com/project/aarmo/allegianceforms"><img src="https://ci.appveyor.com/api/projects/status/6xvt3vn0cev4iupc?svg=true"/></a>
<a href="https://github.com/aarmo/AllegianceForms/releases"><img src="https://img.shields.io/badge/release-v0.3%20alpha-green.svg"/></a>
<a href="https://github.com/aarmo/AllegianceForms/projects/1"><img src="https://img.shields.io/badge/release-v1.0%20alpha-yellow.svg"/></a>
<a href="https://github.com/aarmo/AllegianceForms/issues"><img src="https://img.shields.io/github/issues/aarmo/AllegianceForms.svg"/></a>
<img src="https://raw.githubusercontent.com/aarmo/AllegianceForms/master/Doc/Images/contributions-welcome-brightgreen.png"/>
<a href="https://raw.githubusercontent.com/aarmo/AllegianceForms/master/LICENSE"><img src="https://img.shields.io/badge/license-AGPL-brightgreen.svg"/></a>
</p>

Overview
------
A 2D strategy game inspired by Microsoft's space combat game: Allegiance.

Made for the Free Allegiance community: http://www.freeallegiance.org/

- Allegiance was originally released in March 2000.
- It is now Open Source: https://github.com/FreeAllegiance/Allegiance
- And available free on <a href="http://store.steampowered.com/app/700480/Microsoft_Allegiance/">Steam</a>!

[Screenshots](#screenshots)&nbsp;&nbsp;&nbsp;[Controls](#controls)&nbsp;&nbsp;&nbsp;[Credits](#credits)&nbsp;&nbsp;&nbsp;[Dependancies](#dependancies)

Features
------
- Customisable [Game Settings & Factions](#customise-the-game)
- Commander AI
- Multiple [Maps](#maps), [Map Editor](#map-editor) & [Tech Paths](#tech-tree)
- Miners, Constructors, Scouts, Fighters, Interceptors, Bombers, Gunships, Stealth Fighters, Stealth Bombers, Fighter Bombers, Troop Transports, Towers, Minefields and Capital Ships!

![alt text][ships]
<br/>
![alt text][capships]

Screenshots
------
### Main Menu
![alt text][menu]

### Explore the map
![alt text][explore]
- Discover wormholes to other sectors
- Find your enemy's bases and miners

### Defend your miners & constructors
![alt text][defend]
- Miners collect resources from *Helium* asteroids: <img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/Rocks/helium_1.png" width="30"/>

### Build bases & expand
![alt text][expand]
- Outpost, Refinery, Starbase and Shipyard constructors require *Standard* asteroids: <img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/Rocks/rock_2.png" width="30"/>
- Supremacy constructors require *Carbon* asteroids: <img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/Rocks/carbon_1.png" width="30"/>
- Tactical constructors require *Silicon* asteroids: <img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/Rocks/silicon_2.png" width="30"/>
- Expansion constructors require *Uranium* asteroids: <img src="https://github.com/aarmo/AllegianceForms/raw/master/AllegianceForms/Art/Rocks/uranium_3.png" width="30"/>
- Tower constructors require *No* asteroids.

### Upgrade your tech & battle the enemy
![alt text][tech]
![alt text][battle]
![alt text][gameover]

### Customise the Game
![alt text][custom]
![alt text][faction]

[Overview](#overview)

Controls
------
### Selection
Key	| Description
--- | --- 
**Left Click** & **Drag** | Selects units and bases.
**Double Click** | Select all units of the same type in sector.
**Shift** | Hold to add units/bases to the current selection.

### General Commands
Key	| Description
--- | ---
**Control+(0-9)** | Set sector preset 0-9.
**(0-9)** | View sector preset 0-9.
**Space** | Switch between the sector of the last alert.
**F3** | Show/Hide the Minimap window.
**F5** | Show/Hide the Research/Construction window.
**F6** | Show/Hide the Pilot List window.
**F12** | Show/Hide the AI Debug window.
**`** | Show/Hide the Quick Command menu.

### Base Commands
Key	| Description
--- | ---
**Right Click** | Sets a new *Default Location* for a base.
**S** | Launch a *Scout*.
**F** | Launch a *Fighter*.
**I** | Launch an *Interceptor*.
**B** | Launch a *Bomber*.
**G** | Launch a *Gunship*.
**T** | Launch a *Stealth Fighter*.
**O** | Launch a *Steath Bomber*.
**X** | Launch a *Fighter Bomber*.
**P** | Launch a *Troop Transport*.

### Ship Commands
Key	| Description
--- | ---
**Right Click** | Orders the selected unit(s) to *Attack Move*/*Dock*/*Capture*.
**Shift** | Hold to queue up additional orders.
**Control** | Hold to see the scan range of the selected ships.
**A** | Orders the selected unit(s) to *Attack Move*.
**S** | Orders the selected unit(s) to *Stop*.
**D** | Orders the selected unit(s) to *Dock* at the nearest friendly base.
**R** | Orders the selected unit(s) to repeatedly *Patrol* between these positions.
**E** | Orders the selected miners(s) to *Mine* around this position.
**B** | Orders a selected constructor to *Build* near this position.
**C** | Orders the selected troop transports to *Capture* an enemy base.

[Overview](#overview)

Maps
------
Name | Image | Teams
--- | --- | ---
Across4 | ![alt text][mapacross4] | 2 / 4
Brawl2 | ![alt text][mapbrawl2] | 2
Cross2 | ![alt text][mapcross2] | 2
Cross3 | ![alt text][mapcross3] | 3
Cross4 | ![alt text][mapcross4] | 2 / 4
DoubleRing2 | ![alt text][mapdoublering2] | 2
DoubleRing3 | ![alt text][mapdoublering3] | 3
DoubleRing4 | ![alt text][mapdoublering4] | 2 / 4
Grid2 | ![alt text][mapgrid2] | 2
HiHigher2 | ![alt text][maphihigher2] | 2
HiLo2 | ![alt text][maphilo2] | 2
NerveHigh2 | ![alt text][mapnervehigh2] | 2
NerveHigh3 | ![alt text][mapnervehigh3] | 3
NerveHigh4 | ![alt text][mapnervehigh4] | 2 / 4
NerveLow2 | ![alt text][mapnervelow2] | 2
NerveLow3 | ![alt text][mapnervelow3] | 3
NerveLow4 | ![alt text][mapnervelow4] | 2 / 4
PinWheel2 | ![alt text][mappinwheel2] | 2
PinWheel3 | ![alt text][mappinwheel3] | 3
PinWheel4 | ![alt text][mappinwheel4] | 2 / 4
QuadClose2 | ![alt text][mapquadclose2] | 2
QuadClose3 | ![alt text][mapquadclose3] | 3
QuadClose4 | ![alt text][mapquadclose4] | 2 / 4
SingleRing2 | ![alt text][mapsinglering2] | 2
SingleRing3 | ![alt text][mapsinglering3] | 3
SingleRing4 | ![alt text][mapsinglering4] | 2 / 4
Spine2 | ![alt text][mapspine2] | 2
Spine3 | ![alt text][mapspine3] | 3
Spine4 | ![alt text][mapspine4] | 2 / 4
Star2 | ![alt text][mapstar2] | 2
TriClose2 | ![alt text][maptriclose2] | 2
TriClose3 | ![alt text][maptriclose3] | 3
TriClose4 | ![alt text][maptriclose4] | 2 / 4
Amber2 | ![alt text][mapamber2] | 2
Constellation2 | ![alt text][mapconstellation2] | 2
Limited2 | ![alt text][maplimited2] | 2
Mica2 | ![alt text][mapmica2] | 2
Pyrite2 | ![alt text][mappyrite2] | 2
Schist2 | ![alt text][mapschist2] | 2
Serpentine2 | ![alt text][mapserpentine2] | 2
Xenon2 | ![alt text][mapxenon2] | 2

[Overview](#overview)

Map Editor
------
![alt text][mapeditor]

### Editor Commands
Key	| Description
--- | ---
**Control+Left Click** | Places a new sector.
**Left Click** | Selects a sector.
**W**,**A**,**S**,**D** | Moves the selected sector up/left/down/right.
**Delete** | Removes the selected sector.
**Shift+Left Click** | Places a wormhole between sectors.
**(1-4)** | Toggles a starting sector for team 1-4.

[Overview](#overview)

Tech Tree
------
![alt text][techtree]

[Overview](#overview)

Credits
------
Item | Source
--- | ---
**Icons** | Free Allegiance: http://www.freeallegiance.org/FAW/index.php/DN_minimap_icons
**Original Rocks** | Hansjörg Malthaner: http://opengameart.org/users/varkalandar
**Bubble Explosion** | Tião Ferreira: http://opengameart.org/users/tiao-ferreira
**Sounds** | Microsoft's Allegiance: http://www.freeallegiance.org

[Overview](#overview)

Dependancies
------
Library | Source
--- | ---
**IrrKlang** | [![Irrklang](http://www.ambiera.com/irrklang/images/irrklang_link_small.png)](http://www.ambiera.com/irrklang/index.html)

[Overview](#overview)

Bonus Game
------
### Lucky Dogfight
![alt text][bonus]

[(Rock Paper Scissors Lizard Spock)](http://www.samkass.com/theories/RPSSL.html)

[ships]: /Doc/Images/Ships.png "Ship Types"
[capships]: /Doc/Images/CapShips.png "Capital Ships"
[menu]: /Doc/Screenshots/MainMenu.png "Main Menu"
[explore]: /Doc/Screenshots/03a_Gameplay01.png "Explore"
[defend]: /Doc/Screenshots/03a_Gameplay02.png "Defend"
[expand]: /Doc/Screenshots/03a_Gameplay03.png "Expand"
[tech]: /Doc/Screenshots/03a_Gameplay05.png "Upgrade"
[battle]: /Doc/Screenshots/03a_Gameplay06.png "Battle"
[gameover]: /Doc/Screenshots/03a_GameOver.png "Game Over"
[custom]: /Doc/Screenshots/CustomSettings.png "Custom Settings"
[faction]: /Doc/Screenshots/FactionDetails.png "Custom Factions"
[bonus]: /Doc/Screenshots/03a_Bonus.png "Dogfight"
[techtree]: /Doc/Images/AllegianceForms-TechTree.png "Tech Tree"
[mapeditor]: /Doc/Screenshots/MapDesigner.png "Map Editor"

[mapacross4]: /AllegianceForms/Data/Maps/Across4.png "Across4"
[mapbrawl2]: /AllegianceForms/Data/Maps/Brawl2.png "Brawl2"
[mapcross2]: /AllegianceForms/Data/Maps/Cross2.png "Cross2"
[mapcross3]: /AllegianceForms/Data/Maps/Cross3.png "Cross3"
[mapcross4]: /AllegianceForms/Data/Maps/Cross4.png "Cross4"
[mapdoublering2]: /AllegianceForms/Data/Maps/DoubleRing2.png "DoubleRing2"
[mapdoublering3]: /AllegianceForms/Data/Maps/DoubleRing3.png "DoubleRing3"
[mapdoublering4]: /AllegianceForms/Data/Maps/DoubleRing4.png "DoubleRing4"
[mapgrid2]: /AllegianceForms/Data/Maps/Grid2.png "Grid2"
[maphihigher2]: /AllegianceForms/Data/Maps/HiHigher2.png "HiHigher2"
[maphilo2]: /AllegianceForms/Data/Maps/HiLo2.png "HiLo2"
[mapnervehigh2]: /AllegianceForms/Data/Maps/NerveHigh2.png "NerveHigh2"
[mapnervehigh3]: /AllegianceForms/Data/Maps/NerveHigh3.png "NerveHigh3"
[mapnervehigh4]: /AllegianceForms/Data/Maps/NerveHigh4.png "NerveHigh4"
[mapnervelow2]: /AllegianceForms/Data/Maps/NerveLow2.png "NerveLow2"
[mapnervelow3]: /AllegianceForms/Data/Maps/NerveLow3.png "NerveLow3"
[mapnervelow4]: /AllegianceForms/Data/Maps/NerveLow4.png "NerveLow4"
[mappinwheel2]: /AllegianceForms/Data/Maps/PinWheel2.png "PinWheel2"
[mappinwheel3]: /AllegianceForms/Data/Maps/PinWheel3.png "PinWheel3"
[mappinwheel4]: /AllegianceForms/Data/Maps/PinWheel4.png "PinWheel4"
[mapquadclose2]: /AllegianceForms/Data/Maps/QuadClose2.png "QuadClose2"
[mapquadclose3]: /AllegianceForms/Data/Maps/QuadClose3.png "QuadClose3"
[mapquadclose4]: /AllegianceForms/Data/Maps/QuadClose4.png "QuadClose4"
[mapsinglering2]: /AllegianceForms/Data/Maps/SingleRing2.png "SingleRing2"
[mapsinglering3]: /AllegianceForms/Data/Maps/SingleRing3.png "SingleRing3"
[mapsinglering4]: /AllegianceForms/Data/Maps/SingleRing4.png "SingleRing4"
[mapspine2]: /AllegianceForms/Data/Maps/Spine2.png "Spine2"
[mapspine3]: /AllegianceForms/Data/Maps/Spine3.png "Spine3"
[mapspine4]: /AllegianceForms/Data/Maps/Spine4.png "Spine4"
[mapstar2]: /AllegianceForms/Data/Maps/Star2.png "Star2"
[maptriclose2]: /AllegianceForms/Data/Maps/TriClose2.png "TriClose2"
[maptriclose3]: /AllegianceForms/Data/Maps/TriClose3.png "TriClose3"
[maptriclose4]: /AllegianceForms/Data/Maps/TriClose4.png "TriClose4"

[mapamber2]: /AllegianceForms/Data/Maps/Amber2.png "Amber2"
[mapconstellation2]: /AllegianceForms/Data/Maps/Constellation2.png "Constellation2"
[maplimited2]: /AllegianceForms/Data/Maps/Limited2.png "Limited2"
[mapmica2]: /AllegianceForms/Data/Maps/Mica2.png "Mica2"
[mappyrite2]: /AllegianceForms/Data/Maps/Pyrite2.png "Pyrite2"
[mapschist2]: /AllegianceForms/Data/Maps/Schist2.png "Schist2"
[mapserpentine2]: /AllegianceForms/Data/Maps/Serpentine2.png "Serpentine2"
[mapxenon2]: /AllegianceForms/Data/Maps/Xenon2.png "Xenon2"
