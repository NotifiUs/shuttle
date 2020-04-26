# Shuttle by NotifiUs, LLC

Out of this world database sync for Amtelco MDR and CTE databases

## Overview

Shuttle is a 64-bit Windows application intended for syncing `MDR` and `CTE` databases within the [Amtelco](https://amtelco.com) ecosystem. 

Shuttle is a modern replacement to **MDR Check** - originally created by Michael Liebowitz in 2005 for [National Amtelco Equipment Owners (NAEO)](https://www.naeo.org).

## Download

You can download the latest release at [github.com/NotifiUs/shuttle/releases](https://github.com/NotifiUs/shuttle/releases)

Select the version you wish to install. From here, you have two options:

* Download the `.zip` file and extract the contents.
* Download the `Shuttle-Setup-x.x.x.exe` file directly

## Install

Run `Shuttle-Setup-x.x.x.exe` to install the application (downloaded directly, or in the extracted folder.)

The application installs into `C:\Program Files\Shuttle` and is available for all users. You will need `Administrator` privileges to install the application. 

## Keeping up to date

The application has built in auto-update functionality which will install the latest version when you exit. 

You won't need to regularly perform manual downloads for the latest version.  

## Other files

If you download the `.zip` file from the release page, there are some additional files included. 

This file is for version control and can safely be ignored: 

* `.gitignore` - This file tells version control what to ignore. 

These files are for auto-update functionality and can safely be ignored:

* `latesty.yml` - This file includes information on the latest version, including checksum hashes. 
* `Shuttle-Setup-X.X.X.exe.blockmap` - This file includes mapping information for application updates.


## Code signing

We do not currently have a 3rd-party verified code signing certificate. 

As a result, you may see `Unknown Publisher` warnings (or the files blocked from running). 

We plan to implement this function before `v1.0.0` is released. 
