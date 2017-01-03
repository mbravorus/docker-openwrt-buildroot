docker-openwrt-buildroot
========================
[![License: MIT](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/noonien/docker-openwrt-buildroot/blob/master/LICENSE)


This is a docker container for the [OpenWRT](https://openwrt.org/)
[buildroot](http://wiki.openwrt.org/doc/howto/buildroot.exigence).

Because the build system requires that its command are not executed by root,
the user `openwrt` was created. The buildroot can be found in
`/home/openwrt/openwrt`.

To run a shell in the buildroot, execute the following command:
```sh
docker run -t -i mbravo/openwrt-stuff/openwrt-50033-ar71xx-generic-tl-wr941nd-v6 sudo -iu openwrt bash
```

More information on how to use this buildroot can be found on the
[OpenWRT wiki](http://wiki.openwrt.org/doc/howto/build).
