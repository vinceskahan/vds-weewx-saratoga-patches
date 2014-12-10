
This are patches to the Saratoga Base-USA.zip tree to add
a new 'WE' (weewx) software type.

It assumes that you are running:
 Saratoga Base-USA.zip as of approximately Dec-08-2014
 my saratoga WE plugin
 the icons of your choosing

and of course 
 weewx version 3.0.1 or later
 and the matching weewx-wd extension

Basic procedure to install is just like any other Saratoga
installation, just with this patching step inserted.

 - extract Base-USA.zip
 - apply each of these patches individually (for now)
      with something like:
          cd saratoga
          patch < filename_here
 - extract my WE plugin
 - extract your desired icon set
 - edit your configurable information as needed
 - edit your look'n'feel as needed

Edits are initially to only the following files:
 - check-fetch-times.php (untested)
 - flyout-menu.xml
 - thermometer.php
 - Settings.php

