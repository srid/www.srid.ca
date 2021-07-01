---
slug: x1c7-review
tags: [blog/x1c7]
date: 2020-12-21
---

On September 10th, I received my #[[X1C7]] (Gen 7, with 10th gen processor) shipped from Lenovo, and this is a brief review of having used it as my primary computer in the last 3+ months.

## Setting up Linux

I usually run [[NixOS]] on my computers, which is what I did on the Carbon. Read the specifics in [[Installing NixOS on X1 Carbon Gen 7]].

## What works

Linux kernel 5.9 or later has the best hardware support. Everything including Thunderbolt and fingerprint reader works on Linux. I was surprised in particular to see that 5k resolution worked in [[LG Ultrafine 5k]], which is a retina-quality Thunderbolt monitor designed specifically for Macbooks. Compared to previous Thinkpads (such as [[P71]]), the trackpad is as good as that of a Macbook.

## WiFI can be unstable

The only annoying issue with the Carbon is that the WiFi card included in my laptop experiences periodic disconnections on Linux. Others have reported the same. See [[X1C7 WiFi issue]]# for details. In the end, I resorted to using a USB wifi dongle to sidestep this problem. 

## Performance

Performance is good enough for general use and programming, but not ideal for heavy lifting. See [[[X1C7 - Moderate Performance]]] for details.

## Battery Life

I did not explicitly measure battery life on this laptop with a 4k screen. It looks to be around 6 hours which is more than enough for my use cases. I used the default [nixos-hardware] configuration; and reddit has [some tips][bat-red]. A fellow programmer reported [5 hours][bat-5h].

## Next computer

My next computer, if I choose to buy one in ~3 years, would likely be similar to the X1C7 but with a bit more performance (assuming battery life does not suffer); i.e., if I were to make this decision again, I'd consider Thinkpad X1E or P1[^amd] - but with integrated graphics (nvidia has poor support on Linux). That said, I still use the Carbon as my primary computer, and use [[VSCode]] remote to shift much of the develoment heavylifting to the [[P71]] workstation at home.
  
[bat-red]: https://old.reddit.com/r/thinkpad/comments/gc5nn2/x1_extreme_gen_2_4k_uhd_linux_battery_life/fp9ebs5/?utm_source=reddit&utm_medium=web2x&context=3

[bat-5h]: https://old.reddit.com/r/thinkpad/comments/hwonb5/x1_carbon_gen_8_4k_battery_life/

[nixos-hardware]: https://github.com/srid/nix-config/blob/48c1c44a7ed52c25c25a19a1771b71a16e174da5/nixos-configuration/x1c7.nix#L11-L13

[^amd]: And if Thunderbolt wasn't a requirement, I'd easily go for a Thinkpad with AMD processor, such as the T14.
