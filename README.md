![pack.png](https://i.loli.net/2018/02/18/5a8974407b453.png)

---

**Languages / 语言：中文**丨[English](README-en.md)

| 翻译进度 | GitHub Actions | 最新快照版本 |
| :--: | :--: | :--: |
| ![Weblate](https://weblate-t.exz.me/widgets/langpack/-/svg-badge.svg) | ![Packer](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package/workflows/Packer/badge.svg?branch=main) | [![GitHub Release](https://img.shields.io/github/release/CFPAOrg/Minecraft-Mod-Language-Package.svg)](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package/releases/latest) |

---

## 仓库说明

这是 Minecraft 模组汉化项目的仓库，用以解决模组作者不接收汉化、汉化提交更新速度慢等诸多问题。

[CFPA 官网](https://cfpa.team)

---

## 参与翻译？

请查阅 [CONTRIBUTING](./doc/CONTRIBUTING.md)。

---

## 使用说明

### 1. 自动加载资源包

安装自动汉化更新模组（I18nUpdateMod）后，即可在游戏加载过程中自动加载资源包，无需进行其他操作。

- [MCMOD](https://www.mcmod.cn/class/1188.html)
- [MCBBS](https://www.mcbbs.net/thread-805273-1-1.html)
- [GitHub](https://github.com/CFPAOrg/I18nUpdateMod2)

### 2. 手动加载资源包

可在 [Releases](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package/releases) 页面下载快照版本资源包，使用方法与**普通资源包**相同。

- 名称前缀有 1-16 的资源包（1-16-汉化资源包-Snapshot-xx）为 1.16 专用资源包。
- 非上述情况的资源包（汉化资源包-Snapshot-xx）为 1.12 专用资源包。

---

## 问题反馈

请在 [CFPAOrg 反馈中心](https://ticket.cyllive.cn/) 新建工单。

---

## 技术说明

**你们是怎么做到流水线式的翻译的？**

emmmm，原理其实很简单。

1. 通过爬虫爬取 CurseForge 的热门模组；
2. 脚本推送回 GitHub 仓库；
3. Weblate 检测到仓库变动，自动抓取 GitHub 变动；
4. 翻译人员在 Weblate 上翻译，Weblate 自动推回到 GitHub；
5. GitHub Actions 检测到仓库变动，自动构建并打包；
6. GitHub Actions 自动发布到 GitHub 的 Release 上，以供下载；

---

## 授权协议

本项目采用 [知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/)（[简体中文](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)）进行许可，协议全文可在 [此处](./LICENSE) 找到。

---

## 特别鸣谢

感谢 `phi` 搭建出了 Weblate 服务器，还提供了机器翻译功能。

感谢 `Summpot`，`Nullpinter` 制作了新版本的 C# 爬虫。

感谢 `PeakXing` 制作的 Logo。

感谢 `Snownee`、`FledgeXu`、`asdflj` 等在内的诸多人的意见和建议。

感谢本项目的最初贡献者 `Aemande123`，`DYColdWind`，`Snownee`，`yuanjie000`，`forestbat`，`3TUSK`，`SihenZhang`，`MoXiaoFreak`，`gloomy_banana`，`yuanjie000`，`exia00125`，`luckyu19` 所提供的汉化。（排名不分先后）

资源包内置了 `3TUSK` 提供的 [全角标点修复文件](./projects/1.16.1/assets/minecraft/minecraft/readme.md)。

可在本仓库的 [Contributors](https://github.com/CFPAOrg/Minecraft-Mod-Language-Package/graphs/contributors) 页面查看所有翻译贡献者。

最后感谢那些参与翻译，并致力于本地化推广的各位玩家，你们辛苦了。
