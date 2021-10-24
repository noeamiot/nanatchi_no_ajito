# nanatchi_no_ajito
Nanatchi no ajito (ナナチのアジト) GRUB Theme

## Install

- Create the needed font files by running from the base of this project
```sh
grub-mkfont -s 16 -o nanatchi_no_ajito_theme/fonts/dejavusansmono_16.pf2 DejaVuSansMono.ttf
grub-mkfont -s 20 -o nanatchi_no_ajito_theme/fonts/dejavusansmono_20.pf2 DejaVuSansMono.ttf
grub-mkfont -s 24 -o nanatchi_no_ajito_theme/fonts/dejavusansmono_24.pf2 DejaVuSansMono.ttf
grub-mkfont -s 40 -o nanatchi_no_ajito_theme/fonts/dejavusansmono_40.pf2 DejaVuSansMono.ttf
grub-mkfont -s 16 -o nanatchi_no_ajito_theme/fonts/unicode_16.pf2 Unicode.ttf
```
Replace the file path in the previous commands (it does not have to be a ttf file).

You can get the latest official releases of DejaVu fonts here (https://dejavu-fonts.github.io/Download.html) or by installing the DejaVu package from your distribution.
You can get the latest official releases of Unicode fonts here (https://ftpmirror.gnu.org/gnu/unifont/) or by installing the unifont package from your distribution.

- Download and move the [background image](https://www.wallpaperflare.com/brown-ball-house-in-cave-illustration-environment-made-in-abyss-wallpaper-hyqio) to `nantchi_no_ajito/images/background.png` (if you can find the original artist, please contact me so I can better reference them as I wasn't able find them).

- Add the content of the grub.cfg file to the the files in the `grud.d` configuration directory (or your own configuration) (if you follow the rebel way, just be carefull as a `grub-install` may override your changes [which should just show the default style of GRUB, but who knows]).

- Copy the `nanatchi_no_ajito_theme` directory to the GRUB themes folder (or your boot directory [usually `/boot/`] if you like it the ugly way).

The pictures in all the subfolders of `natatchi_no_ajito_theme/images/` are taken as-is or scaled from the [Grub2-themes project](https://github.com/vinceliuice/grub2-themes) and are under GPL3 if you need more than the ones included here, you can download them there.

## Result

![Result](https://github.com/noeamiot/nanatchi_no_ajito/blob/master/nanatchi_no_ajito.png "Nanatchi no ajito GRUB theme")