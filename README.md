# tracexec

[中文版本](./README.cn.md)

Tracer for execve{,at} and pre-exec behavior, launcher for debuggers.

![tracexec](https://repo.x-cmd.io/tracexec.svg)

## Install

```sh
x install tracexec
```

## Code insight

Total: **403,965** lines of code across **431** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| CHeader | 335,086 | 65 | 43,383 | 11 |
| Rust | 35,779 | 1,245 | 3,336 | 113 |
| Protobuf | 28,549 | 13,374 | 5,039 | 296 |
| Nix | 1,672 | 178 | 141 | 8 |
| C | 1,281 | 192 | 104 | 3 |

## Source

- **Upstream**: <https://github.com/kxxt/tracexec>
- **Homepage**: <https://tracexec.kxxt.dev>
- **License**: GPL-2.0

## Release

- **Latest**: `v1.0.0` (2026-09-06)
- **Last commit**: 2026-09-06
- **Assets in release**: 6

## Popularity

- **Stars**: 438 · **Forks**: 7 · **Open issues**: 58 · **Contributors**: 5

## Totals (cumulative)

- **Releases**: 63 · **Merged PRs**: 220 · **Open PRs**: 8 · **Closed issues**: 39 · **Open issues**: 19 · **Commits**: 1441

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 3 | 12 | 5 | 0 | 0 | 42 |
| last60d | 2026-07-12 | 3 | 27 | 6 | 0 | 0 | 91 |
| 90d | 2026-06-12 | 3 | 42 | 7 | 1 | 0 | 154 |
| last180d | 2026-03-14 | 3 | 100 | 8 | 3 | 1 | 261 |
| 360d | 2025-09-15 | 10 | 153 | 8 | 12 | 4 | 483 |
| last720d | 2024-09-20 | 28 | 209 | 8 | 19 | 10 | 693 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [tracexec-aarch64-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-aarch64-unknown-linux-gnu-static.tar.gz) | 3.8 MiB | `native/linux/arm64/glibc` |
| [tracexec-aarch64-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-aarch64-unknown-linux-gnu.tar.gz) | 3.3 MiB | `native/linux/arm64/glibc` |
| [tracexec-riscv64gc-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-riscv64gc-unknown-linux-gnu-static.tar.gz) | 3.9 MiB | `native/linux/riscv64/glibc` |
| [tracexec-riscv64gc-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-riscv64gc-unknown-linux-gnu.tar.gz) | 3.4 MiB | `native/linux/riscv64/glibc` |
| [tracexec-x86_64-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-x86_64-unknown-linux-gnu-static.tar.gz) | 4.0 MiB | `native/linux/x64/glibc` |
| [tracexec-x86_64-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-x86_64-unknown-linux-gnu.tar.gz) | 3.3 MiB | `native/linux/x64/glibc` |

## Distribution status

Reported by **11** distros on [repology.org](https://repology.org/project/tracexec). **7** are ✅ on the latest upstream release, **4** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Arch | `0.17.0` | ✅ latest |
| Nix unstable | `0.17.0` | ✅ latest |

## Improve this data

Install metadata for tracexec lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `tracexec` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/tracexec.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T22:11:07Z._
