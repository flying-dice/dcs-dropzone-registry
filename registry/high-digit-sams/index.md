# HighDigitSAMs

A simple, IC-compliant mod for DCS to add more SAM systems to the game, both modern and historical.

## How to Install

Simply copy the Mods folder into your C:\Username\Saved Games\DCS folder, or use OVGME to install the files there.

## Current features

### SAMP/T Complex

This is the ground version of the Aster series of missiles. These also exist on ships like on the British Type 45 destroyer.
For a battery you need the MGE, ME, one of the radars and of course at least one launcher. The MC is optional but does not add any functionality in DCS.
IRL the MC adds a datalink functionality, akin to the ICC for the MIM-104 Patriot.
One battery can have up to 6 launchers IRL.

#### Radars

There is the ARABEL radar which is most common but has lacking performance for ballistic intercepts
There is also the Ground Fire 300 radar which has greatly increased performance and just much better

#### Missiles

Modeled right now are the Aster 30 Block 1, Block 1NT and Block 2
Block 1 is good up to 20km in altitude and 120km in range
Block 1NT gives it a better seeker and possibly a better booster increasing the altitude coverage to 25km and the range to 150km
Block 2 is completely different and more akin to the US' THAAD. It can intercept targets up to 200km away and up to 70km in altitude
Keep in mind that this has to be modeled within DCS' restrictions so its not entirely accurate to what it could do IRL

### S-300PMU-1 (SA-20A Gargoyle) Complex

This upgraded version of the S-300 added ABM capability and the long range 48N6 missile to the advanced S-300 complex.  
All components labelled as SA-20A in the mission editor.  
Now includes a truck-mounted 30N6 radar, 3D model by ERO.

### S-300PMU-2 (SA-20B Gargoyle) Complex

This incremental upgrade from the S-300PMU-1 features improved ABM capability and increased range.  
All components labelled as SA-20B in the mission editor. 3D models by ERO.

### Polyana-D4M1 C2 Vehicle

This wheeled command vehicle is perfect for Skynet users to use as a node for their IADS.  
3D model by ERO.

### S-300V (SA-12 Gladiator/Giant) Complex (contributed by LetMePickThat)

The S-300V was a tracked, mobile area defense SAM with a particular focus on countering ballistic missiles. It features SARH guidance for the 9M82 anti-ballstic missile, and the 9M83 anti-aircraft.

### S-300VM (SA-23 Gladiator/Giant) Complex (contributed by LetMePickThat)

This upgraded variant of the S-300V features Track-Via-Missile guidance and the extremely capable 9M82M anti-ballstic missile, in addition to the 9M83M missile, all on a tracked chassis.  
All components labelled as SA-23 in the mission editor, complete with custom 3D models created by ERO.

### 9K317 Buk-M1-2 (SA-17 Grizzly) Transporter/Erector/Launcher and Radar, 9A310M1-2

This upgraded Buk TELAR carries a more capable radar, and fires the 9M317 missiles, which is longer-ranged and more agile than the original 9M38 Buk missile.  
This variant has an improved ability to defend itself from anti-radiation missiles. ABM capability and support units coming to the complex soon!

### V-759/5V23 Missile for S-75 (SA-2) Complex

This late-production missile for the SA-2 has an improved warhead, maneuverability and G-tolerance compared to previous versions, and was widely exported in the 1970s.  
Note: This missile is modeled very differently from the default DCS version of the SA-2. Its guidance and maneuverability have been tuned based on documentation to hopefully much better reflect the actual capabilities of this system. Do not expect this missile to miss you if you do not defend properly!  
Add to your SA-2 complex by selecting the launcher for the V-759 in the mission editor.

### V-601P/5V27 Missile for S-125 (SA-3) Complex

This upgraded missile for the SA-3 features a number of improvements to the guidance and rocket motor.  
Note: this version performs much more closely to the historical SA-3 than the DCS version, and as such it is generally much less dangerous to face.  
Add to your SA-3 complex by selecting the launcher for the V-601P in the mission editor.

### HQ-2 Missile

This Chinese-developed copy of the S-75 makes a number of upgrades to its performance, particularly guidance, overload capability and kinematic performance.  
Note: Associated radar systems not included until I can figure out a way to add RWR symbology without breaking IC.  
Add to your SA-2 complex by selecting the HQ-2 launcher in the mission editor, available to China, Iran, and CJTF Red.

### 9K338 Igla-S (SA-24) MANPADS

The 9K338 system features significant kinematic and countermeasure resistance improvements from the previous 9K38 Igla. It fires the 9M342 missile which has an average speed of 650 meters per second.  
Selectable in the mission editor as the SAM SA-24 Igla-S.

### 9K34 Strela-3 (SA-14) MANPADS

The 9K34 system was a major improvement over the previous 9K32 Strela-2, featuring a limited all-aspect engagement capability and improved fusing.  
It saw service around the world from the late 1970s onward.  
Selectable in the mission editor as the SAM SA-14 Strela-3.

### 9K32 and 9K32M Strela-2 (SA-7 and SA-7B) MANPADS

The 9K32 system was the first man-portable SAM system to enter serial production in the Soviet Union, starting in 1970.  
Both versions are rear-aspect only, with the SA-7B featuring an improved seeker, warhead, and rocket motor.  
For mission makers: use Average skill level and face the units away from the expected threat axis, so that they will have the best shot parameters.

# Version history

#### V 2.1.0 2024-07-15 -

Added SAMP/T Block 1, 1NT and 2 with the necessary vehicles (3D models by ERO and zahnatom, Lua by zahnatom)
Added SA-7 and SA-7B by Des-mundo
Incorporated 48N6 guidance improvements by YoloWingPixy - 48N6 variants should guide more like the vanilla 5V55, with a more parabolic arc
Added "12" HARM code for the S-300VM (SA-23) TR - Thanks to YoloWingPixy

#### V 2.0.0 2023-11-04 -

Removed KS-19, Fire Can, S-300PS as they have become obsolete with recent DCS changes  
Fixed IC-compliance issue with DCS 2.9  
Updated SA-20 variants to use ED's updated flight model for the 48N6  
Added support for masted & trailer-mounted 19J6 search radar to SA-20 variants  
Minor changes to S-300V flight models

#### V 1.4.2 2021-04-27 -

Added PDF guide, added 51P6a and 92N6 models  
fixed bug with S-300VM guidance  
updated display names and added short display names for all units increased maximum targets for 92N6 engagement radar (SA-20B) to 36 increased maximum targets for 9S32 engagement radar (SA-23) to 24 updated all S-300P variants to give lock-only warning

#### V 1.4.1 2021-01-30 -

Hotfix for model conflict

#### V 1.4.0 2021-01-27 -

Added S-300PMU-2, S-300V, Gazetchik Decoy by LetMePickThat, including new 3D models by ERO  
Reduced top speed and accuracy of V-759, tweaked PN coefficients.
Includes RWR symbology for SA-12 and now the SA-23 search radars.
Changed SON-9 to use the silkworm 3D model.

#### V 1.3.0 2020-12-13 -

Added SON-9, KS-19 by Hextopia. Added new S-300 3D models by ERO.  
Added SA-10B implementation by LetMePickThat.
Increased 5V55RUD missile performance slightly. Slightly reduced overload limit for V-759 missile.
Restored launch warning for SA-23.  
Added Polyana-D4M1.  
Added improved textures and 3D models for everything.

#### V 1.2.0 2020-10-31 -

Kinematics updates to missiles, added S-300VM, 9K338 and 9K34, added truck mount for 30N6 radar

#### V 1.1.0 2020-10-10 -

Second release, added V-759, V-601P, and HQ missiles/launchers, changed 48N6 guidance to command (no more launch warning)

#### V 1.0.0 2020-10-3 - Initial release
