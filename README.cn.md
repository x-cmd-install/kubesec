# kubesec

[English version](./README.md)

Secure Secret management for Kubernetes (with gpg, Google Cloud KMS and AWS KMS backends)

![kubesec](https://repo.x-cmd.io/kubesec.svg?lang=zh)

## 安装

```sh
x install kubesec
```

## 代码洞察

合计: **3,251** 行代码（覆盖前 5 种语言、共 **27** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 3,153 | 92 | 189 | 22 |
| Makefile | 59 | 0 | 16 | 1 |
| Dockerfile | 21 | 15 | 9 | 1 |
| Yaml | 18 | 0 | 0 | 1 |
| Markdown | 0 | 344 | 122 | 2 |

## OpenSSF Scorecard 评分

总评分: **2.6 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Dangerous-Workflow** (-1/10) — no workflows found
- **Token-Permissions** (-1/10) — No tokens found

## 源代码

- **上游仓库**: <https://github.com/shyiko/kubesec>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `0.9.2` (2018-08-10)
- **最近提交**: 2019-08-16
- **Release 含资产**: 6 个

## 流行度

- **Star**: 613 · **Fork**: 42 · **开放 issue**: 31 · **贡献者**: 5

## 累计统计

- **发布数**: 17 · **已合并 PR**: 4 · **开放 PR**: 0 · **已关闭 issue**: 19 · **开放 issue**: 12 · **提交数**: 132

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-14 | 0 | 0 | 0 | 0 | 0 | 0 |
| 360d | 2025-09-15 | 0 | 0 | 0 | 0 | 0 | 0 |
| last720d | 2024-09-20 | 0 | 0 | 0 | 0 | 1 | 0 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [kubesec-0.9.2-darwin-amd64](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-darwin-amd64) | 12.2 MiB | `native/darwin/x64` |
| [kubesec-0.9.2-darwin-amd64.asc](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-darwin-amd64.asc) | 833 B | `native/darwin/x64` |
| [kubesec-0.9.2-linux-amd64](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-linux-amd64) | 12.3 MiB | `native/linux/x64` |
| [kubesec-0.9.2-linux-amd64.asc](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-linux-amd64.asc) | 833 B | `native/linux/x64` |
| [kubesec-0.9.2-windows-amd64.exe](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-windows-amd64.exe) | 12.3 MiB | `native/win/x64` |
| [kubesec-0.9.2-windows-amd64.exe.asc](https://github.com/shyiko/kubesec/releases/download/0.9.2/kubesec-0.9.2-windows-amd64.exe.asc) | 833 B | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/kubesec) 上共有 **8** 个发行版报告此项目。**7** 个 ✅ 已是最新上游版本，**1** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Nix unstable | `2.14.2` | ✅ latest |
| openSUSE Tumbleweed | `2.14.2` | ✅ latest |

## 改进这些数据

kubesec 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kubesec` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kubesec.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260910.yml` · 2026-09-10T23:16:26Z._
