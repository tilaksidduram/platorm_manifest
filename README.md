ParanoidAndroid Legacy
===============


Getting Started
---------------

To get started with ParanoidAndroid, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the ParanoidAndroid trees, use a command like this:
    
    mkdir ~/android
    cd ~/android		
    mkdir ~/android/PA	
    cd ~/android/PA
    repo init -u git://github.com/tilaksidduram/platorm_manifest.git -b jb43


Then to sync up:

    repo sync -j(number depending on how much cores you computer has; default is 5)

For information on how to build, check [Here](https://github.com/ParanoidAndroid/paranoid)
