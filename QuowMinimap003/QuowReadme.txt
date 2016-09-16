Quow's Minimap Plugin, for Mushclient
=====================================
You need the entire "maps" folder - place this somewhere sensible, such as a Discworld folder on your computer, or your Mushclient folder.  
There should be 47 .png map files in this folder.

Next place the plugin file (QuowsMinimap.xml) somewhere - again either a Discworld folder, your Mushclient plugins folder, your Desktop, anywhere sensible.

Now you need to configure the plugin file - you can do this with any text editor, including Notepad on windows.  Open Notepad/your text editor, choose;
File->Open
In the file open window, in the bottom right dropdown box where it says "Text Documents (*.txt)", click and select "All Files (*.*)"
Now navigate to, and select, the QuowsMinimap.xml file, and open it.

Scroll down to line 28, you should see;
sQuowMapPath = "D:/Discworld/maps/"

You must change this to the location you places the /maps/ folder - IMPORTANT - you must use FORWARD slashes, not backward slashes!  For example, you might change it to;
sQuowMapPath = "C:/Mushclient/maps/"

IMPORTANT:  Make sure you have the final slash / at the end of "maps"!

Now save the file (File->Save).



Within Mushclient, with the Discworld world/connection loaded in Mushclient, go to the File->Plugins menu, click "Add", locate the QuowMinimap.xml plugin file, and Open it.

You should see a (blacked out) miniwindow appear with the title "Quow's Minimap" - you can drag this window around by left-click-dragging the titlebar.

Type "help minimap" into the mushclient window for instructions.

You should type "minimap setup" to configure your MUD options to work correctly with the plugin.

As you move around, whenever you are somewhere the plugin recognises (major locations, waypoints, hotspots, uniquely named shops etc.), the map should show your position.

I hope you enjoy!

- Quow.