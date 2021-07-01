---
slug: x1c7-wifi
---

WiFi can disconnect from time to time (in [[Linux]]). This is the most annoying problem with the #[[X1C7]]. It vanishes for some days, before returning.

[See reddit discussion](https://old.reddit.com/r/thinkpad/comments/iu1de6/x1_carbon_w_5k_monitor_running_linux/g5ijbw9/?utm_source=reddit&utm_medium=web2x&context=3); Looks to be [this bug](https://bugzilla.kernel.org/show_bug.cgi?id=203709), though in 2021 I'm seeing more of the [0x707](https://bugzilla.kernel.org/show_bug.cgi?id=203593) bug.

In the end, I decided to just use an external wifi card ([[AC600M USB WiFi Adapter]]#)

**Update**: Turns out, this only happens if there are multiple router channels (eg: different "pods"[^bell] for the main router) in use; and the issue is not specific to the X1 Carbon, as I've seen it happen on the [[P71]] too.

[^bell]: Such as the [Wi-Fi pods](https://www.bell.ca/Bell_Internet/Products/Wifi) from Bell Canada.