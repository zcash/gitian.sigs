This repository contains Gitian signatures for [Zcash](https://github.com/zcash/zcash).

It should be updated on each release.

If you have 2FA on your GitHub account, you'll need an auth token to push your sigs from within the Vagrant VM.
Another way is to copy them into a clone of this repo on your local computer before pushing:

`vagrant scp :/home/vagrant/gitian.sigs/v1.0.11 ~/Zcash/gitian.sigs/`
