pkgname=man-hook
pkgver=0.1.1
pkgrel=1
depends=( 'man-db' 'pacman' )
source=( 'man.hook' )
md5sums=SKIP
validgpgkeys=SKIP

package() {
    mkdir -p "$pkgdir/usr/share/libalpm/hooks"
    cp "$srcdir/man.hook" "$pkgdir/usr/share/libalpm/hooks/man.hook"
}