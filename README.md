# Stuff needed to build for giulia

### Init Your ROM's Manifest. For example:

```
repo init -u https://github.com/DerpFest-AOSP/android_manifest.git -b 16 --git-lfs
```

### Clone Repository

```
git clone https://github.com/aosp-for-giulia/local_manifest.git .repo/local_manifests
```

### Start Sync 

```
repo sync -j$(nproc --all) --no-tags --no-clone-bundle --current-branch
```
