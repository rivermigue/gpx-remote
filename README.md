GamePanelX-V3-Remote

Created by Ryan Gehrig

=============

GamePanelX is a Free and Open Source Game Control Panel.

This is the GamePanelX Remote portion of the project.  This allows you to run your gameservers on a system other than the master server.  It also provides you with Linux user account privilege separation, and a built-in FTP server.  Thank you for choosing GamePanelX Remote!



SUPPORTED OPERATING SYSTEMS
------------------------------
Linux: RedHat/CentOS/Fedora, Debian/Ubuntu



INSTALLATION
------------------------------
# sudo chmod u+x install.sh
# sudo ./install.sh

This will get you started on the installation.  This will also ask you if you want to install the FTP server.



UPDATE
------------------------------
To update, run:
# sudo chmod u+x update.sh
# sudo ./update.sh

Note: To update a Remote release _older_ than 3.0.10, run:
# sudo chmod u+x upgrade_309_3012.sh
# sudo ./upgrade_309_3012.sh



SUPPORT/DOCUMENTATION/TUTORIALS
-------------------------------
Website: http://gamepanelx.com/
Documentation: http://gamepanelx.com/wikiv3/index.php?title=Remote_Install
Support Forums: http://gamepanelx.com/forums/
General Documentation: http://gamepanelx.com/wikiv3/



UNINSTALL
-------------------------------
To uninstall, this will walk you through removal.
NOTE: If you answer YES to removing your GPX user, this will remove ALL gpx files including gameservers and accounts for GamePanelX Remote in /usr/local/gpx.

# sudo chmod u+x ./uninstall.sh
# sudo ./uninstall.sh
