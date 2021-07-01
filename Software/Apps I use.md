---
slug: apps
---

| Type                 | App                                           | Why                                                                                                                                                                                                                                                                                                                                                        |
| -------------------- | --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Email                | [ProtonMail]                                  | DeGoogle                                                                                                                                                                                                                                                                                                                                                   |
| File Sync            | Syncthing                                     | p2p Dropbox alternative                                                                                                                                                                                                                                                                                                                                    |
| File Storage         | ProtonDrive                                   | DeGoogle; encryption-at-rest; [sync, in future][pd-sync]                                                                                                                                                                                                                                                                                                   |
| File Sharing         | [IPFS]                                        | p2p[^ipfspinning]                                                                                                                                                                                                                                                                                                                                          |
| Video hosting        | [Odysee](https://odysee.com/$/invite/@srid:2) | DeGoogle; decentralized                                                                                                                                                                                                                                                                                                                                    |
| Chat                 | [Element]                                     | [decentralized moderation]                                                                                                                                                                                                                                                                                                                                 |
| Browser              | [Brave]                                       | DeGoogle; chromium-based; [peer-to-peer encrypted sync][brave-sync]; [decentralized-love](https://brave.com/ipfs-support/); [anti-censorship](https://www.theregister.com/2021/03/03/brave_buys_a_search_engine/); [no bad politics](https://old.reddit.com/r/brave_browser/comments/o0iaw7/why_im_now_using_brave_coming_from_firefox/h1vudwj/?context=3) |
| Search Engine        | [Brave Search]                                | DeGoogle; transparency                                                                                                                                                                                                                                                                                                                             |  |
| Password Manager     | [[Pass with GPG]]                             | plain-text; git; gpg                                                                                                                                                                                                                                                                                                                                       |
| OS                   | [[NixOS]] + GNOME                             |
| Editor / IDE         | [[VSCode]]                                    | UX; remote editing; extensions                                                                                                                                                                                                                                                                                                                             |
| Note taking          | [[Neuron]], [[Emanote]]                       | Open source; future-proof                                                                                                                                                                                                                                                                                                                                  |
| Programming Language | [[Haskell]]                                   | [statically-typed; FP](https://wiki.haskell.org/Why_Haskell_matters), [[No JavaScript]]                                                                                                                                                                                                                                                                    |

[ProtonMail]: https://protonmail.com/
[Brave]: https://brave.com/
[Brave Search]: https://brave.com/search/
[IPFS]: https://ipfs.io/
[Element]: https://element.io/
[decentralized moderation]: https://matrix.org/blog/2020/10/19/combating-abuse-in-matrix-without-backdoors
[pass]: https://www.passwordstore.org/

## Browser extensions

Note that Chrome extensions work on Brave.

* [Vimium](https://vimium.github.io/)
* [De-Mainstream YouTube](https://demainstream.com/) ([Extension link](https://chrome.google.com/webstore/detail/de-mainstream-youtube/dkcdmdpcapjlaoioeenamjdanpeehjan?hl=en))
* [Redirect: YouTube -> Odysee](https://reclaimthenet.org/watch-on-odysee-browser-extension/)

## To consider

- [ ] Google Domains -> NameCheap
- [ ] Android -> some Linux phone
- [ ] GitHub -> [radicle](https://radicle.xyz/)[^radicle] (for repo hosting, project management and discovery)

[^radicle]: Radicle holds a lot of promise, but it is still in too early a phase for switching active projects.
[^ipfspinning]: Needs a IPFS pinning service for [data permanence](https://docs.ipfs.io/concepts/persistence/). [IPFS Cluster](https://cluster.ipfs.io/) is one way to achieve this.

[brave-sync]: https://support.brave.com/hc/en-us/articles/360021218111-How-do-I-set-up-Sync-
[pd-sync]: https://old.reddit.com/r/ProtonMail/comments/j2isz7/version_410_is_here/g77goh0/?context=3
