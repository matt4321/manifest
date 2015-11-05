TeamEOS
===========


Getting Started
---------------

To get started with TeamEOS, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Init core trees without any device/kernel/vendor :

    repo init -u git://github.com/teameos/manifest.git -b mm6.0

Then to sync up:

    repo sync

Get device and compile

    source build/envsetup.sh
    lunch eos_shamu-userdebug
    mka bacon

