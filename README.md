# static-binaries

**Common static (x64 gnu) binaries & utils used in CI-pipelines**

- Stripped
- Compressed with [UPX](https://github.com/upx/upx) v4 when applicable
- Prefer musl over gnu
- Tested in Ubuntu/Debian/Alpine
- Prefer new version over backward compatibility

**Motivation:**

- Keep things in _one_ place
- Different binaries releases have different names & compression tools, i.e .zip , \*.tgz , .tar.gz , .lzt , .deb etc
- Compressed binaries => less bandwidth => faster installation time (see [upx.txt](upx.txt))
- Available via CDN, ie: https://cdn.jsdelivr.net/gh/borestad/static-binaries/x86-64/jq
- apt-get/linuxbrew/go get/cargo is too slow


**TODO:**

- Keep versioning
