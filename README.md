[Android Ice Cold Project](http://aicp-rom.com)
====================================
Attempting to create an MTK based AICP repo. At present this is a WIP, and anyone that attempts to sync and build these files,
will probably, well not probably, but will hit issues! You have been warned!

This only has device and vendor files for the Huawei G750T01 which is a mt6592 based device.

Download the Source
===================


Initializing Repository
-----------------------

Repo initialization:

    $ repo init -u https://github.com/ukhellfire/platform_manifest.git -b mm6.0


sync repo :

    $ repo sync

***

Building
--------

After the sync is finished,

    source build/envsetup.sh

    brunch cm_g750t01-userdebug

Remember to `make clobber` every now and then!


Optional After Successful Build
--------------------------------

After a build, if you would like to share your build on XDA (Regular Unofficial Builds) , then please do follow the following Template to create
an XDA thread. Note that the template is a guideline of sort. You may make your own changes to it (esp please do in the download link) but try
and make thread as close to this one as possible. This is to aviod cluttering and make stuff organised.

Link : https://dl.dropboxusercontent.com/u/57672206/xda%20template
