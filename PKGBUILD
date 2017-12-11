# Maintainer: Chanathip Srithanrat <axesd9@gmail.com>

pkgname=brother-dcpj140wcupswrapper
pkgver=1.1.3_6
pkgrel=1
pkgdesc='Brother DCP-J140W CUPSwrapper printer driver'
arch=('x86_64')
url='http://support.brother.com/g/s/id/linux/en/'
license=('GPL')
depends=('lib32-glibc'
         'cups')
install="$pkgname.install"
source=("http://download.brother.com/welcome/dlf005589/${pkgname#brother-}-${pkgver/_/-}.i386.deb")
md5sums=('583901050447156f8428bbdff1219ba6')

prepare() {
    bsdtar xf data.tar.gz
}

package() {
    cp -R opt $pkgdir
}
