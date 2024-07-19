pkgname="gufetch"
pkgver="1.0.0"
pkgdesc="A Fetch script written in POSIX sh."
arch=("x86_64")
depends=('figlet'
         'lolcat')
makedepends=('shc')
pkgrel="1"
liscense=("custom")
source=("/home/$USER/gufetch/src/")
sha512sums=("SKIP")

build() {
  shc -f gufetch
  gcc  gufetch.x.c
  }
package() {
  mv $source ./
  tar --zstd -cf ./a.out
}
