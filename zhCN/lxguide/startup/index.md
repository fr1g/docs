# 开始

欢迎使用LauncherX！我们不断致力于为您打造美观便捷的使用体验。

[[toc]]

>   本文创建日期：2023年7月14日，修改日期：2024年3月6日，作者：Feiron Iguista

-------

::: warning

请注意：LauncherX不在任何一个平台上支持32位或更低的操作系统。

:::

## 环境要求

基本上，对于所有的桌面环境，前置条件基本上是一致的。

首先，为了能够让LauncherX稳定地大展拳脚，您的**电脑需要满足以下条件**:

**软件要求**

Windows7及更新版本的64位操作系统、Windows 10 或更新版本的 for ARM 64位操作系统<br> *或*    macOS 12 及更新版本 (基于Intel芯片或Apple芯片)<br> *或*    带有Xfce/GNOME之类桌面环境的Linux 64位操作系统 (建议内核版本高于5).

**硬件要求**

**CPU**: 主频高于2.5GHz的至少4核心64位处理器 (amd64/ARM64/x86-64)<br>**运行内存**: 不少于4GB<br>        **GPU**: 建议性能高于: Intel UHD 770 (集成显卡) / 建议性能高于: Radeon RX560<br>**存储空间**: 预留100MB (Windows: ~30MB，Linux和macOS: ~60MB。预留更多空间以供下载等缓存使用。实际上安装游戏需要为游戏预留一定空间。)



## 下载LauncherX

接下来，该**下载LauncherX**了:

我们推荐优先使用**包含运行时的独立版**。请前往[官网下载](https://corona.studio/launcherx/download)稳定版，或赞助我们以取得测试版；<br>或者在我们的**配置助手**发布后，使用配置助手来为您选择合适的LauncherX。这将是最适合普通用户的方案（敬请期待）。

下载LauncherX的一般流程如下：

- 打开[官网](https://corona.studio/launcherx/download)（或[官网.MIN](https://mincorona.studio/lx)）

- 一般而言，网页会根据你的电脑来推荐下载的版本。你需要下载对应你电脑系统和CPU架构的版本，如果网页选择了和你电脑情况不一致的版本，请用下载按钮右侧的**三角按钮**（如果是MIN站 ，直接在网页上点击对应正确构建的按钮来开始下载）来选择正确对应你电脑的选项。如果你不知道如何确认你的电脑系统版本和CPU架构，参见：[辨识计算机环境 | 日冕知识库](/zhCN/guide/general/check-system.html)
    :::tip 截至目前，大多数用户使用的是Windows x64。

- 下载完毕后，将LauncherX解压并放置到一个合适的地方。
    :::tip 关于存放位置
    macOS建议放在【应用程序】(也就是说Applications) 目录下; Linux可以放在任何你常用于存放程序的地方，Windows同样，但是**不要放在桌面或其他难以打理的地方**，最好放在一个空文件夹里，因为Windows版LauncherX会在当前所在位置解压出自己的工作目录和默认的游戏文件夹。
    Linux和macOS版本的LauncherX会在一个合适的地方存储LauncherX的配置文件和默认游戏目录，电脑上任意地方的LauncherX将共用该配置文件；Windows版本则会在每个LauncherX所在的位置创建独立的默认游戏目录和配置文件。

    :::

## 开始使用LauncherX

那么现在，无论是Windows，macOS还是Linux某个带桌面环境的发行版，也无论架构是x86-64，x86-S，amd64还是ARM64，您已经根据当前操作系统下载好了对应的LauncherX到您希望其所运行的文件夹中。那么您就可以像运行其他程序一样双击它的图标来运行了。

接下来，面对所有已知可能出现的问题，您都可以在此系列文档的【初次启动】部分 (按操作系统不同分成三篇) 找到说明并了解可能的解决方法。

::: info

由于设备不同，您在初次启动时可能会遇到些小麻烦，为此我们感到十分抱歉。我们正在努力解决这些严重影响体验的问题，因而本文将会不定期发生变更，恕不另行通知。

如果需要提供反馈，请参考：[报告异常&建言新策 | 日冕知识库](/zhCN/lxguide/report-issue.html)

:::

## 共有的问题

由于我们的Java运行时检测机制是通过 “搜索-执行” 模式工作以确认该运行时是否可用，所以在您启动LauncherX时候，可能会遇到来自Java的错误弹窗。您完全可以直接将它关闭，因为这并不影响LauncherX运行; 且如果您没有选择任何一个被LauncherX判断为有问题的JRE作为游戏启动所使用的Java，那么您的游戏启动几乎不可能受到受损JRE的影响。由于每次LauncherX启动都会检查搜索到的JRE是否可用，因此您应该将该受损的运行时**移除**，或者用自动化窗口关闭工具（比如 火绒弹窗拦截）对错误弹窗进行精准打击。

## 下一步

假设您的LauncherX现在能正常运行，但是您不知道接下来该做什么？参考：[安装游戏 | 日冕知识库](/zhCN/lxguide/features/installing-games.html)，下载并安装您的游戏。

已经加入了内部测试？参考：[切换更新通道 | 日冕知识库](/zhCN/lxguide/others/switch-channel.html)
