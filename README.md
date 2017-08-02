# EmpireHUD
Hitsume's MSDP GUI for EmpireMUD b5.9+ and MUSHclient 4.94+

![Preview](/preview.png?raw=true)

### Installation instructions:

1) Clone this repository, or download it as a zip and extract.

2) Run MUSHclient.

3) Open the Plugins menu (File -> Plugins, or Ctrl+Shift+P).

4) Click Add...

5) Navigate to and select EmpireMUD_GUI.xml.

It should now be working! Optionally:

6) Type "gui downloadmap" to acquire a copy of the graphical world map from empiremud.net. It can then be viewed in the score window by right-clicking Score / Map and selecting "Show map (instead of score)".

### Other info:

A list of text commands used by the GUI can be viewed using the 'gui' alias.

Several elements of the GUI can be hovered over for extra information or right clicked for configuration options.

If you don't want to download the standard EmpireMUD map, you can either:

1) Download your map of choice manually and place it in the EmpireHUD folder (it should be named WorldName-map.png, and the political map should be named WorldName-map-political.png, where WorldName is the name of your world file).

2) Change the URL near the top of the EmpireHUD xml (or use the "gui mapurl main/alt url" command to change it for a single session), then use "gui downloadmap".

### Notes for older users:

The installation location should no longer matter (though the plugin may not be able to download the map if it's in Program Files).

ATCP_Mapper_Test.xml was developed with an older version of EmpireMUD and tries to use the MSDP room vnum field to map areas. This variable no longer works for mortals, so the plugin doesn't work.
