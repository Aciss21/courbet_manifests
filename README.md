Courbet Android Building
===========

Getting started
---------------
Then use a command like this to clone the local manifest at the root of your local repository:
```
git clone -b 16 https://github.com/Aciss21/courbet_manifest.git .repo/local_manifests
```
Then to sync up:
```
repo sync --no-clone-bundle --no-tags -j"$(nproc --all)"
```
