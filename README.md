# herdr-bin

Prebuilt [herdr](https://github.com/herdrdev/herdr) binaries for Linux and Windows, mirrored from the official GitHub releases.

herdr is licensed under Apache-2.0; these files are unmodified copies of the upstream release assets.

## Current version: v0.9.5 (released 2026-10-14)

| File | Platform |
|------|----------|
| `v0.9.5/herdr-linux-x86_64` | Linux x86_64 |
| `v0.9.5/herdr-linux-aarch64` | Linux ARM64 |
| `v0.9.5/herdr-windows-x86_64.zip` | Windows x86_64 |

Verify with `sha256sum -c SHA256SUMS` inside the version directory.

## Install

Linux:

```sh
install -m 755 v0.9.5/herdr-linux-x86_64 ~/.local/bin/herdr
```

Windows: unzip `herdr-windows-x86_64.zip` and put `herdr.exe` on your `PATH`.
