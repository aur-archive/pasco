# Contributor: Michael P <ptchinster@archlinux.us>
pkgname=pasco
pkgver=20040505_1
pkgrel=2
pkgdesc="Examine the contents of Internet Explorer's cache files (forensic purposes)."
arch=('i686' 'x86_64')
url="http://www.jonesdykstra.com/"
license=('GPL')
source=("http://downloads.sourceforge.net/sourceforge/fast/${pkgname}_${pkgver}.tar.gz")
md5sums=('dfcc3932c4d93d90a252159b9d8b525c')

build() {
	cd "$srcdir/${pkgname}_${pkgver}/src"
	make install || return 1
	mv -v ../bin $srcdir/../pkg
}

