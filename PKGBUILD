# Maintainer: Gerome Matilla <gerome.matilla07@gmail.com | gmail>

pkgname=plymouth-theme-arch10
pkgver=1
pkgrel=1
pkgdesc="Windows10-like Archlinux boot splash theme for Plymouth"
arch=('any')
url="https://github.com/manilarome/$pkgname"
license=('GPL3')
depends=('lightdm-webkit2-greeter')
source=("$url/releases/download/v$pkgver/$pkgname-$pkgver.tar.gz")
sha512sums=('2a5d2da6104c216db84d20e69bfb172eb15dacf25120aa99707e282de78bb546c48d4b361e4eb051494884a9c1b8ac28c29169a24714dc8653cd5578b4e84910')

package() {
	install -dm 755 "$pkgdir"/usr/share/plymouth/themes/arch10/
	cp -r --no-preserve=ownership * "$pkgdir"/usr/share/plymouth/themes/arch10/

	install -Dm 644 LICENSE "$pkgdir"/usr/share/licenses/$pkgname/LICENSE
}
