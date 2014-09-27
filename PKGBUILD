# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneos-apps-settings
pkgver=20140908
pkgrel=1
pkgdesc="This provides to One OS's UI."
arch=('i686' 'x86_64')
url="http://infinityos.org/"
license=('LGPLv2+')
makedepends=('bzr')
_realver=0.3.1
provides=("oneos-apps-settings")
source=https://github.com/g97iulio1609/oneos-apps-settings
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/etc/skel/.local/usr/share/
    cp -R applications "${pkgdir}"/etc/skel/.local/usr/share/

    mkdir -p "${pkgdir}"/etc/skel/.config/
    cp -R google-chrome "${pkgdir}"/etc/skel/.config/
cp -R libreoffice "${pkgdir}"/etc/skel/.config/


}
