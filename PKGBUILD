pkgname=dolphin-waifu2x
pkgver=0.1.1
pkgrel=1
pkgdesc="Utility to simplify work with waifu "
arch=(any)

depends=(waifu2x-converter-cpp)

package() {
  install -d $pkgdir/usr/bin
  install -d $pkgdir/usr/share/kservices5

  install -t $pkgdir/usr/bin/ -m775 $startdir/bin/*
  install -t $pkgdir/usr/share/kservices5/ -m644 $startdir/kservices5/*  
}
