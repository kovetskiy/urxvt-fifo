pkgname="urxvt-fifo"
pkgver=1.0
pkgrel=1
pkgdesc="Extension for sending keys to urxvt via fifo"
url="https://github.com/kovetskiy/urxvt-fifo"
arch=('any')
license=('GPL')
makedepends=()
source=(https://github.com/kovetskiy/urxvt-fifo)
md5sums=(SKIP)

pkgver() {
    cd "${pkgname}"
    echo $(git rev-list --count master).$(git rev-parse --short master)
}

package() {
    install -Dm644 "$srcdir"/urxvt-fifo "$pkgdir"/usr/lib/urxvt/perl/fifo
}
