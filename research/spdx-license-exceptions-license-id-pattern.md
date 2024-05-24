# SPDX License Exceptions - License - Identifier - Pattern

| License Name | Identifier | Postfix Pattern |
| ------------ | ---------- | --------------- |
| 389 Directory Server Exception | 389-exception | |
| Asterisk exception | Asterisk-exception | |
| Asterisk linking protocols exception | Asterisk-linking-protocols-exception | |
| Autoconf exception 2.0 | Autoconf-exception-2.0 | |
| Autoconf exception 3.0 | Autoconf-exception-3.0 | |
| Autoconf generic exception | Autoconf-exception-generic | `(?!\-)` |
| Autoconf generic exception for GPL-3.0 | Autoconf-exception-generic-3.0 | |
| Autoconf macro exception | Autoconf-exception-macro | |
| Bison exception 1.24 | Bison-exception-1.24 | |
| Bison exception 2.2 | Bison-exception-2.2 | |
| Bootloader Distribution Exception | Bootloader-exception | |
| Classpath exception 2.0 | Classpath-exception-2.0 | |
| CLISP exception 2.0 | CLISP-exception-2.0 | |
| cryptsetup OpenSSL exception | cryptsetup-OpenSSL-exception | |
| DigiRule FOSS License Exception | DigiRule-FOSS-exception | |
| eCos exception 2.0 | eCos-exception-2.0 | |
| Fawkes Runtime Exception | Fawkes-Runtime-exception | |
| FLTK exception | FLTK-exception | |
| fmt exception | fmt-exception | |
| Font exception 2.0 | Font-exception-2.0 | |
| FreeRTOS Exception 2.0 | freertos-exception-2.0 | |
| GCC Runtime Library exception 2.0 | GCC-exception-2.0 | `(?!\-)` |
| GCC Runtime Library exception 2.0 - note variant | GCC-exception-2.0-note | |
| GCC Runtime Library exception 3.1 | GCC-exception-3.1 | |
| Gmsh exception | Gmsh-exception | |
| GNAT exception | GNAT-exception | |
| GNOME examples exception | GNOME-examples-exception | |
| GNU Compiler Exception | GNU-compiler-exception | |
| GNU JavaMail exception | gnu-javamail-exception | |
| GPL-3.0 Interface Exception | GPL-3.0-interface-exception | |
| GPL-3.0 Linking Exception | GPL-3.0-linking-exception | |
| GPL-3.0 Linking Exception (with Corresponding Source) | GPL-3.0-linking-source-exception | |
| GPL Cooperation Commitment 1.0 | GPL-CC-1.0 | |
| GStreamer Exception (2005) | GStreamer-exception-2005 | |
| GStreamer Exception (2008) | GStreamer-exception-2008 | |
| i2p GPL+Java Exception | i2p-gpl-java-exception | |
| KiCad Libraries Exception | KiCad-libraries-exception | |
| LGPL-3.0 Linking Exception | LGPL-3.0-linking-exception | |
| libpri OpenH323 exception | libpri-OpenH323-exception | |
| Libtool Exception | Libtool-exception | |
| Linux Syscall Note | Linux-syscall-note | |
| LLGPL Preamble | LLGPL | |
| LLVM Exception | LLVM-exception | |
| LZMA exception | LZMA-exception | |
| Macros and Inline Functions Exception | mif-exception | |
| OCaml LGPL Linking Exception | OCaml-LGPL-linking-exception | |
| Open CASCADE Exception 1.0 | OCCT-exception-1.0 | |
| OpenJDK Assembly exception 1.0 | OpenJDK-assembly-exception-1.0 | |
| OpenVPN OpenSSL Exception | openvpn-openssl-exception | |
| PCRE2 exception | PCRE2-exception | |
| PS/PDF font exception (2017-08-17) | PS-or-PDF-font-exception-20170817 | |
| INRIA QPL 1.0 2004 variant exception | QPL-1.0-INRIA-2004-exception | |
| Qt GPL exception 1.0 | Qt-GPL-exception-1.0 | |
| Qt LGPL exception 1.1 | Qt-LGPL-exception-1.1 | |
| Qwt exception 1.0 | Qwt-exception-1.0 | |
| RRDtool FLOSS exception 2.0 | RRDtool-FLOSS-exception-2.0 | |
| SANE Exception | SANE-exception | |
| Solderpad Hardware License v2.0 | SHL-2.0 | |
| Solderpad Hardware License v2.1 | SHL-2.1 | |
| stunnel Exception | stunnel-exception | |
| SWI exception | SWI-exception | |
| Swift Exception | Swift-exception | |
| Texinfo exception | Texinfo-exception | |
| U-Boot exception 2.0 | u-boot-exception-2.0 | |
| Unmodified Binary Distribution exception | UBDL-exception | |
| Universal FOSS Exception, Version 1.0 | Universal-FOSS-exception-1.0 | |
| vsftpd OpenSSL exception | vsftpd-openssl-exception | |
| WxWindows Library Exception 3.1 | WxWindows-exception-3.1 | |
| x11vnc OpenSSL Exception | x11vnc-openssl-exception | |

## Deprecated

| License Name | Identifier | Postfix Pattern |
| ------------ | ---------- | --------------- |
| Nokia Qt LGPL exception 1.1 | Nokia-Qt-exception-1.1 | |

## Common Pattern

### Prefix Pattern

```
(?:WITH\W*|SPDX\-Exception\-IdentifierW*)
```

### Escaping - Base Pattern

```
\+
\-
\.
```

### Postfix Pattern

```
(?![\+\-\.\w])
```

## Reference

### WITH

- [SPDX: Handling License Info](https://spdx.dev/learn/handling-license-info/)

```
WITH
```

### SPDX-Exception-Identifier:

- [Linux kernel licensing rules](https://www.kernel.org/doc/html/latest/process/license-rules.html)

```
SPDX-Exception-Identifier:
```
