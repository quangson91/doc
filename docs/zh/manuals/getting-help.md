---
title: 如何获得帮助
brief: 本教程介绍了使用 Defold 遇到麻烦时该如何寻求帮助.
---

# 获得帮助

如果你使用 Defold 时遇到了麻烦请联系我们以便解决或绕过问题! 有许多途径可以讨论和汇报问题. 依个人喜好选择:

## 在论坛里提交问题

在我们的 [论坛](https://forum.defold.com) 上提交问题是一个好方法. 依据你的问题的类型可以在 [Questions](https://forum.defold.com/c/questions) 或者 [Bugs](https://forum.defold.com/c/bugs) 类目下发帖. 提交问题的时候请尽附加可能多的信息. 记得发问之前在论坛 [搜索](https://forum.defold.com/search) 一下相关内容, 也许论坛上已经存在你的问题的解决方案了.

有多个问题, 就发多张帖子. 不要在一个帖子说发布不相干的问题.

### 提供信息
提问时请提供以下信息:

**题目**
简明扼要的标题. 像 "如何让游戏对象延面对方向前进?" 或者 "如何实现 Sprite 渐隐效果?" 就比较好. 像 "我需要 Defold 的帮助!" 或者 "我的游戏不动了!" 就不怎么好.

* **问题的描述 (必须)** - 问题的简短描述.

* **问题的复现 (必须)** - 复现问题的步骤:
  1. 进入 '...'
  2. 点击 '....'
  3. 滑动到 '....'
  4. 错误出现

* **期望行为 (必须)** - 期望实现的行为的简短描述.

* **Defold 版本 (必须)** - 版本 [例如 1.2.155]. 最好再加上引擎和编辑器的 SHA1, 可以从 <kbd>Help->About</kbd> 菜单项里看到.

* **操作平台 (必须)** - 在哪个操作平台上出现的问题?
  - 平台: [比如 iOS, Android, Windows, macOS, Linux, HTML5]
  - 系统: [比如 iOS8.1, Windows 10, High Sierra]
  - 设备: [比如 iPhone6]

* **详细系统信息 (可选)** - 有关错误出现系统平台的详细信息.
  - HTML5: 提供关于 WebGL 的详细信息, 参考网站 https://webglreport.com/?v=1

* **日志 (可选)** - 请附带相关 (云编译服务器, 引擎和编辑器) 日志. 参考 [下面关于日志文件获取的章节](#log-files).

* **问题复现小项目 (可选)** - 请附加一个可以再现问题的最小项目包. 这可以对别人研究修复问题提供极大帮助. 如果你把项目打成zip包请去掉其中的 `.git`, `.internal` 和 `build` 文件夹.

* **绕过方法 (可选)** - 如果你找到了可以绕过问题的方案, 也请附加上.

* **屏幕截图 (可选)** - 如果可以, 附加屏幕截图有助于描述出现的问题.

* **其他 (可选)** - 还可以加入其他问题相关上下文信息.


## 从编辑器里汇报问题

编辑器提供了一个汇报错误的方便的方法. 选择 <kbd>Help->Report Issue</kbd> 菜单项来汇报错误.

![](images/getting_help/report_issue.png)

这样就会在 GitHub 上生成一个错误报告. 请提供 [日志文件](#log-files), 操作系统, 重现方法, 临时绕过错误的方法等信息.

::: 注意
报告之前确保你已经拥有 GitHub 账户.
:::


## 在 Slack 上讨论问题

如果在使用 Defold 时遇到困难你可以尝试在 [Slack](https://www.defold.com/slack/) 上提出问题. 虽然我们推荐复杂问题应该在论坛上深入讨论. 而且注意 Slack 上不支持错误报告.


# 日志文件

游戏引擎, 编辑器和云编译服务器都有日志系统, 这对于定位调试错误十分有利. 报告错误时请务必带上日志文件.

* [引擎日志](/manuals/debugging-game-and-system-logs)
* 编辑器日志
  * Windows: `C:\Users\ **Your Username** \AppData\Local\Defold`
  * macOS: `/Users/ **Your Username** /Library/Application Support/` 或 `~/Library/Application Support/Defold`
  * Linux: `~/.Defold`
* [编译服务器日志](/manuals/extensions#build-server-logs)