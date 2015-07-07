## flashplayer plugin

The flashplayer plugin is a cross-platform utility than plays animations, videos and sound files in .SWF format. This is a freeze version for Linux systems, refer to [adobe](http://get.adobe.com/flashplayer/) for the original one.

## Quick start

### On Ubuntu (only LTS releases)

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```
   
2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install firefox-flashplugin
   ```

3. Enjoy ☺!

### On other Linux distributions

1. Extract `tar jxf libflashplayer.tar.bz2`

2. Copy the plugin to the mozilla plugin directory `cp libflash*so ~/.mozilla/plugins/`
