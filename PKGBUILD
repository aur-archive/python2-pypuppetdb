
pkgname=python2-pypuppetdb
_realname=pypuppetdb
pkgver=0.1.1
pkgrel=1
pkgdesc="Library for working with the PuppetDB REST API."
arch=(any)
url="https://github.com/nedap/pypuppetdb"
license=("APACHE")
depends=('python2'
         'python2-requests')

backup=()
install=pypuppetdb.install

source=("http://pypi.python.org/packages/source/p/${_realname}/${_realname}-${pkgver}.tar.gz")

md5sums=('3a1f1b553e9049ab105ba72f210cfefc')

package() {
  cd ${srcdir}/${_realname}-${pkgver}
  python2 setup.py install --root=${pkgdir}/ --optimize=1
}
