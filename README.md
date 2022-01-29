# My Linux Desktop Journey

I used Linux as my primary Desktop OS between 1999 and 2012, in chronological order on RedHat, [SuSE Linux](https://en.wikipedia.org/wiki/SUSE), [Mandrake Linux](https://en.wikipedia.org/wiki/Mandriva), Debian and Ubuntu, first on [KDE Desktop](https://en.wikipedia.org/wiki/KDE), next on [GNOME Desktop](https://en.wikipedia.org/wiki/GNOME) since version [0.99.1](https://mail.gnome.org/archives/gnome-announce-list/1998-December/msg00004.html) (interesting blog and podcast: [« The History of GNOME »](https://www.bassi.io/articles/2018/10/25/history-of-gnome-episode-1/)).

July 2012, with the arrival of [Homebrew](https://brew.sh/) I switched to MacOS as my primary Desktop OS.

Middle of 2021, I decided to pilot a progressive return to Linux Desktop.

This repository is inspired by [`jokeyrhyme/my-linux-journey`](https://gitlab.com/jokeyrhyme/my-linux-journey/-/issues) ([see my tweet](https://twitter.com/klein_stephane/status/1454034063845695496)).

I use [these GitHub issues](https://github.com/stephane-klein/my-linux-desktop-journey/issues) to track my hurdles, my goals and [their solutions](https://github.com/stephane-klein/my-linux-desktop-journey/issues?q=is%3Aissue+is%3Aclosed).

## Hardware

New equipment since January 2022:

- [Intel® NUC 11 Performance kit - NUC11PAHi7](https://www.intel.com/content/www/us/en/products/sku/205073/intel-nuc-11-performance-kit-nuc11pahi7/specifications.html)
  - [Intel® Core™ i7-1165G7 Processor (12M Cache, up to 4.70 GHz)](https://www.intel.com/content/www/us/en/products/sku/208662/intel-core-i71165g7-processor-12m-cache-up-to-4-70-ghz/specifications.html)
  - [Crucial 32GB Kit (2 x 16GB) DDR4-3200 SODIMM CT2K16G4SFRA32A](https://www.crucial.com/memory/ddr4/ct2k16g4sfra32a)
  - [WD_BLACK™ SN850 NVMe™ SSD - 1To](https://www.westerndigital.com/fr-fr/products/internal-drives/wd-black-sn850-nvme-ssd#WDS100T1X0E)
- Connected on this monitors:
  - [23.8" Dell P2415Q](https://www.displayspecifications.com/en/model/be0153a)
  - [23.8" Dell P2421DC](https://www.displayspecifications.com/en/model/77151d40)

## Desktop environments

For now, I try to use GNOME Window Manager on Fedora 35 on xorg display server.

```
[stephane@nuc-i7 ~]$ neofetch
             .',;::::;,'.                stephane@nuc-i7
         .';:cccccccccccc:;,.            ---------------
      .;cccccccccccccccccccccc;.         OS: Fedora Linux 35 (Workstation Edition) x86_64
    .:cccccccccccccccccccccccccc:.       Host: NUC11PAHi7 M15513-306
  .;ccccccccccccc;.:dddl:.;ccccccc;.     Kernel: 5.15.16-200.fc35.x86_64
 .:ccccccccccccc;OWMKOOXMWd;ccccccc:.    Uptime: 3 hours, 52 mins
.:ccccccccccccc;KMMc;cc;xMMc:ccccccc:.   Packages: 1989 (rpm), 15 (flatpak)
,cccccccccccccc;MMM.;cc;;WW::cccccccc,   Shell: zsh 5.8
:cccccccccccccc;MMM.;cccccccccccccccc:   Resolution: 3840x2160, 2560x1440
:ccccccc;oxOOOo;MMM0OOk.;cccccccccccc:   DE: GNOME 41.3
cccccc:0MMKxdd:;MMMkddc.;cccccccccccc;   WM: Mutter
ccccc:XM0';cccc;MMM.;cccccccccccccccc'   WM Theme: Adwaita
ccccc;MMo;ccccc;MMW.;ccccccccccccccc;    Theme: Adwaita-dark [GTK2/3]
ccccc;0MNc.ccc.xMMd:ccccccccccccccc;     Icons: Adwaita [GTK2/3]
cccccc;dNMWXXXWM0::cccccccccccccc:,      Terminal: tmux
cccccccc;.:odl:.;cccccccccccccc:,.       CPU: 11th Gen Intel i7-1165G7 (8) @ 4.700GHz
:cccccccccccccccccccccccccccc:'.         GPU: Intel TigerLake-LP GT2 [Iris Xe Graphics]
.:cccccccccccccccccccccc:;,..            Memory: 5634MiB / 31719MiB
  '::cccccccccccccc::;,.
```

## Keyboard shortcut

I try to keep MacOS and Gnome shortcut consistent because I works mainly on MacOS.

This table is in work in progress:

| Action                                                                                                                 | MacOS shortcut         | Gnome shortcut       |
|------------------------------------------------------------------------------------------------------------------------|------------------------|----------------------|
| [Open "Spotlight" / Show the activities Overview](https://github.com/stephane-klein/my-linux-desktop-journey/issues/3) | `<Cmd><Option><Space>` | `<Cmd><Alt><Space>`  |
| Switch windows                                                                                                         | `<Cmd><Tab>`           | `<Cmd><Tab>`         |
| Insert Emoji                                                                                                           | `<Ctrl><Cmd><Space>`   | `<Ctrl><Cmd><Space>` |

---

My English is not very good, feel free to correct me.
