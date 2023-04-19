# Intalling TeX Live 2023 on Ubuntu 22.04.2 LTS (Jammy Jellyfish)/ Linux Mint Vera 21.1

Instructions :

- Install TeX Live 2023 following the steps descibed in [TeX Live - Quick install for Unix](https://www.tug.org/texlive/quickinstall.html)

- When installtion is done, exceute the following commands (may take a while for some of them)

```bash
mktexlsr
tlmgr generate _fmtutil
fmtutil-sys --all
tlmgr generate _updmap
updmap-sys
```
- Add the Latex 2023 fonts path :

```html
<dir>/path/to/texlive/2023/fonts/opentype</dir>
<dir>/path/to/texlive/2023/fonts/truetype</dir>
```
to your fonts configuration file :

```html
/etc/fonts/fonts.conf
```

Finally update with : `fc-cache -f`, and all should work fine !


