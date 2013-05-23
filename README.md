android_local_ef44s
======================

Local Manifest for Pantech Vega S5

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	mkdir .repo/local_manifests

To initialize your local repository using the Cyanogemod manifest, use commands like these:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-10.1

    curl -L -o .repo/local_manifests/pantech.xml -O -L https://raw.github.com/killsleep/android_local_ef44s/master/ef44s.xml
 
    	( or Download: https://github.com/killsleep/android_local_ef44s/blob/master/ef44s.xml
		and place it in ~/Android/.repo/local_manifest.xml (or ~/'name you chose'/.repo)

Then to sync up:

    repo sync
