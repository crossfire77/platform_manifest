platform_manifest
=================
Android for Samsung Ace (cooper)

$ repo init -u git://github.com/crossfire77/platform_manifest.git -b AOKP-legacy

$ repo sync

$ source build/envsetup.sh

$ lunch aokp_marvel-userdebug

$ make bacon -jx    
