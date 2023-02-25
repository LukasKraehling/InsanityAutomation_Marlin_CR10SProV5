## Creality Touch/TFT Screen supported firmware

This branch adds support for the Creality touchscreen machines and was split off from the standard Creality branches due to specific custom changes not found upstream. This includes extensions to the EXTui framework among other smaller tweaks that we have been working towards getting submitted upstream. Machines supported here are :

- [CR10S Pro / V2](https://www.tinymachines3d.com/products/cr-10s-pro-v2-3d-printer?rfsn=3419592.cc302fe)
- [CR10 Max](https://www.tinymachines3d.com/products/creality-cr-10-max-3d-printer?rfsn=3419592.cc302fe)
- [Ender 5 Plus](https://www.tinymachines3d.com/products/ender-5-plus-silent-board-custom-dual-z-3d-printer?rfsn=3419592.cc302fe)
- [Ender 6](https://amzn.to/3JRyOhi)
- [CR-X / Pro](https://www.tinymachines3d.com/products/creality-cr-x-pro-3d-printer-with-dual-extruder-and-bl-touch?rfsn=3419592.cc302fe)
- [CR10 V2 ](https://www.tinymachines3d.com/products/creality-cr-10-v2-3d-printer?rfsn=3419592.cc302fe)
- [CR10 V3 ](https://www.tinymachines3d.com/products/creality-cr-10-v3-plus-3d-printer-with-genuine-e3d-direct-drive-extruder-and-bl-touch?rfsn=3419592.cc302fe)
- [Ender 3 / Pro 4.2.2 and 4.2.7](https://amzn.to/3BRHlxY)
- [Ender 3 V2](https://www.tinymachines3d.com/products/ender-3-v2?rfsn=3419592.cc302fe)
- [Ender 3 Max](https://www.tinymachines3d.com/products/ender-3-max-3d-printer?rfsn=3419592.cc302fe)
- [Ender 5 / Pro 4.2.2 and 4.2.7](https://amzn.to/3gMb2Yu)
- [CR10S5 500mm](https://www.tinymachines3d.com/products/creality-cr-10-s5-3d-printer?rfsn=3419592.cc302fe)
- [CR6 SE](https://www.tinymachines3d.com/products/creality-cr-6-se-3d-printer?rfsn=3419592.cc302fe)
- [CR6 Max](https://www.tinymachines3d.com/products/creality-cr-6-max-3d-printer?rfsn=3419592.cc302fe)
- [CR10 Smart](https://www.tinymachines3d.com/products/creality-cr-10-smart-3d-printer?rfsn=3419592.cc302fe)
- [Ender 7](https://www.tinymachines3d.com/products/ender-7-3d-printer?rfsn=3419592.cc302fe)
- [CR30](https://www.tinymachines3d.com/products/cr-30-infinite-z-belt-3d-printer?rfsn=3419592.cc302fe)
- [Sermoon D1](https://amzn.to/3LXfZeD)
- [CR5 / Pro HT](https://amzn.to/3gWvpBt)
- [Ender 3 S1](https://www.tinymachines3d.com/products/ender-3-s1-3d-printer?rfsn=3419592.cc302fe)
- [Ender 2 Pro](https://www.tinymachines3d.com/products/ender-2-pro-3d-printer?rfsn=3419592.cc302fe)

- CR10S, CR10S4, CR20 and Pro, CR10, CR10Mini, CR2020, Ender 4, Ender 2 - Legacy support
- These configurations exist however due to age and product availability are no longer actively tested

## Coming Soon
- [CR10 Smart Pro](https://www.tinymachines3d.com/products/cr-10-smart-pro-3d-printer?rfsn=3419592.cc302fe)
- [CR200B]()

## Resin machines below from Tiny Machines are listed simply as an additional way to help support the project. If youre considering buying one, please do so through the following links :
 - [Halot One CL-60](https://www.tinymachines3d.com/products/halot-one-cl-60-resin-3d-printer?rfsn=3419592.cc302fe)
 - [LD-002R](https://www.tinymachines3d.com/products/ld-002r-resin-printer?rfsn=3419592.cc302fe)
 - [LD-002H](https://www.tinymachines3d.com/products/ld-002h-resin-3d-printer?rfsn=3419592.cc302fe)
 - [LD-006](https://www.tinymachines3d.com/products/ld-006-resin-3d-printer?rfsn=3419592.cc302fe)
 - [UW-02 Washer](https://www.tinymachines3d.com/products/uw-02-washing-curing-machine?rfsn=3419592.cc302fe)


Ender 3V2 has a dedicated file set. CR10 Smart has a dedicated high resolution screen set. Portrait displays use the CR6/E3 Touch variant and landscape use the combined set.

Screen files are archived with [7-Zip](https://www.7-zip.org/) simply because it came out 1/5 the file size of a zip file. That added up fast!

There is a limitation with Windows systems and path depth so the file names need to be shorter than we would prefer. If you get an error compiling due to the path limit, move the folder to the root of your hard drive. Here is a legend to help decode the files:

- BLT = BLTouch
- BIL = Bilinear Leveling
- UBL - Unified Bed Leveling
- DZ = Dual Z Steppers
- Fil = FilamentRunout
- Slnt = Creality Silent Board
- H = E3D Hemera Extruder
- MC = Mosquito Creality mount
- ME = Mosquito E3D mount
- Melzi Host option disables local SD card to allow more features and buffer for Octoprint control
- NF = Noise filtering for machines with cable extensions - reduces homing accuracy!
- LR = Stock runout replaced with Lerdge
- ZM = BLTouch connected to ZMin port instead of Probe pin 5 connector harness

## Support

This firmware is provided to the public as-is with no warranty or guarantee. It's based on a large open source project and there is no entitlement to support. That said, Tiny Machines 3D customers may obtain
support through their normal support queue. I will provide support to Patreons as I am able. If you require more immediate support and are not a Tiny Machines 3D customer, you may contact them at
support@tinymachines3d.com about purchasing support hours. Aside from this, we are active on many Facebook groups as well as several discord channels and typically help anyone we can when we come across them.

We have now created a dedicated Discord server to handle support and archive relevant guides and instructions. Patreon supporters will get priority assistance.

## We will NOT handle any support requests for any built compiled from upstream code. The display library from here was taken and submitted upstream without consultation or properly tagging authorship of changes. It was kept off the upstream repo as it was explicitly designed as a drop in library before the Extensible UI API methodology was butchered by hybrid applications with direct includes being repeatedly duplicated. We will not now or ever spend the time to chase bugs caused by changes to the API data types made without concern for backwards compatability.

Extensible UI was designed to allow UI code to live standalone long term. If the API was managed and either versioned or functions overloaded, not changed, UI's no longer being actively maintained would not require maintenance by the Marlin team. The intention was any UI set would drop into the Lib folder and just work. This UI has been maintained under that mindset despite the upstream implementations being full of macros requiring direct pointer access to processed variables, making them fundamentally incompatible with the API, however still relying on its event trigger mechanism.

As another reason this was not placed upstream was to eliminate the nead to develop around merge conflicts following previous code theft issues which have cuased most development to now proceed in the dark, the merge upstream was caught by exactly that, merge issues while adding IDEX functionality.

Due to the blatent disregard to intentions and correct attribution, all support Marlin links have been removed from this repo and open PRs closed, and as long as the situation remains, no further work will be submitted upstream.

Shout out to Tom Brazier, as nearly all notable improvements to the Marlin core code since the last release have come from him.

Insanity Automation Discord - https://discord.gg/TKmJ85PyG4

## Primary Notes for DW7.4.7
   - Added IDEX screens
   - Fan adjustment now numeric instead of simple on/off
   - Tap Z offset on adjustment screen to type numeric value
   - Sync to 2.1.2 with LA now on for all builds, Silent specific builds eliminated
   - TODO note prior to building release batches - Primary outstanding bug is upstream issue causing M600 to fail to resume, verified on both DWIN and Standard full graphics displays.

## Primary Notes for DW7.4.6
  - Added Support for the Ender 2 Pro
  - Added support for the Ender 3 S1 thanks to F1rst Layer providing a machine!
  - Added support for the new DACAI screens being used on current production E3V2 and S1 machines
  - Added support for runtime configurable runout sensors matching RRF M591 including type and polarity
  - Moved E3V2/S1 machines to Marlin Display
  - - Due to the ongoing fued between developers and GPL violations involved with both the Pro/Enahnced UI and the Jyers UI, we have decided to support neither and stay away from the conflict as much as possible. The Marlin UI has more configuration functionality and the menus are more adaptive to the configuration of the machine. This is based off of the default Marlin menu system and will be the most stable long term going forward as well. The cosmetics and graphical icons may not be as nice as with the other UI's however we belive the added functionality more than makes up for it.
  - Removed non-touchscreen 8 bit UBL builds due to RAM constraints
  - Removed Pre-Built Melzi / Sanguino files. These are legacy and no longer actively supported. Its recommended to purchase replacement 32bit motherboards for any machine still using it from https://amzn.to/3KdqyI8

## Primary Notes for DW7.4.5
  - Added support for CR10 Smart - Thanks to Tinymachines for providing the machine
  - Revised file size issues causing corrupted screens on DWINOS3/4 displays (Sermoon, E6/7 etc)
  - Added support for enabling / disabling filament runout and power loss recovery on the touchscreen
  - Added LED control for equiped machines
  - Resolved issue redirecting some users to chinese language displays instead of manual move screens
  - Update to upstream current as of 2022-02-04
  - CR6 / E3 Portrait Touchscreen files have an added NextGen dwin set. This supports the new DWIN OS 4 screens that began shipping in december. There are a few cosmetic issues left to resolve, but we decided to add them now anyway so that users who haver that hardware and will require it are not stuck.

## Primary Notes for DW7.4.4
  - Added Feedrate / Accel / Jerk Screens
  - Touchscreen DGUS tools bumped to 8.2
  - - All Portrait displays operate with the same build
  - - Older screens (10S Pro) audio file selection is a bit off, havnt found a way to properly enforce wav file used yet
  - Ender 7 support
  - Sermoon D1 Support
  - - Some users have reported Z clicking that the scripts run in the Leveling screen resolves, so if you hear clicking from the Z stepper when printing, run measuring from the leveling screen after powerup before printing.
  - E3V2 Screens Icon issue fixed thanks to note from Jyers on icon file size limit

## Primary Notes for DW7.4.3

 - PID Messaging Fixed
 - M600 / Advanced pause messaging improved
 - Volume / Brightness numeric entry fixed
 - Bump base to 2.0.9.2
 -- Includes improved UI for the E3V2 with expanded menus submitted by Jyers
 - Add Gcode configuration to disable BLTouch High Speed Mode to allow runtime config to support CRTouch
 -- This one is pending upstream https://github.com/MarlinFirmware/Marlin/pull/22916
 - Untested preliminary support for the Sermoon D1
 -- Preliminary reports say it works aside from the LCD
 -- I do not own one of these, however a local community member has offered to bring his down when im done with the Ender 7
 - CR30 Support Added

## Primary Notes for DW7.4
- Added Screen Calibration Options
-- Standby Brightness
-- Volume
-- Both now saved in EEPROM
-- Screen configuration code based loosely on the work from the CR6 community modified for this screen model
-- Automatic Screen rotation for the Ender 6 (Default is upside-down)
- Manual Mesh Controls for no Probe machines
-- CRX and Ender 6 with no Probe can now use all mesh controls
-- All machines now use the same screen files except for Ender 3 V2 Rotary Dial machines and CR6
- Home button added to 5 point adjustment screen
- Tap mesh values to manually type in a new value - allows for manual adjustment of mesh values
- Additional functions, messaging on pause / filament runout
-- No will no longer cancel print
-- Depending on state, if only option is continue (eg Reheat, Load filament) Any response continues
-- On final Confirm Continue, No will purge more filament and Yes will resume
- Most places temperatures are shown, can now tap them to type in a value to set the temerature
- Updated to Marlin 2.0.9 Base
- CR6 Branches merged in
-- Support for this machine is primarily based on the fork by the [CR6 Community](https://github.com/CR6Community)

## Primary notes for DW7.3
- File browser rewritten to support paging as well as subdirectories
-- New file browser has a limit of a 66 character directory depth. This can be expanded at the cost of more RAM if users find this more limiting.
-- Due to the above, the current recommendation is to try and limit folder depth to 3 subdirectories and keep names short if possible.
- Base bumped to Marlin Bugfix as of 20210418

# Changes for DW7.3.1
- Added SD file refresh button for users with damaged SD Detect Pins
- Modified print finish button action to raise z by 5mm and disable steppers rather than rehome XY
- Solve rounding issue with babystepping below step precision by forcing always round up caused by recent upstream change
- Modified babystepping resolution for fine adjustment to .02mm from .01mm
- Force file pages to reset paging value on entry to screen to prevent incorrect scrolling
- Additional string length buffer safeties

The default build button is now a batch Build All! If you want to build a custom stock 2560 environment, use the env:megaatmega2560 environment.
For SKR 1.3/1.4 boards use the LPC1768/9 environments as usual. For SKR Mini or Creality STM32F1 boards use the standard STM32 environments per vendor.

## About Our Branches

The firmware branches maintained here are made possible by the support of [Tiny Machines 3D](https://www.tinymachines3d.com/?rfsn=3419592.cc302fe) as well as our customer base through our 3D printing Services.
Maintaining and developing these branches takes a significant investment, made up of time and machines. To support continued development, please consider your next 3D Printer related purchase from Tiny Machines 3D
and thank them for supporting open source development. Or, consider us for printing services outside of your machine’s capabilities. Print service requests can be sent to d.menzel@insanityautomation.com and we will
respond typically within 1 working day. If you do not need anything printed or a 3D Printer but still want to contribute, you can support us through [Patreon](https://www.patreon.com/InsanityAutomation).

## Setup

All configuration options intended to be adjusted by end users have been placed in the top section of Configuration.h and have been documented there. There is typically a break line to segregate the standard
configuration below. Anything aside from the upper options is intended for advanced users only.
Please keep in mind when flashing the Creality 32 bit boards with the binary files (.bin) that occasionally they will not accept particular filenames. This is most common with reflashing after an aborted flash. The machine stores the filename it was last flashed with, so renaming the file to something such as firmware.bin or firmware1.bin (anything different than what it is now) will typically resolve any issue with file names.

## Known Issues
 - While auto leveling (measuring) is in progress pressing other buttons on the screen can abort portions of the script depending where it is
 - - The process includes heating the bed before probing, probing then heating the nozzle before moving to Z0.
  - Thanks to Jarrett Wendt for finding that if you are experiencing distorted sounds, and use a Mac, the default Archive Utility on MacOS has been found to be corrupting the files. If you're on a Mac, try unzipping with The Unarchiver or Keka instead.

## Future Goals

For this branch, we still have some active goals open that we plan to continue working on provided there is continued interest in the project.
- CR10 Smart Power controls and network reset pin output to web interface device
- Screens for IS and LA adjustment



## Creality Firmware Branches
  - Most Creality machines [CrealityDwin_2.0](https://github.com/InsanityAutomation/Marlin/tree/CrealityDwin_2.0)
  - CR6 modified from [CR-6 Community](https://github.com/CR6Community) - [Creality CR6](https://github.com/InsanityAutomation/Marlin/tree/CR-6Devel)
## Formbot / Vivedino Firmware Branches
  - Raptor 1/2 Firmware [Raptor_2.0.X](https://github.com/InsanityAutomation/Marlin/tree/Raptor_2.0.X)
  - Trex 2+/3 Firmware [TM_Trex2+_2.0.x](https://github.com/InsanityAutomation/Marlin/tree/TM_Trex2+_2.0.x)
## Mamorubot / HieHa Firmware Branches
  - SX4/SX2 Firmware [TM_SX4_2.0](https://github.com/InsanityAutomation/Marlin/tree/TM_SX4_2.0)
## Other Firmware
  - Raise 3D N2+ (Dual) 2.0 [Raise3D-N2+-Dual](https://github.com/InsanityAutomation/Marlin/tree/Raise3D-N2+-Dual)
  - Evnovo Artillery Sidewinder X1 2.0 [Evnovo X1](https://github.com/InsanityAutomation/Marlin/tree/ArtilleryX1_2.0_Devel)
  - [Anet E16](https://github.com/InsanityAutomation/Marlin/tree/AnetE16V2.0.5.2)
  - Lulzbot with Universal Tools options [Lulzbot](https://github.com/InsanityAutomation/Marlin/tree/LulzbotTestBase)
  - Funmat HT with Graphical Display [Funmat HT](https://github.com/InsanityAutomation/Marlin/tree/FunmatHT)
  - [Modix Big60](https://github.com/InsanityAutomation/Marlin/tree/ModixBig60)
  - Tronxy Chithu Machines [Tronxy](https://github.com/InsanityAutomation/Marlin/tree/TronxyX5SA)



[Marlin Commit History](https://github.com/MarlinFirmware/Marlin/pulls?q=is%3Apr+is%3Aclosed+author%3AInsanityAutomation)

## Marlin
This is just one of many forks of Marlin. We don't try to bury that behind fancy marketting or anything else.

<p align="center"><img src="buildroot/share/pixmaps/logo/marlin-outrun-nf-500.png" height="250" alt="MarlinFirmware's logo" /></p>

<h1 align="center">Marlin 3D Printer Firmware</h1>

<p align="center">
    <a href="/LICENSE"><img alt="GPL-V3.0 License" src="https://img.shields.io/github/license/marlinfirmware/marlin.svg"></a>
</p>

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
