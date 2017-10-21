debian-ppa
==========

Debian PPA Utility - Utility which allows you to add PPA's on Debian.
It adds "add-apt-repository" binary which allows you to add PPA's.

[Debian PPA Utility blog post](http://foolcontrol.org/?p=1642)

How to use it?
--------------

__Download/Build package__

You can [download my signed package](https://s3.eu-central-1.amazonaws.com/adnan-public-dl/debian-ppa/debian-ppa_1.0_all.deb) 

Source and changes file are in [same directory](http://hodzic.org/debian-ppa/debian-ppa_1.0_all.deb) 

Or you can build your own by running "`dpkg-buildpackage -uc -us`" inside of the debian-ppa source directory.

__Install/Add PPA's__

After you install the package, you're able to run "`add-apt-repository`" and add PPA's. i,e:

`sudo add-apt-repository ppa:linrunner/tlp`
