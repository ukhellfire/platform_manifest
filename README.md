Android Ice Cold Project - MEDIATEK Style
====================================
Attempting to create an MTK based AICP repo. At present this is a WIP, and anyone that attempts to sync and build these files,
will probably, well not probably, but will hit issues! You have been warned!

EDIT: As of Sunday 29th May, 15:25, This repo now syncs flawlessly... One Step Closer!

This only has device and vendor files for the Huawei G750T01 which is a mt6592 based device.

Download the Source
===================


Initializing Repository
-----------------------

Repo initialization:

    repo init -u https://github.com/ukhellfire/platform_manifest.git -b mm6.0


sync repo :

    repo sync



Building
--------

After the sync is finished,


    source build/envsetup.sh

    brunch aicp_g750t01-userdebug


Remember to `make clobber` every now and then!

