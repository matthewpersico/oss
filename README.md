This repo contains build/installation scripts for OSS code. See `build-oss --help'.

In order to prevent 'git status' from becoming unmanageable, .gitignore is set
to ignore just about every file that is not a repo member. Therefore, you can't
run a new install and expect to run 'git status' to pick up the new
build-oss.config file so you can 'git add' it. You will have to manually find
it to add.

The initial setup can be accomplished with pai-build-oss in post-any-install.
