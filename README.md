platform_manifest
=================

SYNC IT AND BUILD IT:

repo init -u git://github.com/CodeTh3ory/platform_manifest.git -b master

repo sync

. build/envsetup.sh
lunch
Select from menu
make codex -j8
