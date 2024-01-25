## Download
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/RT1648/local_manifest-fleurprebuilt/master/fleur.xml --create-dirs
```
## Sync
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
