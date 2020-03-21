[![appveyor build](https://ci.appveyor.com/api/projects/status/github/bitwarden/jslib?branch=master&svg=true)](https://ci.appveyor.com/project/bitwarden/jslib)

# Bitwarden JavaScript Library

Common code referenced across Bitwarden JavaScript projects.

# Work-in-progress to migrate to Argon2 in Bitwarden

This repository is a fork of Bitwarden/jslib as of 2020-03-21 for the purpose of moving to Argon2 in Bitwarden, and hopefully creating PR for the upstream to move to. The goal is not to be a long-term alternative to Bitwarden, but rather to do the work necessary to allow for a move to a more modern algorithm.

# Current thoughts on Argon2 migration

Currently, we are preparing to integreate libsodium into Bitwarden sources.

https://libsodium.gitbook.io/doc/password_hashing/default_phf

Where possible, we will also investigate other uses of libsodium to replace first-party re-implementation.

If you have alternative suggestions that may be preferable, please let us know.
