# EmpireHUD
Hitsume's MSDP GUI for EmpireMUD 2.9+ and MUSHclient 4.94+

###Installation instructions:

1) Clone this repository, or download it as a zip.

2) Run MUSHclient.

3) Open the Plugins menu (File -> Plugins, or Ctrl+Shift+P).

4) Click Add...

5) Navigate to and select EmpireMUD_GUI.xml.

6) If you're already connected to EmpireMUD, reconnect to force MSDP to renegotiate.

It should now be working! Optionally:

7) Type "gui downloadmap" to acquire a copy of the graphical world map from empiremud.net. It can then be viewed in the score window by right-clicking Score / Map and selecting "Show map (instead of score)".

###Other info:

Optionally, if you're having trouble navigating indoor areas, after enabling EmpireHUD, you can try also
enabling ATCP_Mapper_Test.xml - this is a version of MUSHclient's default ATCP automapper hacked together
to get its information from the MSDP variables received by EmpireHUD instead. It seems to be somewhat
unreliable, especially in outdoor areas, however.

Usage instructions can be viewed using the 'gui' alias.

If you don't want to download the standard EmpireMUD map, you can either:

1) Download your map of choice manually and place it in the EmpireHUD folder (it should be named WorldName-map.png, and the political map should be named WorldName-map-political.png, where WorldName is the name of your world file).

2) Change the URL near the top of the EmpireHUD xml (or use the "gui mapurl main/alt url" command to change it for a single session), then use "gui downloadmap".

Note for older users: The installation location should no longer matter (though the plugin may not be able to download the map if it's in Program Files).
