# static-binaries

Common static (x64 gnu) binaries & utils used in CI-pipelines, compressed with [UPX](https://github.com/upx/upx) v3.96

**Motivation:**

- Keep things in _one_ place
- Different binaries releases have different names & compression tools, i.e .zip , \*.tgz , .tar.gz , .lzt , .deb etc
- Compressed binaries => less bandwidth => faster installation time (see [upx.txt](upx.txt))
- Available via CDN, ie: https://cdn.jsdelivr.net/gh/borestad/static-binaries/jq
- apt-get/linuxbrew/go get/cargo is too slow

**TODO:**

- Automate everything

All credits goes to:

- [dasel](https://github.com/TomWright/dasel)
- [dprint](https://github.com/dprint/dprint)
- [fd](https://github.com/sharkdp/fd)
- [gron](https://github.com/tomnomnom/gron)
- [hr](https://github.com/jaredsohn/hr)
- [htmlq](https://github.com/mgdm/htmlq)
- [iprange](https://github.com/firehol/iprange)
- [jq](https://github.com/stedolan/jq)
- [pup](https://github.com/ericchiang/pup)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- [sd](https://github.com/chmln/sd)
- [sponge](https://github.com/Chaostheorie/sponge)
- [taskfile](https://github.com/go-task/task)
- [tokei](https://github.com/XAMPPRocky/tokeiP)
