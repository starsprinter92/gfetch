pkgname="gufetch"
pkgver="1.0.0"
pkgdesc="A Fetch script written in POSIX sh."
arch=("x86_64")
depends="figlet,lolcat"
makedepends="shc"
liscense=("custom")
source=("src/gufetch")
sha512sums=("SKIP")

package() {
  shc -f src/gufetch
  gcc  gufetch.x.c
  tar a.out
  }
