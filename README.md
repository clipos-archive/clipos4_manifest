# CLIP OS 4

To download all the necessary files, first ensure to have installed the Git LFS filters hooks for Git with the following command:
```console
git-lfs install --skip-repo
```

This step is required to be done *before synchronizing* the whole source tree and allows to automatically download the files stored within the Git LFS server when Repo checks out the Git LFS-backed repositories of the source tree (i.e.  distfiles and artifacts).

Then, you can use [Repo](https://gerrit.googlesource.com/git-repo/) to get the sources, the distfiles and the artifacts:
```console
mkdir clipos4
cd clipos4
repo init -u https://github.com/clipos-archive/clipos4_manifest
repo sync
```

## [Documentation](https://github.com/clipos-archive/clipos4_doc)

## [Artifacts](https://github.com/clipos-archive/clipos4_artifacts)

## Package repositories (clip-int)

* [distfiles](https://github.com/clipos-archive/clipos4_distfiles)
* [portage](https://github.com/clipos-archive/clipos4_portage)
* [portage-overlay](https://github.com/clipos-archive/clipos4_portage-overlay)
* [portage-overlay-clip](https://github.com/clipos-archive/clipos4_portage-overlay-clip)
* [portage-overlay-dev](https://github.com/clipos-archive/clipos4_portage-overlay-dev)
* [specs](https://github.com/clipos-archive/clipos4_specs)

## Custom developments (clip-dev)

* [anssipki-cli: ANSSI-PKI command-line interface](https://github.com/clipos-archive/src_platform_anssipki-cli)
* [baselayout-clip: Filesystem baselayout and init scripts for CLIP](https://github.com/clipos-archive/src_platform_baselayout-clip)
* [baselayout-rm: Baselayout for rm vservers](https://github.com/clipos-archive/src_platform_baselayout-rm)
* [baselayout-update: Baselayout for update view](https://github.com/clipos-archive/src_platform_baselayout-update)
* [bionic-malloc: Safer memory allocator from Android's bionic libc](https://github.com/clipos-archive/src_platform_bionic-malloc)
* [chroot-launch: launch chroot'ed programs as a non-priv user](https://github.com/clipos-archive/src_platform_chroot-launch)
* [ckiutl: PKCS#11 utility](https://github.com/clipos-archive/src_platform_ckiutl)
* [clip-beacon: Sends information to device management system](https://github.com/clipos-archive/src_platform_clip-beacon)
* [clip-buildbot: CLIP hardened build bot](https://github.com/clipos-archive/src_platform_clip-buildbot)
* [clip-build: build clip fake roots](https://github.com/clipos-archive/src_platform_clip-build)
* [CLIP-Conf-Base: common CLIP configuration import functions](https://github.com/clipos-archive/src_platform_CLIP-Conf-Base)
* [clip-config: graphical configuration tool](https://github.com/clipos-archive/src_platform_clip-config)
* [clip-deb: utilities to generate .deb packages from portage](https://github.com/clipos-archive/src_platform_clip-deb)
* [clip-devutils: Misc devel utilities for CLIP](https://github.com/clipos-archive/src_platform_clip-devutils)
* [clip-download: tool to download CLIP updates for clip distribution](https://github.com/clipos-archive/src_platform_clip-download)
* [clip-emblem: CLIP emblem library](https://github.com/clipos-archive/src_platform_clip-emblem)
* [clip-eraser: Clip eraser](https://github.com/clipos-archive/src_platform_clip-eraser)
* [clip-generic-net: Generic network initialization scripts for clip](https://github.com/clipos-archive/src_platform_clip-generic-net)
* [clip-gtw-net: Network initialization scripts and conf files for clip gateways](https://github.com/clipos-archive/src_platform_clip-gtw-net)
* [clip-hardware: Hardware configurations for clip-installer](https://github.com/clipos-archive/src_platform_clip-hardware)
* [clip-icons: CLIP OS 4 icon set](https://github.com/clipos-archive/src_platform_clip-icons)
* [clip-install-clip: tool to install CLIP updates for clip distribution](https://github.com/clipos-archive/src_platform_clip-install-clip)
* [clip-install-common: tool to install CLIP updates](https://github.com/clipos-archive/src_platform_clip-install-common)
* [clip-install-config: graphical configuration tool for clip-installer profiles](https://github.com/clipos-archive/src_platform_clip-install-config)
* [clip-installer: Simple local installer for CLIP](https://github.com/clipos-archive/src_platform_clip-installer)
* [clip-install-gui: Graphical installer for CLIP](https://github.com/clipos-archive/src_platform_clip-install-gui)
* [clip-install-rm: tool to install CLIP updates for rm distribution](https://github.com/clipos-archive/src_platform_clip-install-rm)
* [clip-lib: Library regrouping all clip helper functions](https://github.com/clipos-archive/src_platform_clip-lib)
* [clip-libvserver: Library regrouping all clip vserver helper functions](https://github.com/clipos-archive/src_platform_clip-libvserver)
* [clip-livecd: Tools allowing the creation of an installation disk for CLIP](https://github.com/clipos-archive/src_platform_clip-livecd)
* [CLIP-Logger: common CLIP perl modules logging functions](https://github.com/clipos-archive/src_platform_CLIP-Logger)
* [clip-lsm: CLIP-LSM (Linux Security Module)](https://github.com/clipos-archive/src_platform_clip-lsm)
* [clip-mdadm-clt: Software RAID client tool](https://github.com/clipos-archive/src_platform_clip-mdadm-clt)
* [clip-mdadm: Software RAID management tools](https://github.com/clipos-archive/src_platform_clip-mdadm)
* [clip-menu-xdg: Clip dynamic menus](https://github.com/clipos-archive/src_platform_clip-menu-xdg)
* [CLIP-Mount: common CLIP mount / umount functions](https://github.com/clipos-archive/src_platform_CLIP-Mount)
* [clip-netd: Networking config restarter daemon](https://github.com/clipos-archive/src_platform_clip-netd)
* [clip-net: Network initialization scripts and conf files for clip](https://github.com/clipos-archive/src_platform_clip-net)
* [clip-patches: Set of Linux patches for CLIP OS](https://github.com/clipos-archive/src_platform_clip-patches)
* [CLIP-Pkg-Base: common CLIP package management functions](https://github.com/clipos-archive/src_platform_CLIP-Pkg-Base)
* [clip-pkgdb: A tool to link metadata to packages in a standalone text database optimized for version control systems](https://github.com/clipos-archive/src_platform_clip-pkgdb)
* [CLIP-Pkg-Download: CLIP package download functions](https://github.com/clipos-archive/src_platform_CLIP-Pkg-Download)
* [CLIP-Pkg-Install: CLIP package install functions](https://github.com/clipos-archive/src_platform_CLIP-Pkg-Install)
* [CLIP-Pkg-QA: common CLIP package QA functions](https://github.com/clipos-archive/src_platform_CLIP-Pkg-QA)
* [ClipQt: Generic Qt code for CLIP](https://github.com/clipos-archive/src_platform_ClipQt)
* [clip-sub: Common CLIP core subroutines](https://github.com/clipos-archive/src_platform_clip-sub)
* [clip-test-box](https://github.com/clipos-archive/src_platform_clip-test-box)
* [clip-tests: Miscellaneous security tests for CLIP](https://github.com/clipos-archive/src_platform_clip-tests)
* [clip-update-user-data: Clip update user data](https://github.com/clipos-archive/src_platform_clip-update-user-data)
* [clip-usb-clt: Usb keys client tool](https://github.com/clipos-archive/src_platform_clip-usb-clt)
* [clip-usb-keys: USB keys management tools](https://github.com/clipos-archive/src_platform_clip-usb-keys)
* [clip-useradmin: CLIP user management tools](https://github.com/clipos-archive/src_platform_clip-useradmin)
* [clip-user-mount: Per-user temporary mounts management for CLIP](https://github.com/clipos-archive/src_platform_clip-user-mount)
* [clip-viewer: CLIP Viewer app for html / plain text logs and help files](https://github.com/clipos-archive/src_platform_clip-viewer)
* [clip-vpn-net: Custom gateway network initialization scripts for clip](https://github.com/clipos-archive/src_platform_clip-vpn-net)
* [clip-vserver: clip servers - start and stop clip vservers](https://github.com/clipos-archive/src_platform_clip-vserver)
* [clip-wallpapers: CLIP OS 4 wallpaper set](https://github.com/clipos-archive/src_platform_clip-wallpapers)
* [core-services: core services for CLIP : core update, etc...](https://github.com/clipos-archive/src_platform_core-services)
* [cryptclt: cryptd GUI clients](https://github.com/clipos-archive/src_platform_cryptclt)
* [cryptd: inter-jail encryption/decryption daemon](https://github.com/clipos-archive/src_platform_cryptd)
* [debootstrap-clip: Debian bootstrap scripts for clip](https://github.com/clipos-archive/src_platform_debootstrap-clip)
* [downloadrequest: clip-download client for the admin view](https://github.com/clipos-archive/src_platform_downloadrequest)
* [fbpanel-clip: Custom fbpanel for CLIP](https://github.com/clipos-archive/src_platform_fbpanel-clip)
* [fdp: File Descriptor Passing helpers and library](https://github.com/clipos-archive/src_platform_fdp)
* [gen-crypt: Signature creation / verification tool](https://github.com/clipos-archive/src_platform_gen-crypt)
* [hotplug-clip: Hotplug event handler for CLIP](https://github.com/clipos-archive/src_platform_hotplug-clip)
* [init-cleaner](https://github.com/clipos-archive/src_platform_init-cleaner)
* [jailmaster: launch chrooted services in a vserver jail](https://github.com/clipos-archive/src_platform_jailmaster)
* [jailrequest: poke a jail'ed jailmaster from outside the jail](https://github.com/clipos-archive/src_platform_jailrequest)
* [libanssipki-client: ANSSI-PKI client library](https://github.com/clipos-archive/src_platform_libanssipki-client)
* [libanssipki-crypto: Library regrouping all ANSSI PKI cryptographic functions](https://github.com/clipos-archive/src_platform_libanssipki-crypto)
* [openbsd-malloc: Safer memory allocator from OpenBSD libc](https://github.com/clipos-archive/src_platform_openbsd-malloc)
* [pam_exec_pwd: PAM module to run external commands](https://github.com/clipos-archive/src_platform_pam_exec_pwd)
* [pam_jail: PAM module to jail users based on their groups](https://github.com/clipos-archive/src_platform_pam_jail)
* [pfring-kernel-patches: Experimental PF_RING patches for CLIP](https://github.com/clipos-archive/src_platform_pfring-kernel-patches)
* [portage-derive: Tool to help keep a Portage tree up-to-date](https://github.com/clipos-archive/src_platform_portage-derive)
* [pwcheckd: authenticate users sending their password over a UNIX socket](https://github.com/clipos-archive/src_platform_pwcheckd)
* [rmh-config: graphical configuration tool for RMH services](https://github.com/clipos-archive/src_platform_rmh-config)
* [rm-sessions: scripts for RM jails](https://github.com/clipos-archive/src_platform_rm-sessions)
* [scdaemon: Smartcard daemon for GnuPG/OpenPGP smartcards](https://github.com/clipos-archive/src_platform_scdaemon)
* [smartcard-monitor: Smartcard events monitor](https://github.com/clipos-archive/src_platform_smartcard-monitor)
* [smartcard-readers: USB smartcard readers devices creation scripts (hotplug)](https://github.com/clipos-archive/src_platform_smartcard-readers)
* [splash-theme-clip: Boot-time splash theme for CLIP OS 4](https://github.com/clipos-archive/src_platform_splash-theme-clip)
* [ssm-display: Display client and daemon for CLIP SSM](https://github.com/clipos-archive/src_platform_ssm-display)
* [strongswan-clip-updown: strongSwan updown plugin specific to CLIP jails](https://github.com/clipos-archive/src_platform_strongswan-clip-updown)
* [strongswan-patches: Set of strongSwan patches for CLIP](https://github.com/clipos-archive/src_platform_strongswan-patches)
* [sub-clip](https://github.com/clipos-archive/src_platform_sub-clip)
* [syslinux-tpm-patches: TPM support for Syslinux](https://github.com/clipos-archive/src_platform_syslinux-tpm-patches)
* [tpm-cmd: A lighthweight TPM commandline tool](https://github.com/clipos-archive/src_platform_tpm-cmd)
* [usb-printer-devices: USB printer devices for RM jails](https://github.com/clipos-archive/src_platform_usb-printer-devices)
* [usb-scanner-devices: USB scanner devices for RM jails](https://github.com/clipos-archive/src_platform_usb-scanner-devices)
* [usb-video-devices: USB video devices for RM jails](https://github.com/clipos-archive/src_platform_usb-video-devices)
* [userd: daemon handling user management tasks](https://github.com/clipos-archive/src_platform_userd)
* [vaultguard: Virtual vault to keep user's secrets](https://github.com/clipos-archive/src_platform_vaultguard)
* [verictl: configure veriexec](https://github.com/clipos-archive/src_platform_verictl)
* [vsctl: start, stop and enter simple vservers](https://github.com/clipos-archive/src_platform_vsctl)
* [xscreensaver-pwcheck: authenticate xscreensaver users through pwcheckd](https://github.com/clipos-archive/src_platform_xscreensaver-pwcheck)

---

Copyright © 2018 [ANSSI](https://www.ssi.gouv.fr/).

CLIP OS is a trademark of the French Republic.
As a consequence, any use of the name "CLIP OS" has to be first authorized by the ANSSI.
This does not preclude changes to the software posted online and their republication or quotation from identifying the original software under the terms of the LGPL v2.1+ license.
Regardless, no use of the name "CLIP OS" on a modified version should suggest that this version is the original work published by the ANSSI.
