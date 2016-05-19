pkgname=linssid
_pkgname=LinSSID
pkgver=2.7
_pkgver=2.7-1
pkgrel=1
pkgdesc="Graphical wireless scanner"
arch=('x86_64')
url="http://sourceforge.net/projects/linssid"
license=('GPL3')
depends=('iw' 'wireless_tools' 'qt5-base' 'qt5-svg')
source=("http://iweb.dl.sourceforge.net/project/$pkgname/${_pkgname}_${pkgver}/${pkgname}_${_pkgver}_amd64.deb")
md5sums=('d75df1674008aa75af02e6dc3aee5ee4')

package() {

    tar -xvf data.tar.xz -C $pkgdir
    rm -r $pkgdir/usr/share/doc


    }
