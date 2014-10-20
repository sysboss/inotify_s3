Push2 S3
==========

Simple bash script.
Watches specified directory for changes and copy newly created
or modified files to Amazon S3 Cloud.

This uses the inotifywait program, which on a Debian-based system is
part of the 'inotify-tools' package.
