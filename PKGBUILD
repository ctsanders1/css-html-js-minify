#Automatically generated by pip2arch on 2015-09-02

pkgname=python-css-html-js-minify
pkgver=1.2.0
pkgrel=1
pkgdesc="StandAlone Async single-file cross-platform no-dependencies Unicode-ready Python3-ready Minifier for the Web."
url="https://github.com/juancarlospaco/css-html-js-minify"
depends=('python' 'pip')
makedepends=('python3' )
license=('CUSTOM')
arch=('any')
source=('https://pypi.python.org/packages/source/c/css-html-js-minify/css-html-js-minify-1.2.0.zip')
md5sums=('68db7a1c2586a9b0b085b3cb76da9fc9')

build() {
    cd $srcdir/css-html-js-minify-1.2.0
    python setup.py build
}

package() {
    cd $srcdir/css-html-js-minify-1.2.0
    python setup.py install --root="$pkgdir" --optimize=1 
}
