# nipm-feed-manager-gui-labview
NIPM Feed Manager GUI (Beta) for LabVIEW 2014 or later.

## Overview
My goal is to provide users with an out-of-the-box Feed Manager that provides a GUI for managing NIPM feeds (e.g. create feed, add package(s) to feed, remove package(s) from feed, etc).  Please feel free to use this API, give feedback, and contribute.

You can use this NIPM Feed Manager GUI to do the following:
* Create new feed(s)
* Manage existing feeds
* Browse packages in a feed
* View a package's attributes (name, version, release notes, dependencies, ...)
* Publish (add) packages to a feed
* Unpublish (remove) packages from a feed

## How to Install
Prerequisites:
* LabVIEW 2014 or later
* [NI Package Manager](http://www.ni.com/downloads/ni-package-manager) 17.5 or later
* [NIPM API (Beta)](https://github.com/allenh-ni/nipm-api-labview/tree/master/Exports)

Installation and Usage Instructions
1. Click on the **Exports** folder, and download the most recent .vip file (VIPM package).
2. Double-click the .vip file.  This will launch VI Package Manager to install the NIPM Feed Manager to LabVIEW 2014 or later.
3. In LabVIEW, launch the NIPM Feed Manager GUI by selecting **Tools»NIPM Feed Manager»NIPM Feed Manager** from the LabVIEW toolbar.

Note: Launching the NIPM Feed Manager launches a VI.  The VI resides in the \<labview\>\project\NIPM Feed Manager directory.  You can modify the VI to suit your needs.

## Documentation
The source code (VI) includes documentation in comments.

Note: Further documentation is still in work.

## Source Code
* **Source** folder - Contains the source code.  The Feed Manager uses the [NIPM API (Beta)](https://github.com/allenh-ni/nipm-api-labview/tree/master/Exports).
* **Build Spec** folder - Contains the VIPM build spec (.vipb) used to create the .vip file.
* **Export** folder - Contains versions of the VIPM package (.vip), which you can use to install this NIPM Feed Manager.
