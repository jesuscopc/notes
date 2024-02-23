# Burn XBOX 360 Games

## Type Xbox Game Isos

* XGD1 - Isos Xbox Classic Games
* XGD2 - Isos Size lower to 8.0GB frequently size is like 7.8GB
* XGD3 - Isos Size Up 8.0GB AAA Games like Gears Of War

* Important Install `libdvd` tools for dvd

```bash
sudo apt-get install libdvd-pkg
```

> Burning an ISO is best done through the command line with ==growisofs==.

* Install growisofs

```bash
sudo apt install growisofs
```

* Burn ISO XGD1

```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:1913776 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

* Burn ISO XGD2

```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:1913760 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

* Burn ISO XGD3

```shell
growisofs -use-the-force-luke=dao -use-the-force-luke=break:2133520 -dvd-compat -speed=2 -Z /dev/sr0=rom.iso
```

## Resources

[Burning Xbox 360 games](https://wiki.archlinux.org/title/Burning_Xbox_360_games)
