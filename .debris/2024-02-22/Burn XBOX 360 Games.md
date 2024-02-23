	
> [!TIP] Type Xbox Game Isos
> XGD1 - Isos Xbox Classic Games
> XGD2 - Isos Size lower to 8.0GB frequently size is like 7.8GB
> XGD3 - Isos Size Up 8.0GB AAA Games like Gears Of War


> [!warning] Important Install `libdvd` tools for dvd
```shell
sudo apt-get install libdvd-pkg
```

* Burning an ISO is best done through the command line with ==growisofs==.

> [!info] Install growisofs
```shell
> sudo apt install growisofs
```

> [!example] Burn ISO XGD1
```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:1913776 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

> [!example] Burn ISO XGD2
```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:1913760 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

> [!example] Burn ISO XGD3
```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:2133520 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

> [!important] Resources
> [Burning Xbox 360 games](https://wiki.archlinux.org/title/Burning_Xbox_360_games)
