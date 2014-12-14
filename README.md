proxpn-tunnelblick
==================

This repository contains setting files (*.tblk) for Tunnelblick/OpenVPN appropriate for use with proXPN OpenVPN service.

These settings were derived from the sample OpenVPN configuration files with information extracted from the proXPN branded Tunnelblick client.

These settings were created due to issues using the branded proXPN client on Macintosh OS X 10.9.5.

For more information and background please visit https://paretech.wordpress.com/2014/12/14/proxpn.

## Installation
1. Verify that Tunnelblick is installed.
2. Verify that Tunnelblick has been executed at least once before proceeding.
3. Copy the *.tblk files to ~/Library/Application Support/Tunnelblick/Configurations

## Notes
1. These configuration files have been tested on a system running Macintosh OS X 10.9.5 and Tunnelblick 3.4.2 (build 4055.4161)
2. The first time a configuration file is used from within Tunnelblick, the operator may be prompted by Tunnelblick for their password so that the permissions set on the configuration files can be changed. This prompt has nothing to do with these configuration files, it is how Tunnelblick operates.
3. Users can save their proXPN password to the OS X keychain manager. At this time the password must be stored once for each configuration file or if the file name changes.
4. These configuration files attempt to downgrade privileges after initializing. As such Tunnelblick may display a warning asking which scripts should be run and when. There is no advice at this time how to proceed or what the consequences are of each of the options other than the information given in the dialogue box. All options have been tested to work at this time.
