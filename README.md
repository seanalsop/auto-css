# auto-css


This is a script that copies an existing CS Studio workspace and replaces all of
the instances of the original hostname with the new ones.
Users can change this to whatever template they like. A UUT workspace "default_uut"
 
Usage example:

./make_new_workspace.sh -n acq2106_999 -t default_uut

The above is the same as:

./make_new_workspace.sh --new_uut=acq2106_999 --template_uut=default_uut

The new UUT is the UUT which is to be created and the template UUT
is the workspace to be used to create the new one.

This script has also been tested with the Linux subsystem for windows!
Simply make sure that Linux subsystem is installed, then change the default 
path chosen by the script to the relevant Windows path to your CSS workspaces.

The best way to do this is to open a linux shell inside your CSS-Workspaces
directory and then use "pwd" to get the path. Paste this path into the 
make_new_workspaces.sh script on line 16 instead of the Linux style default. 


