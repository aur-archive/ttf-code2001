# Maintainer: <kfgz at interia dot pl>
# Contributor: J. Tanzman <jt512 at jt512 dot dyndns dot org> 

pkgname=ttf-code2001
pkgver=0.919
pkgrel=2
pkgdesc="Unicode Plane One font"
arch=('i686' 'x86_64')
url="http://www.code2000.net"
license=('unknown')
depends=('fontconfig' 'xorg-fonts-encodings')
install=font.install
source=(http://www.alanwood.net/downloads/code2001.zip)
md5sums=('e97203991a307ca15b243a3baac6ec08')

package() {
  install -D -m644 CODE2001.TTF "${pkgdir}"/usr/share/fonts/TTF/Code2001.ttf
}
