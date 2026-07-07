# WinGetTest
Testing of deployment of WinGet DSC to configure Windows 11 Deployments. 

## Usage
winget configure --accept-configuration-agreements --disable-interactivity -f https://raw.githubusercontent.com/mikeytadd/WinGetTest/configfiles/NAMEOFFILE.yaml

## Notes
winget configure --enable needs to be run before applying configuration

winget configure validate NAMEOFFILE.yaml - To validate the YALM structure. 
