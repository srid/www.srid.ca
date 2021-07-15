---
slug: windows-iso-linux-usb
tags: [micro]
date: 2021-03-14
---

The Windows 10 ISO contains a file named `sources/install.wim` that weights more than 4G, which is the maximum file size on [FAT filesystems](https://en.wikipedia.org/wiki/File_Allocation_Table). So the USB disk must be partitioned using NTFS, however BIOS doesn't supporting booting from NTFS USB partitions (for whatever reason); this can be worked around by creating the bootable drive using [WoeUSB](https://github.com/slacka/WoeUSB).

On [[NixOS]],

```bash
nix-shell -p woeusb --run woeusbgui
# You might have to set the `$SHELL` environment, and run woeusbgui with `sudo`.
```

Be sure to enable NTFS support in the kernel first; see https://nixos.wiki/wiki/NTFS

In WoeUSB's dialog, select "NTFS" as the file system. The resultant USB should properly boot into Windows installer.

