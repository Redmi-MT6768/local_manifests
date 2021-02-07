# Local Manifests #
### LineageOS 17.1 ###

```bash

# Grab Local Manifests
curl -o .repo/local_manifests/roomservice.xml https://raw.githubusercontent.com/Redmi-MT6768/local_manifests/master/mt6768.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
