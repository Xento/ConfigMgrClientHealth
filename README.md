# ConfigMgr Client Health Development Code

Version: 0.8.0

This is the unstable development version. DO NOT run this in a production environment.
[Download stable version instead](https://gallery.technet.microsoft.com/ConfigMgr-Client-Health-ccd00bd7)

[ConfigMgr Client Health Full documentation](https://www.andersrodland.com/configmgr-client-health/)

Note: Script version 0.8 requires database version 0.7.5.

## Changes since stable release

* Fixed a bug in Test-Registrypol function that could cause looping
* Windows 10 1803 and Windows 10 LTSB will now report build number correctly
* Fixed remaining pieces of hard coded paths in the script
* Fixed a bug that could case gpupdate to hang when initiated by Client Health
* Fixed and enchaned the service tests
* Added a function to test if PolicyPlatform is okay in WMI. Error here will cause ccmsetup to fail.
* Script will now validate if config.xml is valid XML, and abort if XML errors.
* Added restful webservice

This software is provided "AS IS" with no warranties. Use at your own risk.
