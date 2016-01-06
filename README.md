# Taskbar.path

"Taskbar.patch" is patch for Lxpanel 0.5.10 that enables the "close all windows" 
feature for grouped-task in taskbar.

# How to Install

1) First download and extract the sources of LXpanel 0.5.10:

   http://sourceforge.net/projects/lxde/files/LXPanel (desktop panel)/LXPanel 0.5.10/

2) Apply the patch to lxpanel-0.5.10/src/plugins/taskbar.c:

   # patch lxpanel-0.5.10/src/plugins/taskbar.c < taskbar.patch

3) If you want install the italian language, you can patch in the same way the "it.po" file,
   (otherwise you can jump this step) :

   # patch lxpanel-0.5.10/po/it.po < it.patch

4) Compile with:

	# ./configure
	# make
	# make install

Restart your session and test the new feature.
