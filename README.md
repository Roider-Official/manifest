# Roider ROM
memo:Romの説明~~~
## *How to Build*
#### Sync
```
# Create a working folder
$ mkdir {Working Folder}  Example:{Working Folder}="RoiderROM"
$ cd  {Working Folder}
# Initialize local repository
$ repo init -u https://github.com/Roider-Official/manifest -b Eleven
# All repository Download
$ repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
