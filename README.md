Lowlight
========
Copyright (C) 2011 Peter Parkanyi <me@rhapsodhy.hu>

Gitar is a shell script to maintain multiple git sub-repositories in a git repository. It is similar to git submodules, but the sub-repositories do not point to a specific commit.

The sub-repositories may also be anywhere on the filesystem. If the sub-repositories location on the target filesystem is not inside the project directory then a symbolic link is created in the project dir.

Licence
-------
Distributed under the MIT licence
