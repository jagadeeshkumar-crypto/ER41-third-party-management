# Firmware Software Composition (SBOM)

| Layer | Component | Binary | Version Used | Latest Version | EOL | License | Use | URL |
|-------|-----------|--------|--------------|----------------|-----|--------|-----|-----|
| Bootloader | u-boot | xz_uncompressed | 2025.01 | 2025.10 | No official EOL (Upstream maintained) | GPL-2.0-only | Hardware initialization, Firmware loading, Boot control | [Link](https://docs.u-boot.org/en/stable/develop/release_cycle.html) |
| Kernel | linux_kernel | xz_uncompressed | 6.1.111 | 6.18 | Dec 2027 (LTS) | GPL-2.0-only | Core OS services, Device drivers, Networking stack | [Link](https://www.kernel.org/) |
| Kernel | linux_kernel | 0-4341760.unknown | 6.1.111 | 6.18 | Dec 2027 (LTS) | GPL-2.0-only | Not applicable | [Link](https://www.kernel.org/) |
| RootFS - Core Libraries | glibc | libc-2.42.so | 2.42 | 2.42 | No official EOL (Upstream maintained) | LGPL-2.1-or-later | C runtime and system APIs | [Link](https://www.gnu.org/software/libc/) |
| RootFS - Core Libraries | zlib | 8389512-82543496.ubifs | 1.3.1 | 1.3.1 | No official EOL (Upstream maintained) | Zlib | Compression support | [Link](https://www.zlib.net/fossils/) |
| RootFS - Core Libraries | zlib | libz.so.1.3.1 | 1.3.1 | 1.3.1 | No official EOL (Upstream maintained) | Zlib | Not applicable | [Link](https://www.zlib.net/fossils/) |
| RootFS - Security & Cryptography | openssl | 8389512-82543496.ubifs | 3.5.4 | 3.6 | 2030-04-08 (LTS) | OpenSSL OR Apache-2.0 | TLS and cryptographic services | [Link](https://openssl-library.org/source/) |
| RootFS - Security & Cryptography | openssl (stunnel dependency) | stunnel | 3.5.4 | 3.6 | No official EOL (Upstream maintained) | Not applicable | Not applicable | [Link](https://www.openssl.org/source/) |
| RootFS - Userland Utilities | busybox |busybox | 1.36.1 | 1.37 | No official EOL (Upstream maintained) | GPL-2.0-only | init, shell, core commands | [Link](https://busybox.net/downloads/) |
| RootFS - Userland Utilities | sed | busybox | 4.9 | 4.9 | No official EOL (Upstream maintained) | GPL-3.0-only | Text and config processing | [Link](https://ftp.gnu.org/gnu/sed/) |
| RootFS - Userland Utilities | udhcp | busybox | 1.36.1 | 1.37 | No official EOL (Upstream maintained) | GPL-2.0-only | Not applicable | [Link](https://busybox.net/downloads/) |
| RootFS - Filesystem Utilities | e2fsprogs | mke2fs | 1.47.2 | 1.47.3 | No official EOL (Upstream maintained) | No license identified | ext filesystem creation | [Link](https://e2fsprogs.sourceforge.net/) |
| RootFS - Networking Services | stunnel | 8389512-82543496.ubifs | 5.76 | 5.76 | No official EOL (Upstream maintained) | GPL-2.0-only | Not applicable | [Link](https://www.stunnel.org/) |
| RootFS - Networking Services | miniupnpd | miniupnpd | 2.3.0 | 2.3.9 | No official EOL (Upstream maintained) | GPL-2.0-only | Not applicable | [Link](https://miniupnp.tuxfamily.org/) |
| RootFS - Utilities | bc | ER41_2.7.13_5mm-V4.0_V30.1.01.20240418_25581063_Q_UKF_X_box | 7 | 1.08.2 | No official EOL (Upstream maintained) | GPL-3.0-or-later | Not applicable | [Link](https://www.gnu.org/software/bc/) |
