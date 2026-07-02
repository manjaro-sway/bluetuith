# Maintainer: darkhz <kmachanwenw at gmail dot com>
pkgname=bluetuith
_pkgname=bluetuith
pkgver=0.2.7
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

sha256sums_aarch64=("81ec8bdbdf18ddabff0ce5fb11f478dfa8dccbd9efc8e14583d4cbb8ef0f8d84")
sha256sums_arm=("2c52000affdbdae7cdefe66edb8292429aec2bfb2f14d6f306d6a12d9089376e")
sha256sums_armv6h=("186d314023715a2c94b0a96ba1bc6829b93864de96a75f547fd74efecda9cce9")
sha256sums_armv7h=("bc2a86074d76bda44736d9ff9fbb91bf07857b962a5843a028a69c5bb7cc6e80")
sha256sums_i686=("4d5577e3fa67f31951cb25137ce87b8ec3cb7ff17b78bbba9908f30126a046cb")
sha256sums_x86_64=("145888f0e3959d29832c7395403c2327e0f03b9591e4cdd3f712741cf0f934e9")

package() {
  install -Dm 755 "${_pkgname}" -t "${pkgdir}/usr/bin"
}
