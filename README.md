# Local Manifests #
Just grab the manifest and sync to get device sources
### LineageOS 18.1 ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/eleven.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```