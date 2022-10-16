pkgname=man-hook
pkgver=0.3
pkgrel=2
depends=( 'man-db' 'pacman' )
source=( 'man.hook' ) # 'man.hook.sig'
sha256sums=( 'b6fdc8e55659959ad6fe91cb65094808a657db6e7da7e21fd6f37d63207695b0' )
validgpgkeys=SKIP

package() {
    mkdir -p "$pkgdir/usr/share/libalpm/hooks"
    cp "$srcdir/man.hook" "$pkgdir/usr/share/libalpm/hooks/man.hook"
}