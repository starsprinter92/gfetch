pkgname="gufetch"
pkgver="1.0.0"
pkgdesc="A Fetch script written in POSIX sh."
arch=("x86_64")
depends=('figlet'
         'lolcat')
makedepends=('shc')
pkgrel="1"
liscense=("custom")
source=("src/gufetch")
sha512sums=("SKIP")

build() {
  shc -f gufetch
  gcc  gufetch.x.c
  }
package() {
  rm $source/gufetch
  mv $source/a.out $source/gufetch
  tar --zstd -cf $source/gufetch
}
