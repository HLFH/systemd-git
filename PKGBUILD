# Maintainer: Yurii Kolesnykov <root@yurikoles.com>
# Based on testing/systemd by Christian Hesse <mail@eworm.de>

_pkgbase=systemd
pkgbase=${_pkgbase}-git
pkgname=('systemd-git' 'systemd-libs-git' 'systemd-resolvconf-git' 'systemd-sysvcompat-git')
pkgdesc='systemd (git version)'
pkgver=252.r61711.71eaa9291d
pkgrel=1
arch=('x86_64')
url='https://www.github.com/systemd/systemd'
makedepends=('acl' 'cryptsetup' 'docbook-xsl' 'gperf' 'lz4' 'xz' 'pam' 'libelf'
             'intltool' 'iptables' 'kmod' 'libcap' 'libidn2' 'libgcrypt'
             'libmicrohttpd' 'libxcrypt' 'libxslt' 'util-linux' 'linux-api-headers'
             'python-jinja' 'python-lxml' 'quota-tools' 'shadow' 'gnu-efi-libs' 'git'
             'meson' 'libseccomp' 'pcre2' 'audit' 'kexec-tools' 'libxkbcommon'
             'bash-completion' 'p11-kit' 'systemd' 'libfido2' 'tpm2-tss' 'rsync'
             'bpf' 'libbpf' 'clang' 'llvm')
source=('git+https://github.com/systemd/systemd'
        '0001-Use-Arch-Linux-device-access-groups.patch'
        'initcpio-hook-udev'
        'initcpio-install-systemd'
        'initcpio-install-udev'
        'arch.conf'
        'loader.conf'
        'splash-arch.bmp'::'https://github.com/archlinux/svntogit-packages/raw/packages/systemd/trunk/splash-arch.bmp'
        'systemd-user.pam'
        'systemd-hook'
        '20-systemd-sysusers.hook'
        '30-systemd-binfmt.hook'
        '30-systemd-catalog.hook'
        '30-systemd-daemon-reload.hook'
        '30-systemd-hwdb.hook'
        '30-systemd-sysctl.hook'
        '30-systemd-tmpfiles.hook'
        '30-systemd-udev-reload.hook'
        '30-systemd-update.hook')
sha512sums=('SKIP'
            '3ccf783c28f7a1c857120abac4002ca91ae1f92205dcd5a84aff515d57e706a3f9240d75a0a67cff5085716885e06e62597baa86897f298662ec36a940cf410e'
            'f0d933e8c6064ed830dec54049b0a01e27be87203208f6ae982f10fb4eddc7258cb2919d594cbfb9a33e74c3510cfd682f3416ba8e804387ab87d1a217eb4b73'
            'aeefb607471cffb5ed4c3d9f36dc0954a9a08cee4b7b4ff55468b561e089e3d8448398906a7df328049ba51b712e4d50698b96bc152bdb03a35ce39c3f51a7cb'
            'a8c7e4a2cc9c9987e3c957a1fc3afe8281f2281fffd2e890913dcf00cf704024fb80d86cb75f9314b99b0e03bac275b22de93307bfc226d8be9435497e95b7e6'
            '61032d29241b74a0f28446f8cf1be0e8ec46d0847a61dadb2a4f096e8686d5f57fe5c72bcf386003f6520bc4b5856c32d63bf3efe7eb0bc0deefc9f68159e648'
            'c416e2121df83067376bcaacb58c05b01990f4614ad9de657d74b6da3efa441af251d13bf21e3f0f71ddcb4c9ea658b81da3d915667dc5c309c87ec32a1cb5a5'
            '5a1d78b5170da5abe3d18fdf9f2c3a4d78f15ba7d1ee9ec2708c4c9c2e28973469bc19386f70b3cf32ffafbe4fcc4303e5ebbd6d5187a1df3314ae0965b25e75'
            'b90c99d768dc2a4f020ba854edf45ccf1b86a09d2f66e475de21fe589ff7e32c33ef4aa0876d7f1864491488fd7edb2682fc0d68e83a6d4890a0778dc2d6fe19'
            '217a9dc3f9d8cd0c9fee54f777396f5a270c2e8a30c572ce5f635165adadcec275af0dae1456019cedb9cc93b7cef0862e5070aeb99a19e496625200e8dfac93'
            '299dcc7094ce53474521356647bdd2fb069731c08d14a872a425412fcd72da840727a23664b12d95465bf313e8e8297da31259508d1c62cc2dcea596160e21c5'
            '0d6bc3d928cfafe4e4e0bc04dbb95c5d2b078573e4f9e0576e7f53a8fab08a7077202f575d74a3960248c4904b5f7f0661bf17dbe163c524ab51dd30e3cb80f7'
            '2b50b25e8680878f7974fa9d519df7e141ca11c4bfe84a92a5d01bb193f034b1726ea05b3c0030bad1fbda8dbb78bf1dc7b73859053581b55ba813c39b27d9dc'
            '63e55b3acd14bc54320b6f2310b43398651ad4e262d4f4a0135e05d34a993e56ed673cc46e57f15b418371df5c4cef6f54486db96325e4abb1d33fb1a3946254'
            'a1661ab946c6cd7d3c6251a2a9fd68afe231db58ce33c92c42594aedb5629be8f299ba08a34713327b373a3badd1554a150343d8d3e5dfb102999c281bd49154'
            '9426829605bbb9e65002437e02ed54e35c20fdf94706770a3dc1049da634147906d6b98bf7f5e7516c84068396a12c6feaf72f92b51bdf19715e0f64620319de'
            'da7a97d5d3701c70dd5388b0440da39006ee4991ce174777931fea2aa8c90846a622b2b911f02ae4d5fffb92680d9a7e211c308f0f99c04896278e2ee0d9a4dc'
            'a50d202a9c2e91a4450b45c227b295e1840cc99a5e545715d69c8af789ea3dd95a03a30f050d52855cabdc9183d4688c1b534eaa755ebe93616f9d192a855ee3'
            '825b9dd0167c072ba62cabe0677e7cd20f2b4b850328022540f122689d8b25315005fa98ce867cf6e7460b2b26df16b88bb3b5c9ebf721746dce4e2271af7b97')

pkgver() {
  cd "$_pkgbase"
  local _major=`grep -m1 version meson.build | cut -d\' -f2`
  printf "%s.r%s.%s" "${_major}" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
}

prepare() {
  cd "$_pkgbase"

  # Replace cdrom/dialout/tape groups with optical/uucp/storage
  patch -Np1 -i ../0001-Use-Arch-Linux-device-access-groups.patch
}

build() {
  local _timeservers=({0..3}.arch.pool.ntp.org)
  local _nameservers=(
    # We use these public name services, ordered by their privacy policy (hopefully):
    #  * Cloudflare (https://1.1.1.1/)
    #  * Quad9 (https://www.quad9.net/)
    #  * Google (https://developers.google.com/speed/public-dns/)
    '1.1.1.1#cloudflare-dns.com'
    '9.9.9.9#dns.quad9.net'
    '8.8.8.8#dns.google'
    '2606:4700:4700::1111#cloudflare-dns.com'
    '2620:fe::9#dns.quad9.net'
    '2001:4860:4860::8888#dns.google'
  )

  local _meson_options=(
    # internal version comparison is incompatible with pacman:
    #   249~rc1 < 249 < 249.1 < 249rc
    -Dversion-tag="${pkgver}-${pkgrel}-arch"
    -Dshared-lib-tag="${pkgver}-${pkgrel}"
    -Dmode=release

    -Dbpf-framework=true
    -Dgnu-efi=true
    -Dima=false
    -Dlibidn2=true
    -Dlz4=true
    -Dman=true

    # We disable DNSSEC by default, it still causes trouble:
    # https://github.com/systemd/systemd/issues/10579
    
    -Ddbuspolicydir=/usr/share/dbus-1/system.d
    -Ddefault-dnssec=no
    -Ddefault-hierarchy=unified
    -Ddefault-kill-user-processes=false
    -Ddefault-locale='C.UTF-8'
    -Dlocalegen-path=/usr/bin/locale-gen
    -Ddns-over-tls=openssl
    -Dfallback-hostname='archlinux'
    -Dnologin-path=/usr/bin/nologin
    -Dntp-servers="${_timeservers[*]}"
    -Ddns-servers="${_nameservers[*]}"
    -Drpmmacrosdir=no
    -Dsysvinit-path=
    -Dsysvrcnd-path=

    -Dsbat-distro='arch'
    -Dsbat-distro-summary='Arch Linux AUR'
    -Dsbat-distro-pkgname="${pkgname}"
    -Dsbat-distro-version="${pkgver}"
    -Dsbat-distro-url="https://aur.archlinux.org/pkgbase/${pkgname}"
  )

  arch-meson "$_pkgbase" build "${_meson_options[@]}"

  meson compile -C build
}

check() {
  meson test -C build
}

package_systemd-git() {
  pkgdesc='system and service manager'
  pkgdesc+=' (git version)'
  license=('GPL2' 'LGPL2.1')
  depends=('acl' 'libacl.so' 'bash' 'cryptsetup' 'libcryptsetup.so' 'dbus'
           'iptables' 'kbd' 'kmod' 'libkmod.so' 'hwdata' 'libcap' 'libcap.so'
           'libgcrypt' 'libxcrypt' 'libcrypt.so' 'systemd-libs-git' 'libidn2' 'lz4' 'pam'
           'libelf' 'libseccomp' 'libseccomp.so' 'util-linux' 'libblkid.so'
           'libmount.so' 'xz' 'pcre2' 'audit' 'libaudit.so' 'libp11-kit'
           'libp11-kit.so' 'openssl' 'libcrypto.so' 'libssl.so')
  provides=('nss-myhostname' "systemd-tools=$pkgver" "udev=$pkgver")
  provides+=("systemd=$pkgver")
  replaces=('nss-myhostname' 'systemd-tools' 'udev')
  conflicts=('nss-myhostname' 'systemd-tools' 'udev')
  conflicts+=('systemd')
  optdepends=('libmicrohttpd: remote journald capabilities'
              'quota-tools: kernel-level quota management'
              'systemd-sysvcompat: symlink package to provide sysvinit binaries'
              'polkit: allow administration as unprivileged user'
              'curl: machinectl pull-tar and pull-raw'
              'libbpf: support BPF programs'
              'libfido2: unlocking LUKS2 volumes with FIDO2 token'
              'tpm2-tss: unlocking LUKS2 volumes with TPM2')
  backup=(etc/pam.d/systemd-user
          etc/systemd/coredump.conf
          etc/systemd/homed.conf
          etc/systemd/journald.conf
          etc/systemd/journal-remote.conf
          etc/systemd/journal-upload.conf
          etc/systemd/logind.conf
          etc/systemd/networkd.conf
          etc/systemd/oomd.conf
          etc/systemd/pstore.conf
          etc/systemd/resolved.conf
          etc/systemd/sleep.conf
          etc/systemd/system.conf
          etc/systemd/timesyncd.conf
          etc/systemd/user.conf
          etc/udev/udev.conf)
  install=systemd.install

  meson install -C build --destdir "$pkgdir"

  # we'll create this on installation
  rmdir "$pkgdir"/var/log/journal/remote

  # runtime libraries shipped with systemd-libs
  install -d -m0755 systemd-libs
  mv "$pkgdir"/usr/lib/lib{nss,systemd,udev}*.so* systemd-libs

  # manpages shipped with systemd-sysvcompat
  rm "$pkgdir"/usr/share/man/man8/{halt,poweroff,reboot,shutdown}.8

  # executable (symlinks) shipped with systemd-sysvcompat
  rm "$pkgdir"/usr/bin/{halt,init,poweroff,reboot,shutdown}

  # files shipped with systemd-resolvconf
  rm "$pkgdir"/usr/{bin/resolvconf,share/man/man1/resolvconf.1}

  # avoid a potential conflict with [core]/filesystem
  rm "$pkgdir"/usr/share/factory/etc/{issue,nsswitch.conf}
  sed -i -e '/^C \/etc\/nsswitch\.conf/d' \
    -e '/^C \/etc\/issue/d' "$pkgdir"/usr/lib/tmpfiles.d/etc.conf

  # ship default policy to leave services disabled
  echo 'disable *' >"$pkgdir"/usr/lib/systemd/system-preset/99-default.preset

  # add mkinitcpio hooks
  install -D -m0644 initcpio-install-systemd "$pkgdir"/usr/lib/initcpio/install/systemd
  install -D -m0644 initcpio-install-udev "$pkgdir"/usr/lib/initcpio/install/udev
  install -D -m0644 initcpio-hook-udev "$pkgdir"/usr/lib/initcpio/hooks/udev

  # The group 'systemd-journal' is allocated dynamically and may have varying
  # gid on different systems. Let's install with gid 0 (root), systemd-tmpfiles
  # will fix the permissions for us. (see /usr/lib/tmpfiles.d/systemd.conf)
  install -d -o root -g root -m 2755 "$pkgdir"/var/log/journal

  # match directory owner/group and mode from [extra]/polkit
  install -d -o root -g 102 -m 0750 "$pkgdir"/usr/share/polkit-1/rules.d

  # add example bootctl configuration
  install -D -m0644 arch.conf "$pkgdir"/usr/share/systemd/bootctl/arch.conf
  install -D -m0644 loader.conf "$pkgdir"/usr/share/systemd/bootctl/loader.conf
  install -D -m0644 splash-arch.bmp "$pkgdir"/usr/share/systemd/bootctl/splash-arch.bmp

  # pacman hooks
  install -D -m0755 systemd-hook "$pkgdir"/usr/share/libalpm/scripts/systemd-hook
  install -D -m0644 -t "$pkgdir"/usr/share/libalpm/hooks *.hook

  # overwrite the systemd-user PAM configuration with our own
  install -D -m0644 systemd-user.pam "$pkgdir"/etc/pam.d/systemd-user
}

package_systemd-libs-git() {
  pkgdesc='systemd client libraries'
  pkgdesc+=' (git version)'
  depends=('glibc' 'libcap' 'libgcrypt' 'libp11-kit' 'lz4' 'xz' 'zstd')
  license=('LGPL2.1')
  provides=('libsystemd' 'libsystemd.so' 'libudev.so')
  provides+=("systemd-libs=$pkgver")
  conflicts=('libsystemd')
  conflicts+=('systemd-libs')
  replaces=('libsystemd')

  install -d -m0755 "$pkgdir"/usr
  mv systemd-libs "$pkgdir"/usr/lib
}

package_systemd-resolvconf-git() {
  pkgdesc='systemd resolvconf replacement (for use with systemd-resolved)'
  pkgdesc+=' (git version)'
  license=('LGPL2.1')
  depends=('systemd-git')
  provides=('openresolv' 'resolvconf')
  provides+=("systemd-resolvconf=$pkgver")
  conflicts=('openresolv')
  conflicts+=('systemd-resolvconf')

  install -d -m0755 "$pkgdir"/usr/bin
  ln -s resolvectl "$pkgdir"/usr/bin/resolvconf

  install -d -m0755 "$pkgdir"/usr/share/man/man1
  ln -s resolvectl.1.gz "$pkgdir"/usr/share/man/man1/resolvconf.1.gz
}

package_systemd-sysvcompat-git() {
  pkgdesc='sysvinit compat for systemd'
  pkgdesc+=' (git version)'
  license=('GPL2')
  conflicts=('sysvinit')
  conflicts+=('systemd-sysvcompat')
  depends=('systemd-git')
  provides=("systemd-sysvcompat=$pkgver")

  install -D -m0644 -t "$pkgdir"/usr/share/man/man8 \
    build/man/{halt,poweroff,reboot,shutdown}.8

  install -d -m0755 "$pkgdir"/usr/bin
  ln -s ../lib/systemd/systemd "$pkgdir"/usr/bin/init
  for tool in halt poweroff reboot shutdown; do
    ln -s systemctl "$pkgdir"/usr/bin/$tool
  done
}
