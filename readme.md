# IVAOTH ESP VTBD/DMK Bangkok/Don Mueang GSXL2 Configs for ThaiCreations and KT-Designs
Forked from Chatnaphat Chatilalai's config
Distributed under MIT License

too lazy to type thai lah

NOTAM KT-Designs is WIP

Changes summarized:
-Changed Gate 11 to Gate 10 
-VDGS all jetway'ed gates, and parking position was setted using A333 as a ref, since GSX told us that it can calculate appropriate parking position for other jets using only one given.
-AFCAD Rework
    -Internal GPS Approach procedure (only approach, no STAR)
    -Navaids repositioned per published AIP Thailand
    -Runway lights reworked.

-including iniBuild's Dynamic light for VTBD


installation
1. given the download package (or `git -clone`, if you prefer.), you'd see 3 follders, `iniBuilds DL effect Redist`, `ThaiCreations` and `KT-Designs`
2. Inside `iniBuilds DL effect Redist`, throw the `effect` folder you see inside into your `simroot` folder (where you install your sim and contains the simulator exe)
3. ask yourself do you use KT-Designs or ThaiCreations rendition of DMK, then navigate into said folder given in the package 
4. inside both of these folders there are bunch of `.bgl` files ,a `.ini` config and backup folder, just throw them into where you install the scenery -- and must be the scenery container itself
    (like `addon scenery\KTD_VTBD\scenery`, you should see bunch of BGLs there) Replace them all if asked.
5. Done.. 

tl;dr ESP is just a base software to build FSX/P3D and its easier to call.