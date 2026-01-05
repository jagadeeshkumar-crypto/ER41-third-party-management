# Firmware SBOM – Component Roles
| Layer        | Component                     | Version Used | License              | Role                                                                           |
| ------------ | ----------------------------- | ------------ | -------------------- | ------------------------------------------------------------------------------ |
| Bootloader   | U-Boot                        | 2025.01      | GPL-2.0-only         | Starts the device, initializes hardware, and hands control to the Linux kernel |
| Kernel       | Linux Kernel                  | 6.1.111      | GPL-2.0-only         | Runs the operating system and manages hardware and system resources            |
| Kernel       | Linux Kernel (Firmware Image) | 6.1.111      | GPL-2.0-only         | Provides kernel runtime support within the firmware                            |
| Core Library | glibc                         | 2.42         | LGPL-2.1-or-later    | Provides basic system functions for applications                               |
| Core Library | zlib                          | 1.3.1        | Zlib                 | Supports data compression for system and applications                          |
| Security     | OpenSSL                       | 3.5.4        | OpenSSL / Apache-2.0 | Enables encryption and secure communication                                    |
| User Utility | BusyBox                       | 1.36.1       | GPL-2.0-only         | Provides essential system commands and startup utilities                       |
| User Utility | sed                           | 4.9          | GPL-3.0-only         | Edits configuration and text files                                             |
| User Utility | udhcp                         | 1.36.1       | GPL-2.0-only         | Automatically configures network settings                                      |
| Filesystem   | e2fsprogs                     | 1.47.2       | NA                   | Creates and maintains Linux filesystems                                        |
| Networking   | stunnel                       | 5.76         | GPL-2.0-only         | Secures data sent over the network                                             |
| Networking   | miniupnpd                     | 2.3.0        | GPL-2.0-only         | Automatically manages network ports                                            |
| Utility      | bc                            | 7            | GPL-3.0-or-later     | Performs calculations needed by system scripts                                 |

