MAHDI-ROM manifest for LG L7 && L5 devices 
===========

Getting Started
---------------

To initialize your local repository

$ repo init -u git://github.com/asce1062/platform_manifest.git -b kk-4.4.3-caf

Then to sync up:

$ repo sync -j#

Build your device:

$ . build/envsetup.sh

$ lunch (enter device number and hit enter)

$ brunch P705(P700 or e610)

Flash ZIP:

out/target/product/DEVICENAME/mahdi-VERSION-DEVICENAME.zip

=======
android
=======
