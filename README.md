# PureDarwin System Updater
### A system update manager for PureDarwin

* This is derived from Darwinbuild's darwinup application. 

#### Usage
* Install files from a tarball

 `$ pd_update install library-1.2.3.tar.gz`

* Install several directories from /tmp/

 `$ pd_update install /tmp/*/*~dst/`

* Uninstall everything

 `$ pd_update uninstall all`

* See what archives have been superseded and then uninstall them

 `$ pd_update list superseded`
 
 `$ pd_update uninstall superseded`

* Uninstall several archives by serial, the oldest one, and one named myroot

 `$ pd_update uninstall 9 16 myroot oldest`

* Install a root from src.macosforge.org

 `$ pd_update install http://src.macosforge.org/Roots/10D573/zlib.root.tar.gz`
