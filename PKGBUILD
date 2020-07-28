# Maintainer: Jakub Zalewski <jakub@pozitive.dev>

pkgname=haskell-language-server-bin
pkgver=0.2.2
pkgrel=1
pkgdesc='Integration point for ghcide and haskell-ide-engine.'
arch=('x86_64')
url='https://github.com/haskell/haskell-language-server'
license=('Apache')
provides=('haskell-language-server')
source=("haskell-language-server-wrapper-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-wrapper-Linux.gz"
        "haskell-language-server-8.10.1-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.10.1.gz"
        "haskell-language-server-8.8.4-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.8.4.gz"
        "haskell-language-server-8.8.3-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.8.3.gz"
        "haskell-language-server-8.8.2-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.8.2.gz"
        "haskell-language-server-8.6.5-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.6.5.gz"
        "haskell-language-server-8.6.4-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-Linux-8.6.4.gz")

md5sums=('78fd83dc954f783348be2841f5deef7d'
         '6a234a61d51ecb0703140c1ee6e97554'
         '1195bf83c5f27163810bfd5f98081bd9'
         'c0154eb26703975ec37e27919d4096f5'
         '374fdefc1849f8004f74f6745b39d159'
         '749974ec06075f05fe01af807a4530e0'
         '8abe6cd3380586bb8e93daae75f4e9e6')

package () {
    install -D "$srcdir/haskell-language-server-wrapper-$pkgver" "$pkgdir/usr/bin/haskell-language-server-wrapper"
    install -D "$srcdir/haskell-language-server-8.10.1-$pkgver"  "$pkgdir/usr/bin/haskell-language-server-8.10.1"
    install -D "$srcdir/haskell-language-server-8.8.4-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.4"
    install -D "$srcdir/haskell-language-server-8.8.3-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.3"
    install -D "$srcdir/haskell-language-server-8.8.2-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.2"
    install -D "$srcdir/haskell-language-server-8.6.5-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.6.5"
    install -D "$srcdir/haskell-language-server-8.6.4-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.6.4"
}
