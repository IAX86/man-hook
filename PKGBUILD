pkgname=man-hook
pkgver=0.1
pkgrel=2
depends=( 'man-db' 'pacman' )
source=( 'man.hook' 'man.hook.sig' )
md5sums=SKIP
validgpgkeys=SKIP

package() {
    mkdir -p "$pkgdir/usr/share/libalpm/hooks"
    cp "$srcdir/man.hook" "$pkgdir/usr/share/libalpm/hooks/man.hook"
}