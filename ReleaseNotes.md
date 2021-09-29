# Autel Evo 2 - Firmware Release Notes

Documentation highlighting all bug fixes and new features for each firmware release.


----


## Evo II v2 Firmware v2.1.31

<b>Released:</b> 11th July 2021

<b>Filename:</b> [Model-C_WiMax8020_FW_V2.1.31.zip](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v2-firmware-v2131)

<b>New Features:</b>

* Added Panorama intelligent flight - Landscape, Portrait, Wide-angle (with photo stitching capability), and Sphere (w/o photo stitching capability)
* Added NTRIP Network RTK support on EVO II RTK series
* Added FLIR Boson 640 Radiometric sensor support
* Added customizable Home Point option
* Added A/B button flight speed change option (Standard <-> Ludicrous)
* Added EVO II V2 support on V2.1.31


<b>Bug Fixes and Optimizations:</b>

* Optimized No-Fly zone notifications
* Smoother gimbal pitch start and stop adjustment
* Increased the gimbal pitch sensitivity to support super slow movement.
* Standardized the GPS coordinate system (WGS84)

----


## Evo II v1 Firmware v2.7.25

<b>Released:</b> 1st July 2021

<b>Filename:</b> [Model-C_FW_V2.7.25.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v2725)

<b>New Features:</b>

* Added Panorama intelligent flight - Landscape, Portrait, Wide-angle (with photo stitching capability), and Sphere (w/o photo stitching capability)
* Added NTRIP Network RTK support on EVO II RTK series
* Added FLIR Boson 640 Radiometric sensor support
* Added customizable Home Point option
* Added A/B button flight speed change option (Standard <-> Ludicrous)

<b>Bug Fixes and Optimizations:</b>

* Optimized No-Fly zone notifications
* Smoother gimbal pitch start and stop adjustment
* Increased the gimbal pitch sensitivity to support super slow movement.
* Standardized the GPS coordinate system (WGS84)


----


## Evo II v1 Firmware v2.6.22

<b>Released:</b> 19th March 2021

<b>Filename:</b> [Model-C_FW_V2.6.22.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v2622)

<b>New Features:</b>

* Added RAW file format support in Mission flights
* Added Manual exposure settings, Aperture Priority, and Shutter Priority support in AEB mode
* Added Manual exposure mode support in Hyperlapse
* Added quick zoom changes in the Explorer App
* Intelligent Flight and Mission:
* Added cruise mode in Hyperlapse
* Added Orbit Hyperlapse
* Added Mission recording

<b>Bug Fixes and Optimizations:</b>

* Optimized auto focus performance
* Reduced the minimum distance between two waypoints in waypoint mission
* Removed Boat Mode (EVO II can take off from boats during standard flights)
* Fixed the negative altitude issue during the landing sequence
* Fixed the mission upload issue when resuming a mission
* Added an option to RTH when the aircraft disconnects


----


## Evo II v1 Firmware v2.5.18

<b>Released:</b> 22nd December 2020

<b>Filename:</b> [Model-C_FW_V2.5.18.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v2518)

<b>New Features:</b>

* EVO II aircraft activation
* Added Oblique photography mission mode
* Added the option to turn off the LED indicators on front and rear arms
* Added the option for Beta users to roll back the firmware to the latest public released version
* Added radiometric support for infiRay 640T sensor in picture-in-picture mode
* Added cross-hatch feature in Polygon missions
* Users can manually input GPS coordinates in Waypoint missions

<b>Bug Fixes and Optimizations:</b>

* Optimized takeoff button hold time to eliminate accidental activations
* Optimized the IMU calibration diagram display
* Optimized the warning message display times
* Fixed mobile flight logs display error in iOS
* Fixed the EXP setting saving issue in Android
* Fixed English translation errors


----


## Evo II v1 Firmware v2.5.12

<b>Released:</b> 31st October 2020

<b>Filename:</b> [Model-C_FW_V2.5.12.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v2512)

<b>New Features:</b>

* <i>(none)</i>

<b>Bug Fixes and Optimizations:</b>

* Fixed the "Gimbal is not ready" bug on firmware v2.5.11


----


## Evo II v1 Firmware v2.5.11

<b>Released:</b> 21st October 2020

<b>Filename:</b> [Model-C_FW_V2.5.11.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v2511)

<b>New Features:</b>

* Added IMU Calibration
* Added the third axis compass calibration to improve calibration accuracy
* Added InfiRay 640T thermal camera with radiometric support (specific regions only)
* Added Time Lapse in Intelligent Flight Modes.
* Added SD exFAT large file system support (3.5 GB or more)

<b>Bug Fixes and Optimizations:</b>

* Optimized gimbal stability
* Optimized gimbal automatic calibration by adding gyro bias calibration
* Improved the Smart Orbit performance
* Optimized the balance of picture sharpness and noise, color reproduction and the tones in some scenes for both 8K and 6K to improve JPEG image quality
* Changed the default video encoding format to H.265 for videos in 6K and 8K resolutions
* Resolved EXIF data error issue


----


## Evo II v1 Firmware v2.5.0

<b>Released:</b> 4th August 2020

<b>Filename:</b> [Model-C_FW_V2.5.0.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v250)

<b>New Features:</b>

* Added high-altitude visual positioning to ensure the aircraft can return to the visible range of the take-off point safely when GPS signal under interference
* Users are allowed to take off from a non-static surface in Standard Mode
* Increased the maximum altitude of vehicle dynamic track to 99 ft (30 m)
* Added camera exposure mode, ISO, shutter speed adjustment in waypoint, rectangular, and polygon missions

<b>Bug Fixes and Optimizations:</b>

* Reduced the possibility of image transmission signal loss under interference
* Resolved the Return to Home (RTH) deviation issue in some rare occasions
* Smoothed the aircraft position change during dynamic tracking flights
* Optimized the video output for EVO II Pro at 50P/48P/25P/24P fps
* Increased the maximum Orbit radius to 1640 ft (500 m)
* Other minor bug fixes


----


## Evo II v1 Firmware v2.3.3

<b>Released:</b> 6th July 2020

<b>Filename:</b> [Model-C_FW_V2.3.3.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v233)

<b>New Features:</b>

* <i>(none)</i>

<b>Bug Fixes and Optimizations:</b>

* Resolved the Return to Home (RTH) failure issue in some rare occasions during mission flights
* Adjusted the image transmission standard from CE to FCC for users in Thailand


----


## Evo II v1 Firmware v2.3.0

<b>Released:</b> 21st June 2020

<b>Filename:</b> [Model-C_FW_V2.3.0.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v230)

<b>New Features:</b>

* Added Smart Orbit
* Added pilot warnings for temporary no-fly zones
* Added remote control joystick EXP sensitivity adjustment, allowing for fine-tuning of flight control
* Added aircraft sensitivity adjustment for attitude, brake and yaw movement

<b>Bug Fixes and Optimizations:</b>

* Optimized the accurate landing feature
* Adjusted transmission power to FCC standard for users in Taiwan
* Resolved the GPS coordinate bug in DNG format
* Resolved the H.265 10-bit video bug in HDR mode and log color profile
* Other minor bug fixes


----


## Evo II v1 Firmware v2.2.3

<b>Released:</b> 21st May 2020

<b>Filename:</b> [Model-C_FW_V2.2.3.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v223)

<b>New Features:</b>

* Added no-fly zones in China
* Enabled EVO II Pro users to adjust ISO in Shutter Priority and Aperture Priority modes (latest version app is required)
* Enabled 1-2 second strobe function for bottom LED lights (latest version app is required)

<b>Bug Fixes and Optimizations:</b>

* Optimized EVO II Pro color reproduction in daylight conditions
* Optimized EVO II Pro exposure accuracy in Shutter Priority mode
* Optimized EVO II autofocus accuracy at night
* Stabilized gimbal heading control during flight
* Resolved intermittent performance issue with accurate landing function
* Resolved compatibility issue with H.265 video on Apple platform video players
* Fixed other minor bugs


----


## Evo II v1 Firmware v2.2.0

<b>Released:</b> 9th May 2020

<b>Filename:</b> [Model-C_FW_V2.2.0.bin](https://github.com/ping-spike/AutelEvo2Firmware/blob/master/README.md#autel-evo-ii-v1-firmware-v220)

<b>New Features:</b>

* Updated the protection function for the IMU
* Added support for longer, multiple-battery missions (Users can now Resume, Restart, or Edit their previously started missions)
* Added a crossover pattern feature in the rectangular mission
* Added the feature to lock the gimbal when taking photos

<b>Bug Fixes and Optimizations:</b>

* Optimized the image quality of EVO II and EVO Pro
* Optimized the EXP and changed the default setting to 0.2
* Optimized the no-fly zone restrictions
* Bug fixes


----


## Evo II v1 Firmware v2.1.0

<b>Released:</b> 23rd April 2020

<b>Filename:</b> [Model-C_FW_V2.1.0.bin](https://github.com/ping-spike/AutelEvo2Firmware#firmware-v210)

<b>New Features:</b>

* Remote Control compatibility update to support EVO I and EVO II operation
* Supported the visual auto-calibration and added reminder when the visual works abnormal

<b>Bug Fixes and Optimizations:</b>

* Optimized EVO II 8K and AF function
* Fixed gimbal vibration issue when it faces down during the boot-up process
* Fixed other bugs


----


## This repo is provided by and maintained by: [Grey Arrows Drone Club](https://GreyArro.ws/)


----

