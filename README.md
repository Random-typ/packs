# packs
storage for packs

Here are all the version-upgrades of packs (no source code).
If you want to download packs go to our website (not there yet)

# Versions-folder

The versions folder contains all "upgrade files". The update files cant install packs by them selfes Pcks must be alrady installed.

# Packs-folder

The packs folder contains all packs that exist.

Packs are stored with id's, every id-folder contains an info.xml install.xml and may contain other update files. e. g. (1.0.0-installer.xml)

The install.xml file contains the script to install the pack. While the info.xml contains the newest version number of the pack.
The other -installer.xml files are update script to update a pack.
When a new version is published the downloader will install version after version until the newest one is installed.
