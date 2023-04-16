# texlive2023_outputs

The outputs of Tex Live 2023 installtion on **Linux Mint 21.1 x86_64**

Installtion reference : 

[TeX Live - Quick install for Unix](https://www.tug.org/texlive/quickinstall.html)


Host hardware specs :

```bash
CPU: dual core Intel Core i3-4030U (-MT MCP-)
speed/min/max: 1896/800/1900 MHz Kernel: 5.15.0-69-generic x86_64 
Mem: 4038.7/7853.7 MiB (51.4%) Storage: 465.76 GiB (77.6% used) Procs: 306
Shell: Bash inxi: 3.3.13
```
TeX Live 2023 Installed on :
`/mypartition/`

Contents of 
```bash
/mypartition/texlive2023/install-tl.log
/mypartition/texlive2023/texmf-dist/web2c/fmtutil.cnf
```

The ouptus log of the following commands :

**updmap.log :**

```bash
mktexlsr
tlmgr generate _fmtutil
tlmgr generate _updmap
updmap-sys
```

**Fmtutil-sys--all.log** (takes long time to exec)


```bash
fmtutil-sys --all
```
