suckless dmenu - simple fork
============================
simple fork of dmenu with the patches that i used pre-applied.<br/>
dmenu is an efficient dynamic menu for X.

patches
------------
dmenu-border<br/>
dmenu-caseinsensitive<br/>
dmenu-center<br/>
dmenu-date<br/>
dmenu-listfullwidth<br/>
dmenu-mousesupport<br/>
dmenu-numbers<br/>

installation
------------
edit config.mk to match your system<br/>
this will fuck up all your scripts beginning with `dmenu*` if stored in `bin/dmenu*` as outlined in config.mk.<br/>
type `doas make install` to build dmenu, then install.
