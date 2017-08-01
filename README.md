# Marlin-EasyConfig
Marlin 3D Printer Firmware with Easy Config

                  TEVO TARANTULA EASY CONFIG 
                   terryb.print3d@gmail.com

     This is an attempt to create a simple configuration for as many
  different Tevo Tarantula variants as possible.  This will always be
  a work in progress. Email me if you have any questions, suggestions,
  or if you encounter problems when using Easy Config.

     This is a Marlin 1.1.x configuration file. I will update this as
  new versions of Marlin are released.

  NOTE: Sanity check should still work and should not show any errors.
    Please report any errors.  Thank you.

Users usually don't know what settings are related and end up frustrated.  My goal is to create a small section in
Configuration.h with the few #defines a new user needs to set and all the related settings are done by preprocessor
directives in Configuration.h.

This will work specifically for the Tevo Tarantula and only works because I know this printer and the options that
it comes with.  This should help beginners get up and running in the shortest amount of time after finishing
their build. 

Nothing in the Marlin code has been changed. The only thing I have modified here is Configuration.h so you should be 
able to download the official Marlin distribution, drop this Configuration.h file into the Marlin directory and compile.

As of this post, the version I have tested this with is Marlin 1.1.x.  Specifically 1.1.4.  I will update as new 
versions of Marlin are released.  

My Tevo Tarantula has a large bed, BLTouch sensor, and dual extruder.  This allowed me to test for the small bed, single
extruder, with no bed leveling probe.  I previously also used the SN04 inductive probe and I incorporated that configuration
into this.

Thank you to the Marlin team for such an awesome piece of software. Your contribution to the 3D printing community is
invaluable.  

Below is the list of #defines in the section of Configuration.h you must fill in.  Once you have done that, compile and upload to your Tevo Tarantula and you should be ready for your first print.  I will add explanations of each setting here when I get a chance.

//#define STOCK_MOTHERBOARD
//#define DUAL_EXTRUDER
//#define LARGE_BED
//#define BLTOUCH
//#define SN04
//#define SENSOR_LEFT_OF_NOZZLE      10
//#define SENSOR_RIGHT_OF_NOZZLE     10
//#define SENSOR_BEHIND_NOZZLE       10
//#define SENSOR_IN_FRONT_OF_NOZZLE  10
//#define Y_MOTOR_ON_RIGHT

