Courbet Android Building
===========

Getting started
---------------
Then use a command like this to clone the local manifest at the root of your local repository:
```
git clone https://github.com/Aciss21/courbet_manifests.git .repo/local_manifests -b 17
```
Then to sync up:
```
repo sync --no-clone-bundle --no-tags -j"$(nproc --all)"
```
