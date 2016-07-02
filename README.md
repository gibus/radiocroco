# radiocroco
Simple GUI and command line script to listen to Radio Croco, free radio from Rennes (France), broadcasted on https://radiocroco.info.

No need to launch browser to simply listen to Radio Croco, just launch 'radiocroco' to open up a simple dialog window with Play/Stop button and a fancy visualization window displaying psychedelic drawings in reaction to music (based on goom).

The GUI version comes in two flavours: default one is built on Gtk2, 'radiocroco-wx' uses wxWidgets. Both are supposed to run on major operating systems, but only have only been tested on GNU/Linux. Choose the flavour best adapted to your system... and  to your taste.

You can also run 'radiocroco-console' from a terminal for a console version.

Since July, 1st, 2016, broadcast from https://radiocroco.info (instead of mixlr).

Dependencies (for both GUI and console versions):
* perl
* gstreamer-tools
* gstreamer0.10-plugins-good

Dependencies for Gtk2 GUI version
* libglib-perl
* libgstreamer-perl
* libgstreamer-interfaces-perl
* libgtk2-perl

Dependencies for wxWidgets GUI version
* libwx-perl
