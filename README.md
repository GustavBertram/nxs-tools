# Iron Realms Nexus Client Tools
These are tools for working with the settings files of the IRE [Nexus Client](https://nexus.ironrealms.com/Main_Page).

It has tools to `expand` the .nxs file format into .nexus, and to `compress` the .nexus format into .nxs.

The intent is to make text editing of Nexus Client settings files easier, and to allow version control to compare changes more easily.

## Warning
These tools are NOT officially supported. They are not even unofficially supported. They might break your files.

Always keep a backup of the original .nxs file in case expanding and compressing corrupts your settings.

For a single user, to keep track of changes in version control of your .nxs file, it would be best practice to only `expand` to be able to compare changes.

## Usage
The tools require Node.  Both `expand` and `compress` **will overwrite** target files.

### Linux
On Linux the tools can have execute permission added and called directly.
```
./expand <filename>.nxs
./compress <filename>.nexus
```
### Windows
```
node expand <filename>.nxs
node compress <filename>.nexus
```
