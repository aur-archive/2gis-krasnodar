# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>

pkgname=2gis-krasnodar
pkgver=16
pkgrel=1
pkgdesc="Map of Krasnodar for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Krasnodar-${pkgver}.orig.zip")
md5sums=('9c7ef875b9a1be934493d529e4364549')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Krasnodar.dgdat "${startdir}/pkg/opt/2gis/krasnodar.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Krasnodar.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Krasnodar.dglf" || return 1

}
