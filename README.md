# Intalling TeX Live 2023/2024 on Ubuntu 22.04.2 LTS (Jammy Jellyfish)/ Linux Mint Vera 21.1

Instructions :

- Install TeX Live 2023/2024 following the steps descibed in [TeX Live - Quick install for Unix](https://tug.org/texlive/doc/texlive-en/texlive-en.html#x1-160003.1.1)

- When installtion is done, cd to the installation location and exceute the following commands (may take a while for some of them)

```bash
mktexlsr
tlmgr generate _fmtutil
sudo fmtutil-sys --all
tlmgr generate _updmap
updmap-sys
```
- Add the Latex fonts path (optional) :

```html
<dir>/path/to/texlive/2024/fonts/opentype</dir>
<dir>/path/to/texlive/2024/fonts/truetype</dir>
```
to your fonts configuration file :

```html
/etc/fonts/fonts.conf
```

Finally update with : `fc-cache -f`, and all should work fine !


