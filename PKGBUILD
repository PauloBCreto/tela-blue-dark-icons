# Maintainer: PauloBCreto <pcreto2020@hotmail.com>

pkgname=Tela-Blue-Dark
pkgver=$(date +%y.%m.%d)
pkgrel=$(date +%H%M)
arch=('any')
license=('GPL')
url="https://github.com/PauloBCreto/tela-blue-dark-icons"
pkgdesc=""
source=("git+https://github.com/PauloBCreto/tela-blue-dark-icons.git")
md5sums=(SKIP)


package() {
    cp -r "${srcdir}/tela-blue-dark-icons/tela-blue-dark-icons/usr/" "${pkgdir}/"
    mv "${pkgdir}/usr/share/icons/" "${pkgdir}/usr/share/icons/"
}
