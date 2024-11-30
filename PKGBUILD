# Maintainer: Jeremy Goss <jem@goss-family.net>

pkgname=disable-fallback-initcpio
pkgver=1
pkgrel=1
pkgdesc="Disable the building of the fallback initcpio"
url="https://github.com/jemgoss/disable-fallback-initcpio"
arch=(any)
depends=(mkinitcpio)

package() {
  cd $srcdir
  install -Dt "$pkgdir/usr/share/libalpm/hooks" $srcdir/10-disable-fallback-initcpio.hook
}
