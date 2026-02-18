# WATCH APP
## Features
* ### Apps
  * **settings app**
    * brighntess
    * battery
    * step counter calibration
  * **step tracker app**
    * step counter + controls
  * **timer/stopwatch** *(WIP)*
    * interval training mode *(WIP)*
    * timer *(WIP)*
    * stopwatch *(WIP)*
  * **pong app** *(WIP)*
    * ping pong
  * **home screen**
    * icons/buttons for apps
  * **lock screen**
    * battey widget
    * mechanical clock layout
    * 

* ### UI
  * **Icons**
  * **Buttons**
  * 

* ### Bluetooth LTE
  * #### coming soon?
  * time sync
  * calendar sync
  * other features?

## Source Code Guide
* ### Screens
  * Register screens in .ino file in the setup as so: <br>
  `static SomeScreen screen(ttgo, mgr);` <br>
  `mgr->registerScreen(ScreenId::Screen, &screen);` <br>
  * ### Screen Manager
    * Switch screens using screen manager, accessible in all screen files as so: `mgr->setScreen(ScreenId::Screen);`
  * ### Icons
    * Add icons by convering them to C style array. Run the `png_to_rgb565_magenta.py` script, provide the input and output paths. This will give you a `.h` file. Include it and refer to the array of pixels as the name of the original png file.
* ### TODO
  * Search `TODO:` to find todos 