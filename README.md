## Arch10 Plymouth Theme

Based on https://gitlab.com/maurom/deb10.

<p align='center'>
	<img alt='arch10' src='arch10.webp'/>
	<br/>
	<i>
		Windows10-like Archlinux boot splash theme for Plymouth
	</i>
</p>

### Dependencies

+ `plymouth`

### Installation

+ Manual Installation
	- `$ cp plymouth-theme-arch10/ /usr/share/plymouth/themes/arch10`. Overwrite `arch10` if you ever have one.
	- `# plymouth-set-default-theme -R arch10`.
	- Done! If regenerating `initramfs` image is a success, you can now `reboot`.

+ AUR
	- Makepkg
		+ `$ git clone https://aur.archlinux.org/plymouth-theme-arch10.git`
		+ `$ cd plymouth-theme-arch10`
		+ `$ makepkg -sri`

	- AUR-helper
		+ `$ yay -S plymouth-theme-arch10`

### License

This theme is licensed under GPLv2, for more details check COPYING.
