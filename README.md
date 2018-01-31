# dewey-lib

This repo contains libraries that are required for Dewey. 

It is normally cloned as a submodule into <dewey>/lib.

## git-lfs

This repository uses git large file support (git-lfs). You may need to
install [git-lfs](https://git-lfs.github.com/) on your system. 

## populating python packages

You can populate the python package cache from a requirements file, e.g.:
`pip install --no-use-wheel --download python/ -r ../requirements/production.txt`.

