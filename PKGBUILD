# Maintainer:  Spencer Colton <me@scolton.tech>

pkgname='prc-tools-sc'
pkgver='2.3'
pkgrel='1'
pkgdesc='GCC for Palm OS'
arch=('x86_64')
url='http://gcc.gnu.org'
license=('GPL-2.0-only' 'LGPL-2.1-only' 'GPL-3.0-only' 'LGPL-3.0-only')
depends=('bash' 'libgcc' 'glibc')
makedepends=('flex' 'bison')
optdepends=('palm-os-sdk-git')
options=('!libtool' 'staticlibs' '!buildflags' 'debug')
conflicts=('prc-tools-remix')
provides=('prc-tools')
source=(
  "prc-tools-$pkgver.tar.gz::https://master.dl.sourceforge.net/project/prc-tools/prc-tools/$pkgver/prc-tools-$pkgver.tar.gz?viasf=1"
  "https://ftp.gnu.org/gnu/gcc/gcc-2.95.3.tar.gz"
  "https://ftp.gnu.org/gnu/gcc/gcc-3.3.1/gcc-core-3.3.1.tar.bz2"
  "https://ftp.gnu.org/gnu/gcc/gcc-3.3.1/gcc-g++-3.3.1.tar.bz2"
  "https://ftp.gnu.org/gnu/gdb/gdb-5.3.tar.gz"
  "https://ftp.gnu.org/gnu/binutils/binutils-2.14.tar.bz2"
  "0000-relax_type-tc-m68k-h.patch"
  "0001-relax_type-tc-m68k-c.patch"
  "0002-gdb-lv-obstack-h.patch"
  "0003-gdb-remote_timeout.patch"
  "0004-binutils-2.16.1-fix-ar.patch"
  "0005-gas-as-h.patch"
  "0006-gas-tc-h.patch"
  "0007-gcc-295-disable-makeinfo.patch"
  "0008-obstack-h.patch"
  "0009-gdb-obstack-h.patch"
  "0010-gcc3-decl-c.patch"
  "0011-config-cache.patch"
  "0012-basename.patch"
  "0013-destdir.patch"
  "M86k-PalmOS-GNU.yaml"
)

sha512sums=('d8dae2c03c4ec7ce1ec4ac2a72f301cce820daf0798114d5e12dbc6d5be278816b87609762c48c04e9d8485b93a4818cb6ad3daa7d762595e256117f68f14bf8'
            '50eb27613d5099bbcf2391b11d9818a7ff61f14fa0a01a04f956ce961cf59ccd32c4d7349ea18fdf29c2bec9126c3bda13e13715910b387c25b1bea1a557f485'
            'dac9c40fa301f5bbf7319a1b359c75e46c78ac1c057ffe3734c8b80b00ca3175d8ccf39efdf461d8b060375519c77340d64af47da306be327fbf96a6d399e463'
            '8ca95e613c91c5d3064704745a68160b5e829528645d08657e78a2000bd491db20ec8adb6a6fa53c124270467d96ee650e72422f0e11f5ede819d0e61ffb4f2d'
            'd887296078bf150922953f5d59f330a55f5d7820337884a4cefd4a19607bd7f0ad9e93edb43cc042d21d8303c67c276bec2a9a9289342e0eb8c0579bf7e402cd'
            'e54772795dd91eaba77f18d348d7c94d275b50d54ee7d4a77d9ed2cbdc3943e9603decd6cdbe4be10d444624e671e3aa9e9ad365fa0c7f88d8f35898e8b3ba8c'
            '0822baa65cb10c5ac74069772c3407bc922b9ff68c00221444f143dd0dd855f2e69b67a2b3881cd6a3fc2cf7a8b0084424b63ba909eb5ef528c3b08aa888bb35'
            '539c29d8bc916dcb233d94e1e22b9ee5bfcf0e48b8e58d5e7b1771c48c74adbe781c8fbe3b95c7204f7940f1ae273b826cbbc459f50d87f56681304a2bfc3ca9'
            'd52341abdc7f52c4f78a907a4e3626bbd29d0e0af840ea7e070abd6a8de747d0cc2e65768e3ae6ebc97a264c7fef6cbf3a4051e935b582e9679914deae6d1578'
            'd9ca52757e9ce0ed9fa966c0adb61897bd8c6ebc72937a43ff01446c0ac2fb40c2a4f141ed0b7e149e76ec988ce870d65a4ccc6d299025e2281ffa1245bef619'
            'cc282b46feb41a4e28d76f2d958f18138461e429f4565b555fa21d74890e10b308fb61bc0f9fa3775ddc772dfdf141038585acef88a95371ede9263fd83d6c25'
            'd543d6600df0d1a83dce38674c08330bec64a2adb3dc3ba2daa6250e69a776fb7c2b1c29fe0723ab7c0e7a9c556cdb8ffb387cd22643c759b25819183aca76c8'
            'b7c3acceb1cae7efea457684d1c3e2caeac2917120092497195744dfa4c52816eaf4ce865133d7643247e084711cf2de3982152921abf20d4a0726337e1eb877'
            '13f2865e190130ea962a29ac2e037afcc1791309ba536bf03b30014b627199ee07101cf786e231384291089338b6dee13ea36e754851605c9f815053984fd368'
            '418bddf3f8dc409e2f010071ed1ea2d580a02c9e93955a28c609bc02f9f5968ccbdd472dc5c7cf428f09ee726639f73a128f0e22434b1946b64bb05009980c55'
            '812559c66a812a391c83901cd951cef5f3e47d3bd7bf10cc64d4d410473bf6bba75635cfefdfe9305e7ef4a07c0940b557d2fa7d9b46be8dd860e35627073f23'
            'abad834fd77ab21ceea3377c83e04bc20c5223e5895447dfa60dd61fc666d7c49fc99394c4ac6cc24405dc1d22cf24e73c477e8d9a9eebe79fef23ff7e28cf18'
            '06841daccaad3eca1088ab28d66a6ef5f90cf42c31bdff044cb25388a3a66e3c3bd547ad3b057311da31f23a1cdcf4439748c759d8021d82373295236d968bee'
            'b8000b51effe2ad34e11556865de443af0a528ad8bf63c9daf386bd168bca501684ee2dde8074cffe89d028ee8b8f1e1ab2ce8431c6a02a9b812edeaf6952127'
            '3c155609236166ba6a4545a4d55a9ec121a2caff8a6c1512eb4df9609913e27189358fcbde451ddfcb15ab698900d37da7fdcac476a2ec2d29eb263292ea30fc'
            '7fb3dab2bdbf7cddd2fce883964a76e001816c4d9c147e9892574fc1beafb7f44e949bd21380bfcb32d203a3cb7dbc829ed2c6748d66e20d8d453cc41cae4b85')

prepare() {
  rm -f \
    gcc-3.3.1/gcc/config/arm/palmos.h \
    gcc-3.3.1/gcc/config/palmos.h \
    gcc-3.3.1/gcc/config/t-palmos \
    gdb-5.3/gdb/ChangeLog.palmos \
    gdb-5.3/gdb/config/m68k/palmos.mt \
    gdb-5.3/gdb/config/m68k/tm-palmos.h \
    gdb-5.3/gdb/remote-palmos.c \
    binutils-2.14/ChangeLogs.palmos \
    binutils-2.14/bfd/prc-arm.c \
    binutils-2.14/bfd/prc-m68k.c \
    binutils-2.14/bfd/prc.c \
    binutils-2.14/bfd/prc.h \
    binutils-2.14/ld/emulparams/armpalmos.sh \
    binutils-2.14/ld/emulparams/m68kpalmos.sh \
    binutils-2.14/ld/scripttempl/armpalmos.sc \
    binutils-2.14/ld/scripttempl/m68kpalmos.sc \
    gcc-2.95.3/gcc/ChangeLog.palmos \
    gcc-2.95.3/gcc/config/arm/palmos.h \
    gcc-2.95.3/gcc/config/m68k/fpexcept.c \
    gcc-2.95.3/gcc/config/m68k/fpexcept.c \
    gcc-2.95.3/gcc/config/m68k/lb1sf68palmos.asm \
    gcc-2.95.3/gcc/config/m68k/m68kpalmos.h \
    gcc-2.95.3/gcc/config/m68k/t-m68kpalmos \
    gcc-2.95.3/gcc/config/m68k/xm-m68kpalmos.h \
    gcc-2.95.3/gcc/config/rs6000/x-darwin \
    gcc-2.95.3/gcc/config/t-palmos


  cat prc-tools-"$pkgver"/*.palmos.diff | patch -p0 -f

  # patch -p0 -i 0000-relax_type-tc-m68k-h.patch
  # patch -p0 -i 0001-relax_type-tc-m68k-c.patch
  # patch -p0 -i 0002-gdb-lv-obstack-h.patch
  patch -p0 -i 0003-gdb-remote_timeout.patch
  patch -p0 -i 0004-binutils-2.16.1-fix-ar.patch
  patch -p0 -i 0005-gas-as-h.patch
  patch -p0 -i 0006-gas-tc-h.patch
  patch -p0 -i 0007-gcc-295-disable-makeinfo.patch
  patch -p0 -i 0008-obstack-h.patch
  patch -p0 -i 0009-gdb-obstack-h.patch
  patch -p0 -i 0010-gcc3-decl-c.patch
  patch -p0 -i 0011-config-cache.patch
  patch -p0 -i 0012-basename.patch
  patch -p0 -i 0013-destdir.patch

  pushd "$srcdir/prc-tools-$pkgver"
  ln -s ../binutils-2.14 binutils
  ln -s ../gdb-5.3 gdb
  ln -s ../gcc-2.95.3 gcc295
  ln -s ../gcc-3.3.1 gcc
  popd

  mkdir -p "$srcdir/build"
}

build() {
  cd "$srcdir/build"

  options=(
    '--enable-targets=m68k-palmos'
    '--enable-languages=c,c++'
    "--prefix=/usr"
    "--infodir=/usr/share/info"
    "--mandir=/usr/share/man"
    '--host=i686-pc-linux-gnu'
    '--build=i686-pc-linux-gnu'
    '--with-palmdev-prefix=/opt/palmdev'
    '--disable-nls'
  )

  CFLAGS="-std=gnu89 -w -O1 -fcommon -fno-strict-aliasing -g"

  CFLAGS="$CFLAGS" \
    ../prc-tools-"$pkgver"/configure \
    "${options[@]}"

  CFLAGS="$CFLAGS" \
    make -j1
}

package() {
  cd "$srcdir/build"
  make DESTDIR="$pkgdir" MAKEINFO=true -j1 install

  rmdir "$pkgdir/usr/include"
  rm -f "$pkgdir/usr/lib/*.a"
  rm -f "$pkgdir/usr/share/info/*"
  rm -rf "$pkgdir/usr/share/man"
  rm -rf "$pkgdir/usr/share/info"
  rm -rf "$pkgdir/usr/lib/libiberty.a"

  mkdir -p "$pkgdir/usr/share/prc-tools"
  cp "$srcdir"/M86k-PalmOS-GNU.yaml "$pkgdir/usr/share/prc-tools"
}
