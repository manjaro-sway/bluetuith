# Maintainer: darkhz <kmachanwenw at gmail dot com>
pkgname=bluetuith
_pkgname=bluetuith
pkgver=0.2.2
pkgrel=3
pkgdesc="A TUI based bluetooth manager"
arch=('x86_64' 'i686' 'arm' 'aarch64' 'armv6h' 'armv7h')
url="https://github.com/darkhz/bluetuith"
license=('MIT')
depends=('bluez' 'bluez-obex' 'dbus')
optdepends=('networkmanager: For PANU networking'
            'modemmanager: For DUN networking'
	    'pulseaudio: For switching device audio profiles')
provides=('bluetuith')
conflicts=('bluetuith')

source_x86_64=("https://github.com/darkhz/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_Linux_x86_64.tar.gz")
source_arm=("https://github.com/darkhz/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_Linux_armv5.tar.gz")
source_aarch64=("https://github.com/darkhz/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_Linux_arm64.tar.gz")
source_armv6h=("https://github.com/darkhz/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_Linux_armv6.tar.gz")
source_armv7h=("https://github.com/darkhz/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_${pkgver}_Linux_armv7.tar.gz")

sha256sums_aarch64=("7ea2ba0cbbff67493ef002ac31b08fe5a04ae5a5caee58beb448e1809ab5fdd9")
sha256sums_arm=("1e6e3cc6e2b7b3f1a841b0bf505683941b50d17647b0798c1c924a9d09b2febd")
sha256sums_armv6h=("80e3e94b99ba2cac45a462c8057ff68f5f051f731e02b5878a4a699edfe3e4cf")
sha256sums_armv7h=("23099897f574a5092a394167e4104ad9dbff536fa168eeda008349050dbd2d85")
sha256sums_i686=("d277981512fbf5347270b14c4b125e5e9c72b6e18450fefe23c262c6f3981137")
sha256sums_x86_64=("5ff0f5d199ffaac9517238ddc4be680785e5f7f956a116d7127284bb1d40cb2c")

package() {
  install -Dm 755 "${_pkgname}" -t "${pkgdir}/usr/bin"
}
