oe-layerindex-scripts
=====================

A couple little shell scripts for cloning/updating all the oe layers from LayerIndex

This can be useful for locating existing recipes, and just to see what layers are
available for you to add to your configurations.

The update script will update all git repositories in this directory, not just the
ones cloned from LayerIndex, so you can easily add your own repositories to your
local layer archive.

The update script also displays a git shortlog summary of all the changes made to the
master branches of the git repositories it updates since the last update occurred. I
find this useful as an alternative to Cliff Brake's weekly oe change summary emails.
