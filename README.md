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

+ Assuming that you already have configured plymouth, clone the repo.
+ Assuming that you don't have an `arch10` folder in the plymouth theme directory, `$ cp plymouth-theme-arch10/ /usr/share/plymouth/themes/arch10`
+ `# plymouth-set-default-theme -R arch10`
+ Done! If regenerating `initramfs` is a success, you can now `reboot`

### License

This theme is licensed under GPLv2, for more details check COPYING.
