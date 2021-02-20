# Local Manifests #
Just grab the manifest and sync to get device sources
### LineageOS 18.1 ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/mt6768-11.xml --create-dirs
```

```bash
# Sync
repo sync -j$(nproc --all) --force-sync
```

### LineageOS 17.1 ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/mt6768-10.xml --create-dirs
```

```bash
# Sync
repo sync -j$(nproc --all) --force-sync
```
