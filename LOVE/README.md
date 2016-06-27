# LÖVE snap

This project creates a working snap of LÖVE from a tarball snapshot out of upstream bitbucket.

To get this done, we need to do the following:
 - build from current svn snapshot

## Current state

Working features:
 - Launching love from the command line

Known issues:
 - Cannot pass parameters which are relative URLS (e.g. to launch a game)
   - https://github.com/sergiusens/qt5conf/issues/3