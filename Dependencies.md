EasyBuild has a couple of dependencies, some of them optional:

Required
--------

 * [[Python 2.4|http://python.org/]], or a more recent 2.x version
 * [[environment-modules|http://modules.sourceforge.net/]], version >= 3.2.6
  * An rpm for this is available in the RHEL and SL repositories. An deb file has recently been accepted and [[available in debian-testing for now|http://packages.debian.org/testing/main/environment-modules]] and will be available in Ubuntu 12.10.
  * environment-modules requires [[Tcl|http://www.tcl.tk/]] to be installed (with header files and development libraries)

EasyBuild is written in Python, so a Python installation is indispensable.

EasyBuild not only generates module files to be used along with the software it installs, it also depends on the generated modules for some of its functionality. In practice, you need environment modules to make full use of EasyBuild's features.

### Python modules

 * (none)

## Optional

### Python modules

 * [[GitPython|http://gitorious.org/git-python]], only needed if EasyBuild is hosted in a git repository or if you're using a git repository for easyconfig files (.eb)
 * [[pysvn|http://pysvn.tigris.org/]], only needed if you're using an SVN repository for easyconfig files (.eb)