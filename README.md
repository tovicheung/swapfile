# swapfile
Simple bash utility to swap filenames

## Installation
Installing swapfile is a piece of cake:
```bash
git clone https://github.com/tovicheung/swapfile # clone this repository
cd swapfile # cd to cloned directory
mv swapfile /usr/local/bin # move to path
cd ..
rm -rf swapfile
```
or for people who prefer one-liners:
```bash
git clone https://github.com/tovicheung/swapfile && cd swapfile # cd to cloned directory && mv swapfile /usr/local/bin # move to path && cd .. && rm -rf swapfile
```

## Documentation
Swap file1 and file2
```bash
swapfile file1 file2
```
Get help
```bash
swapfile -h
```
Custom temp file name (uses mktemp)
```bash
swapfile file1 file2 -t .mytmp.XXXXXX
```
