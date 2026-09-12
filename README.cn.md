# tracexec

[English version](./README.md)

Tracer for execve{,at} and pre-exec behavior, launcher for debuggers.

![tracexec](https://repo.x-cmd.io/tracexec.svg?lang=zh)

## 安装

```sh
x install tracexec
```

## 代码洞察

合计: **403,965** 行代码（覆盖前 5 种语言、共 **431** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| CHeader | 335,086 | 65 | 43,383 | 11 |
| Rust | 35,779 | 1,245 | 3,336 | 113 |
| Protobuf | 28,549 | 13,374 | 5,039 | 296 |
| Nix | 1,672 | 178 | 141 | 8 |
| C | 1,281 | 192 | 104 | 3 |

## 源代码

- **上游仓库**: <https://github.com/kxxt/tracexec>
- **官网**: <https://tracexec.kxxt.dev>
- **许可证**: GPL-2.0

## 发布

- **最新版本**: `v1.0.0` (2026-09-06)
- **最近提交**: 2026-09-06
- **Release 含资产**: 6 个

## 流行度

- **Star**: 438 · **Fork**: 7 · **开放 issue**: 58 · **贡献者**: 5

## 累计统计

- **发布数**: 63 · **已合并 PR**: 220 · **开放 PR**: 8 · **已关闭 issue**: 39 · **开放 issue**: 19 · **提交数**: 1441

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 3 | 12 | 5 | 0 | 0 | 42 |
| last60d | 2026-07-14 | 3 | 26 | 6 | 0 | 0 | 91 |
| 90d | 2026-06-14 | 3 | 42 | 7 | 1 | 0 | 154 |
| last180d | 2026-03-16 | 3 | 93 | 8 | 2 | 1 | 261 |
| 360d | 2025-09-17 | 10 | 153 | 8 | 12 | 4 | 483 |
| last720d | 2024-09-22 | 28 | 209 | 8 | 19 | 10 | 691 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [tracexec-aarch64-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-aarch64-unknown-linux-gnu-static.tar.gz) | 3.8 MiB | `native/linux/arm64/glibc` |
| [tracexec-aarch64-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-aarch64-unknown-linux-gnu.tar.gz) | 3.3 MiB | `native/linux/arm64/glibc` |
| [tracexec-riscv64gc-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-riscv64gc-unknown-linux-gnu-static.tar.gz) | 3.9 MiB | `native/linux/riscv64/glibc` |
| [tracexec-riscv64gc-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-riscv64gc-unknown-linux-gnu.tar.gz) | 3.4 MiB | `native/linux/riscv64/glibc` |
| [tracexec-x86_64-unknown-linux-gnu-static.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-x86_64-unknown-linux-gnu-static.tar.gz) | 4.0 MiB | `native/linux/x64/glibc` |
| [tracexec-x86_64-unknown-linux-gnu.tar.gz](https://github.com/kxxt/tracexec/releases/download/v1.0.0/tracexec-x86_64-unknown-linux-gnu.tar.gz) | 3.3 MiB | `native/linux/x64/glibc` |

## 发行版状态

在 [repology.org](https://repology.org/project/tracexec) 上共有 **11** 个发行版报告此项目。**7** 个 ✅ 已是最新上游版本，**4** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Arch | `0.17.0` | ✅ latest |
| Nix unstable | `0.17.0` | ✅ latest |

## 改进这些数据

tracexec 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `tracexec` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/tracexec.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260912.yml` · 2026-09-12T04:45:28Z._
