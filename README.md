# ObsidianOS ISO Build
This ISO is compatible with x86_64 PCs only. <br>
The ObsidianOS build scripts are used to build the ObsidianOS installation ISO images.
## Building Instructions
### 1. Install build tools (Arch Linux)
```
sudo pacman -S archiso
```
### 2. Clone the repository
```
https://github.com/obsidiandt/ObsidianOS-iso
```
### 3. Build
```
cd baseline
sudo mkarchiso -v -w baseline/ -o output/
```
