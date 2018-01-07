# 什么是 Electron？
Electron 是一个基于 Chrominum 和 Node.js 的跨平台桌面应用框架。

在这个框架中很容易构建基于 HTML、CSS 和 JavaScript 技术的跨平台应用。构建出来的应用会很好地兼容 Mac、Windows 和 Linux 操作系统。

它还有其它一些特性：

- 自动更新 —— 应用支持自动更新
- 原生菜单和通知 —— 可以创建原生应用菜单和上下文菜单
- 应用崩溃报告 —— 可以将崩溃报告提交到远程服务器
- 调试和分析 —— Chrominum 的内容模块可以发生性能瓶颈和缓慢的操作。你也可以在应用中使用自己喜欢的 Chrome 开发者工具。
- Windows installer —— 可以快速便捷地创建安装包。

# 安装 Electron
>npm install electron --save-dev

如果你使用了代理，安装过程可能出现connect timeout错误，则需要加-no-proxy

>npm install electron -no-proxy --save-dev