# Initialize local repository
```
repo init -u https://github.com/Good4Nothing-AOSP/android -b tsubaki --git-lfs
```

# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

# Build

- Set up the build environment
```bash
. b*/env*
```

- Lunch a target
```bash
lunch lineage_codename-bp4a-user
```

- To start compiling
```bash
m bacon
```

