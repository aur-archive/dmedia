# Maintainer: Hilton Medeiros <medeiros.hilton@gmail.com>

pkgname=dmedia
pkgver=12.04.0
pkgrel=1
pkgdesc="A simple distributed media library."
arch=('any')
url="https://launchpad.net/dmedia/trunk/"
license=('AGPL3')
depends=('python' 'dbus-python' 'python-gobject' 'python-userwebkit' 'python-microfiber' 'filestore')
source=("https://launchpad.net/$pkgname/trunk/12.04/+download/$pkgname-$pkgver.tar.gz")
md5sums=('3f803e3d0c88a39be158a3268e9b2e0f')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python setup.py install --prefix=/usr --root="$pkgdir" -O1
}
