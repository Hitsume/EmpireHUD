# EmpireHUD
Hitsume's MSDP GUI for EmpireMUD 2.9+ and MUSHclient 4.94

Installation instructions:
1) Clone this repository into your MUSHclient folder, or download the zip and place its contents into a folder named EmpireHUD, in your MUSHclient folder.
2) Run MUSHclient.
3) Open the Plugins menu (File -> Plugins, or Ctrl+Shift+P).
4) Click Add...
5) Navigate to and select EmpireMUD_GUI.xml.
6) If you're already connected to EmpireMUD, reconnect to force MSDP to renegotiate.
It should now be working!
Optional:
7) Type "gui downloadmap" to acquire a copy of the graphical world map from empiremud.net (which can then be viewed in the score window with "gui config map on").

Optionally, if you're having trouble navigating indoor areas, after enabling EmpireHUD, you can try also
enabling ATCP_Mapper_Test.xml - this is a version of MUSHclient's default ATCP automapper hacked together
to get its information from the MSDP variables received by EmpireHUD instead. It seems to be somewhat
unreliable, especially in outdoor areas, however.

Usage instructions can be viewed using the 'gui' alias.

If you put the folder in a different place and are getting spammed with notes, you can change where the plugin will
search for images in the variables near the top of the XML file (look for 'path = "EmpireHUD"').

If you don't want to download the standard EmpireMUD map, you can either
1) Download your map of choice manually and place it in the EmpireHUD folder, or
2) Change the URL near the top of the EmpireHUD xml.

Screenshot showing recommended location (Windows 7): http://puu.sh/loHlT/e4867f77aa.png
