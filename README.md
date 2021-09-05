# Local Manifests #
Just grab the manifest and sync to get device sources
### AOSP R ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/eleven.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```