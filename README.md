# radiocroco
Simple GUI and command line script to listen to Radio Croco, free radio from Rennes (France), broadcasted on mixlr service.

No need to launch browser on Mixlr website to simply listen to Radio Croco, just launch 'radiocroco' to open up a simple dialog window with Play/Stop button, or run 'radiocroco-console' from a terminal for a console version.

The GUI version comes in two flavours: default one is built on Gtk2, 'radiocroco-wx' uses wxWidgets. Both are supposed to run on major operating systems, but only have only been tested on GNU/Linux. Choose the flavour best adapted to your system... and  to your taste.

Since July, 1st, 2016, broadcast from https://radiocroco.info (instead of mixlr).

Dependencies (for both GUI and console versions):
* perl

Dependencies for Gtk2 GUI version
* libglib-perl
* libgstreamer-perl
* libgtk2-perl
* gstreamer0.10-plugins-good

Dependencies for wxWidgets GUI version
* libwx-perl
* gstreamer0.10-plugins-good
* gstreamer-tools

Dependencies for console version
* mplayer2
