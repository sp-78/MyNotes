1) How to install or upgrade an RPM package?
nstalling or Upgrading

There are two main options of rpm command that are used to install or upgrade RPM packages:

    -i is used to install a new package. Always use this for kernel installations and upgrades just in case.

    -U is used to upgrade an RPM package but will also install a package if it does not exist in the RPM database.

Usage and additional options can be found in the RPM man page. Type man rpm from the command line. 

2) How to make rpm auto install dependencies
yum --nogpgcheck localinstall packagename.arch.rpm


