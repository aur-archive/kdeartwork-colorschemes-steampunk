# Maintainier Miguel Aguilar <zodiac_es@yahoo.es> 

pkgname=kdeartwork-colorschemes-steampunk
pkgver=3.0
pkgrel=3
pkgdesc="SteampunK KDE color-schemes. This item is a part of Steam-Powered Linux KDE theme set."
arch=('i686' 'x86_64')
url="http://kde-look.org/content/show.php?content=142139"
license=('CCPL-by-sa')
groups=(steam-powered-linux)
depends=('kdebase-workspace')
source=(http://kde-look.org/CONTENT/content-files/148277-SteampunK.colors)
md5sums=('87655f1cf58232d0b0af54568f094f4a')

package() {
   cd $startdir/src/
   install -dm 755  $pkgdir/usr/share/apps/color-schemes/
   install -Dm 644   148277-SteampunK.colors $pkgdir/usr/share/apps/color-schemes/SteampunK.colors
}
