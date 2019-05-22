# auto-css


This is a script that copies an existing CS Studio workspace and replaces all of
the instances of the original hostname with the new ones.
Users can change this to whatever template they like. A UUT workspace "default_uut"
 
Usage example:
./make_new_workspace -n acq2106_999 -t default_uut

The above is the same as:
./make_new_workspace --new_uut=acq2106_999 --template_uut=default_uut

The new UUT is the UUT which is to be created and the template UUT
is the workspace to be used to create the new one.

