# Themes for Wine

Install themes for Wine:

- Capriccio
- Light
- Neiio
- Royale
- Shiftie2d
- Vaio
- 'XP Style'

## How generate package

```bash
# Install dpkg-deb tool
sudo apt update
sudo apt install dpkg

# Generate deb package
./compile.sh

# Install package
sudo apt install ./wine-themes_0.0.1_all.deb

# Change theme
winecfg
```

## Download debian package ready

[https://github.com/winunix/debian/tree/master/pool/main/w/wine-themes](https://github.com/winunix/debian/tree/master/pool/main/w/wine-themes)
