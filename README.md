# Joplin Portable for PortableApps.com

A version of Joplin running under the PortableApps.com platform.

## Status 
This project is in early beta stage. 

## Todo
- [ ] Documentation
- [ ] Icons are showing a black background instead of being transparent

## Disclaimer
Joplin is already Portable right from the bat. This wrapper does only segrate the data into
the PortableApps `Data` directory.

## Todo
- [x] Documentation

## Build

### Prerequisites

* [PortableApps.com Launcher](https://portableapps.com/apps/development/portableapps.com_launcher)
* [PortableApps.com Installer](https://portableapps.com/apps/development/portableapps.com_installer)
* [Powershell](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-linux?view=powershell-7)
* [Wine (Linux / MacOS only)](https://www.winehq.org/)

### Build

To build the installer run the following command in the root of the git repository.

```
powershell Other/Update/Update.ps1
```
