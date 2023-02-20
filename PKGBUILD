pkgname=poly-battery
pkgver=1.0.0
pkgrel=1
pkgdesc="Another polybar battery display module"
arch=('any')
url="https://github.com/5eqn/poly-battery"
license=('MIT')
depends=('polybar' 'libnotify')
source=("https://github.com/5eqn/poly-battery/archive/refs/tags/v$pkgver.tar.gz")
md5sums=('TODO-idontknowyet')

package() {
  cd "$srcdir/v$pkgver"
  make install
}
