---
slug: x1c7-perf
---

#[[X1C7]]'s performance is reasonably good for both home-office and coffee-shop use. 

The carbon does suffer a bit with heavy workloads, such as some long compilation (eg: GHCJS) tasks, IDE heavylifting (haskell-language-server) or when using complex (bloated) web apps. However, for the bulk of them I can offload them to my [[P71]] workstation at home (via manual ssh, [[VSCode]] [remote ssh][vsr] or [distributed](https://nixos.wiki/wiki/Distributed_build) build), and then use its [binary cache](https://nixos.wiki/wiki/Binary_Cache). 

Per the pareto principle, the carbon is still a delight to use, although one must be aware of this compromise in performance, and not to mention memory (16G max RAM).

[vsr]: https://code.visualstudio.com/docs/remote/ssh
