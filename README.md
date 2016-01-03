# mkffimage
Gluon firmware generation for Rheinbach (ff-rhb) 

These scripts generate a new Freifunk Gluon Firmware for Rheinbach.

The process follows the documentation on http://gluon.readthedocs.org/en/v2015.1.2/

The first step clones the gluon repositories to a directory gluon/<branch>/gluon in the current directory. The second step clones the site directory from https://github.com/Byggvir/ff-rhb.git.

If these directories exists I assume that they contain the repositories and the repositories are updated with "git pull".

All directories are cleaned before the generation starts. 


Contact: Thomas Arend
E-mail: thomas - at - arend-rhb.de
Date: 03.01.2016
