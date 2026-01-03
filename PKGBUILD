# Maintainer: Sofiya S.V <sofija.p2018@gmail.com>
pkgname=clearine
pkgver=0.7.10
pkgrel=1
pkgdesc="GTK3-based logout-window overlay for independent windowmanager."
# arch=('x86_64')
arch=("any")
url="https://github.com/sofijacom/clearine"
license=('GPL')
depends=(
  'gtk3'
  'python-cairo'
  'python-gobject'
)
provides=('clearine')
# install="$pkgname.install"

package() {
  cd "${srcdir}"
  bsdtar -xf clearine-0.7.9.tar.xz -C "$pkgdir"
}
