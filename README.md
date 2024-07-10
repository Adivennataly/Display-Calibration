## Display Calibration 
 Enhance Display Color Saturation for Universal Android Devices.

 this module using SurfaceFlinger services
 

 service running :
  - service call SurfaceFlinger 1023 i32 0
  - service call SurfaceFlinger 1022 f 1.25
 
 properties :
  - persist.sys.sf.native_mode 0
  - persist.sys.sf.color_saturation 1.25

 *default value 1.0, maximum value 1.5 (using 1.25)

## Requirement
 this is module so install using Magisk app.

 *does not cause softbrick or bootloop.

## Tested on
  - Android 12 MIUI 13
  - Android 13 MIUI 14
