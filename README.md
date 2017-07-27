<img src="https://github.com/YuanWei-OS/yuanweios/blob/c7.1.2/YuanweiOS.png">

Welcome to YuanweiOS
===================


Getting Started
---------------

To get started with YuanweiOS7.1.2, you'll need to get familiar with
[Git and Repo](http://source.android.com/download/using-repo).

Please take note that we have two main line branches depending on
which hardware base your phone is working.

To initialize your local repository using the YuanweiOS trees, use this command:


	repo init -u git://github.com/YuanWei-OS/yuanweios.git -b c7.1.2



Then sync up with this command:

	repo sync

To start your build run this command:

	. build/envsetup.sh && breakfast <device> && time brunch <device>
