# Maintainer: Jakub Zalewski <jakzale@gmail.com>

pkgname=haskell-language-server-bin
pkgver=0.2.1
pkgrel=1
pkgdesc='Integration point for ghcide and haskell-ide-engine.'
arch=('x86_64')
url='https://github.com/haskell/haskell-language-server'
license=('Apache')
provides=('haskell-language-server')
source=("haskell-language-server-wrapper-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/$pkgver/haskell-language-server-wrapper-Linux.gz"
        "haskell-language-server-8.10.1-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.10.1.gz"
        "haskell-language-server-8.8.4-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.8.4.gz"
        "haskell-language-server-8.8.3-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.8.3.gz"
        "haskell-language-server-8.8.2-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.8.2.gz"
        "haskell-language-server-8.6.5-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.6.5.gz"
        "haskell-language-server-8.6.4-$pkgver.gz::https://github.com/haskell/haskell-language-server/releases/download/0.2.1/haskell-language-server-Linux-8.6.4.gz")

md5sums=('5d7a44860066710872f5750db43cadef'
         '8b2e47e05b952af32bb09bc5d1f93a58'
         'b45dd8b510204a1fadaf230e7c1d9ae4'
         'f13569899bc35f7a062f52b40ec2bf00'
         '79f4ee18e9044ed091cd09765a8f15fd'
         '448682b5d820b4a1bc295a157f366185'
         'f37ff59a5dfed5382c20a02100e3efb4')

package () {
    install -D "$srcdir/haskell-language-server-wrapper-$pkgver" "$pkgdir/usr/bin/haskell-language-server-wrapper"
    install -D "$srcdir/haskell-language-server-8.10.1-$pkgver"  "$pkgdir/usr/bin/haskell-language-server-8.10.1"
    install -D "$srcdir/haskell-language-server-8.8.4-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.4"
    install -D "$srcdir/haskell-language-server-8.8.3-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.3"
    install -D "$srcdir/haskell-language-server-8.8.2-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.8.2"
    install -D "$srcdir/haskell-language-server-8.6.5-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.6.5"
    install -D "$srcdir/haskell-language-server-8.6.4-$pkgver"   "$pkgdir/usr/bin/haskell-language-server-8.6.4"
}
