pkgname=man-hook
pkgver=0.2
pkgrel=3
depends=( 'man-db' 'pacman' )
source=( 'man.hook' ) # 'man.hook.sig'
sha256sums=( '4c6bedd61a9134abf00ca796f626158c440289f6979b27fe48c098fa06259fb2' )
validgpgkeys=SKIP

package() {
    mkdir -p "$pkgdir/usr/share/libalpm/hooks"
    cp "$srcdir/man.hook" "$pkgdir/usr/share/libalpm/hooks/man.hook"
}