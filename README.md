# EmpireHUD
Hitsume's MSDP GUI for EmpireMUD 2.9+ and MUSHclient 4.94

Installation instructions:
1) Clone this repository into your MUSHclient folder.
2) Run MUSHclient.
3) Open the Plugins menu (File -> Plugins, or Ctrl+Shift+P).
4) Click Add...
5) Navigate to and select EmpireMUD_GUI.xml.
6) If you're already connected to EmpireMUD, reconnect to force MSDP to renegotiate.
It should now be working!
Optionally, if you're having trouble navigating indoor areas, after enabling EmpireHUD, you can try also
enabling ATCP_Mapper_Test.xml - this is a version of MUSHclient's default ATCP automapper hacked together
to get its information from the MSDP variables received by EmpireHUD instead. It seems to be somewhat
unreliable, especially in outdoor areas, however.

If you put the folder in a different place and are getting spammed with notes, you can change where the plugin will
search for images in the variables near the top of the XML file (look for 'path = "EmpireHUD"').
