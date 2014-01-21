Simons-git-helper
=================

To make work easier and more save with the whole committing, pulling and merging things, I created a shell script on the basis of Timos ideas.

It creates an additional Branch called "development" to work in. The name of the branch can be replaced in the script.

Install
=======

To install the tool just download "sgh", bring it to your /usr/bin directory and make it executable.


ToDo
=======

- Better Error Handling

Changelog
=======

Version 0.3
- integrated sgh continue commit/pull
    - After dealing with conflicts simply run this command to continue what you were doing.

Version 0.2
- integrated sgh pull
    - Fully automatic pull if no local changes were made. Pulls master and merges with dev branch.

Version 0.1
- integrated sgh commit "Commit message"
    - Fully automatic commit, it adds and commits files, pulls master and merges the changes before pushing your changes to master. At the end changes back to dev branch
- Error Handling: if an error occurs throughout the progress the program exits with an hopefully helpful message