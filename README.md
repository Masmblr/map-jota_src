# Jota - Game Level For Tremulous
![header](meta/header/header.jpg) 

## Overview: A Haunting Station in the Clouds

Jota is a game level by Matthias "Masmblr" Peters for the open source game [_Tremulous_](https://tremulous.net/).

Map Description: 
> Jota, a captivating map, was born during the development of Edge Dark, an expansion for my Tremulous Mod, "Edge." With a layout reminiscent of ATCS, Jota provides players with a sense of familiarity, making it easier to navigate through its intricate design.
> 
> The idea behind Jota's map design was to create an abandoned station suspended in the clouds. Centuries ago, this station was abandoned and left to the passage of time. However, remarkably, it still retains its functionality, albeit now inhabited by eerie and mysterious creatures that have taken over its corridors and chambers.
> 
> The name "Jota" derives from the Greek alphabet, specifically the ninth letter, "Iota" (I, ι). The choice of this name reflects the map's small size, as "Iota" implies something minuscule or tiny in Greek. Despite its small scale, Jota manages to deliver an immersive experience within its compact confines.
> 
> Jota possesses several distinct features. It follows a symmetrical layout, ensuring balanced gameplay for both teams. The map includes two tunnel doors, providing strategic access points, as well as tunnel shafts and vents located above each base and shafts. These architectural elements contribute to the map's dynamic gameplay and tactical possibilities. To enhance the visual experience, Jota incorporates new HD textures.
> 
> The construction of Jota took approximately three weeks.. hope you like it!
 
* * *

## Screenshots:
[<img src="meta/preview_levelshots/17.jpg" width="250"/>](meta/preview_levelshots/17.jpg)
[<img src="meta/preview_levelshots/18.jpg" width="250"/>](meta/preview_levelshots/18.jpg)
[<img src="meta/preview_levelshots/19.jpg" width="250"/>](meta/preview_levelshots/19.jpg)
[<img src="meta/preview_levelshots/20.jpg" width="250"/>](meta/preview_levelshots/20.jpg)
[<img src="meta/preview_levelshots/21.jpg" width="250"/>](meta/preview_levelshots/21.jpg)
[<img src="meta/preview_levelshots/22.jpg" width="250"/>](meta/preview_levelshots/22.jpg)
[<img src="meta/preview_levelshots/1.jpg" width="250"/>](meta/preview_levelshots/1.jpg)
[<img src="meta/preview_levelshots/2.jpg" width="250"/>](meta/preview_levelshots/2.jpg)
[<img src="meta/preview_levelshots/3.jpg" width="250"/>](meta/preview_levelshots/3.jpg)
[<img src="meta/preview_levelshots/4.jpg" width="250"/>](meta/preview_levelshots/4.jpg)
[<img src="meta/preview_levelshots/5.jpg" width="250"/>](meta/preview_levelshots/5.jpg)
[<img src="meta/preview_levelshots/6.jpg" width="250"/>](meta/preview_levelshots/6.jpg)
[<img src="meta/preview_levelshots/7.jpg" width="250"/>](meta/preview_levelshots/7.jpg)
[<img src="meta/preview_levelshots/8.jpg" width="250"/>](meta/preview_levelshots/8.jpg)
[<img src="meta/preview_levelshots/9.jpg" width="250"/>](meta/preview_levelshots/9.jpg)
[<img src="meta/preview_levelshots/10.jpg" width="250"/>](meta/preview_levelshots/10.jpg)
[<img src="meta/preview_levelshots/11.jpg" width="250"/>](meta/preview_levelshots/11.jpg)
[<img src="meta/preview_levelshots/12.jpg" width="250"/>](meta/preview_levelshots/12.jpg)
[<img src="meta/preview_levelshots/13.jpg" width="250"/>](meta/preview_levelshots/13.jpg)
[<img src="meta/preview_levelshots/14.jpg" width="250"/>](meta/preview_levelshots/14.jpg)
[<img src="meta/preview_levelshots/15.jpg" width="250"/>](meta/preview_levelshots/15.jpg)
[<img src="meta/preview_levelshots/16.jpg" width="250"/>](meta/preview_levelshots/16.jpg)
[<img src="meta/preview_levelshots/23.jpg" width="250"/>](meta/preview_levelshots/23.jpg)
[<img src="meta/preview_levelshots/24.jpg" width="250"/>](meta/preview_levelshots/24.jpg)

## Version History:
| Version: | Date:        | Status: |
| ------- | ------------- | ------: |
| 1.0     | 01/06/2015    |  beta   |
| 1.1     | 14/06/2015    | beta    |
| 1.2     | 20/06/2015    | release |

## How-To
**Binary**:
1. Download the release package.
2. Save the *.pk3 file to the following directory: `/%PATH%/Tremulous/base/`.
3. Start the Tremulous game and select "Create Server" with the desired map.

**Source**:
1. Download the [source release](https://github.com/Masmblr/map-Jota_src/releases/) and the [tremulous-common-files](https://github.com/Masmblr/tremulous-map-common/releases/tag/v1.0).
2. Extract the files to the default installation directory. It should look like this:

```
DRIVE:/%PATH%/tremulous/
|   tremulous.exe
|   tremulous.x86
|   ...
+---base
|   |   autogen.cfg
|   |   data-1.1.0.pk3
|   |   map-atcs-1.1.0.pk3
|   |   ...
|   +---env
|   +---maps 
|   +---models 
|   +---scripts
|   +---sounds
|   \---textures
```
1. Download [NetRadiant Level Editor](https://netradiant.gitlab.io/page/download/).
2. Launch NetRadiant and select "Tremulous" as your game setting.
3. Open the '.map' file located in the directory `/%PATH%/tremulous/base/maps` and, from the menu, choose 'Build -> 'Build with final settings.'
4. Start the Tremulous game with `-sv_pure 0 -devmap MAPNAME`. Make sure to replace "MAPNAME" with the actual name of the map you compiled.

## Development Tools:
Photoshop CS6 \
[Audacity](https://www.audacityteam.org/) \
[NetRadiant](https://netradiant.gitlab.io/) \
[Q3Map2](http://q3map2.robotrenegade.com/)

## Related Resources:
Official Tremulous website: https://tremulous.net </br>
NET Radiant Level-Editor: https://netradiant.gitlab.io </br>
Master-Server-List: http://dpmaster.deathmask.net/?game=tremulous </br>
Unofficial successor "Unvanquished": https://unvanquished.net

## Legal Information and Attribution
Some assets may be derivative works or subject to different licenses. Please refer for author and license details. Note that some files may have been modified. Below is a list of files and their legal statuses.

***
env\jota\jota_bk.jpg <sup>[1](#Credit-1)</sup> \
env\jota\jota_dn.jpg <sup>[1](#Credit-1)</sup> \
env\jota\jota_ft.jpg <sup>[1](#Credit-1)</sup> \
env\jota\jota_lf.jpg <sup>[1](#Credit-1)</sup> \
env\jota\jota_rt.jpg <sup>[1](#Credit-1)</sup> \
env\jota\jota_up.jpg <sup>[1](#Credit-1)</sup> \
levelshots\jota.jpg <sup>[1](#Credit-1)</sup> \
maps\jota.map <sup>[1](#Credit-1)</sup> \
scripts\jota.arena <sup>[1](#Credit-1)</sup> \
scripts\jota.particle <sup>[1](#Credit-1)</sup> \
scripts\jota.shader <sup>[1](#Credit-1)</sup> \
scripts\jota.trail <sup>[1](#Credit-1)</sup> \
scripts\shaderlist.txt <sup>[1](#Credit-1)</sup> \
sound\jota\gas.wav <sup>[1](#Credit-1)</sup> \
sound\jota\gereat_01.wav <sup>[1](#Credit-1)</sup> \
sound\jota\propeller_langsam.wav <sup>[1](#Credit-1)</sup> \
sound\jota\propeller_schnell.wav <sup>[1](#Credit-1)</sup> \
sound\jota\pumpen_01.wav <sup>[1](#Credit-1)</sup> \
sound\jota\umgebung.wav <sup>[1](#Credit-1)</sup> \
sound\jota\wind_loop.wav <sup>[1](#Credit-1)</sup> \
sound\jota\wind_loop_2.wav <sup>[1](#Credit-1)</sup> \
textures\jota\decal_1.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\decal_2.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\header_edgedark.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\header_yaltsmapserver.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_01.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_02.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03_blend.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03_blend_blue.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03_blend_red.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03b.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_03r.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_04.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_04_blend.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_05.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_06.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_07.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_08.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_10.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_11.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_12.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_13.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_14.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_14b.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_15.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_16.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_17.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_18.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_19.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_20.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_20_blend.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_21.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_22.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_24.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_25.jpg <sup>[2](#Credit-2)</sup> \
textures\jota\jota_26.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_27.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_28.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_29.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_30.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_31.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_31_b.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_31_blend.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_31_c.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_31c_blend.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_32.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_33.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_34.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_35.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_35_blend.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_36.tga <sup>[1](#Credit-1)</sup> \
textures\jota\jota_37.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_37x.tga <sup>[1](#Credit-1)</sup> \
textures\jota\jota_40_a.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_40_b.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_40_c.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_41.tga <sup>[1](#Credit-1)</sup> \
textures\jota\jota_42d.tga <sup>[1](#Credit-1)</sup> \
textures\jota\jota_43.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_44.tga <sup>[1](#Credit-1)</sup> \
textures\jota\jota_45.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\jota_flare_01.jpg <sup>[1](#Credit-1)</sup> \
textures\jota\sparks.tga <sup>[1](#Credit-1)</sup>
***

### Credit-1

[Matthias "Masmblr" Peters](mailto:masmblr@gmail.com) \
Content: Map, Textures, Shaders \
License: [MIT License](https://opensource.org/license/mit/).
(See "LICENSE" file for more Informations.)

### Credit-2
[Yves Allaire](http://www.evillair.net/) \
Content: eX -Textures \
License: Attribution License

For all other content, their respective licensing rules and other legal provisions apply.

## Special Thanks:
* id Software for Quake3
* Dark Legion Development for Tremulous
* Team Xonotic for NetRadiant 
