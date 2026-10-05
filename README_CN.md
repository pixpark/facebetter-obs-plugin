<h1 align="center">
  <a href="https://www.facebetter.net"><img src="./assets/logo-light.svg" alt="Facebetter Logo" width="200"></a>
</h1>

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://facebetter.net/zh/obs" target="_blank">官网</a>
  <span> · </span>
  <a href="https://github.com/pixpark/facebetter-obs-plugin/releases" target="_blank">下载</a>
</p>

<p align="center">
  <img src="./assets/obs-hero.webp" alt="OBS 中的 Facebetter 美颜面板" width="880">
</p>

## 介绍

给 [OBS Studio](https://obsproject.com/) 用的实时美颜滤镜。美肤、美型、美妆、美体、LUT、贴纸和虚拟背景都在本机处理，直接进直播画面。

这个仓库只发布安装包，不包含源码。

| | |
| --- | --- |
| macOS | 13 及以上，Intel 与 Apple 芯片 |
| Windows | 10 / 11，64 位 |
| OBS Studio | 28 及以上，64 位 |

面板语言跟随 OBS。支持简体中文、繁体中文、英语、日语、韩语、葡萄牙语、西班牙语、德语。其余语言显示英文。

## 下载

在最新的 [Release](https://github.com/pixpark/facebetter-obs-plugin/releases/latest) 里：

| 文件 | 平台 |
| --- | --- |
| `facebetter-obs-macos-latest.zip` | macOS，Intel 与 Apple 芯片 |
| `facebetter-obs-windows-latest.zip` | Windows x64 |

安装前请完全退出 OBS，菜单栏里的 OBS 也要退出。

## macOS

1. 解压。
2. 打开 `Facebetter-OBS-*-macos-universal.pkg`。
3. 打开 OBS。

插件只装给当前用户：

`~/Library/Application Support/obs-studio/plugins/facebetter.plugin`

安装包尚未经过苹果公证。系统可能弹出**「未打开」**，并提供**「移到废纸篓」**。不要移到废纸篓。

1. 打开**「系统设置 → 隐私与安全性」**。
2. 在被拦截的 Facebetter 安装包旁边，点**「仍要打开」**。
3. 再确认一次**「打开」**。

## Windows

1. 解压。
2. 把整个 `obs-facebetter` 文件夹复制到：

   `C:\ProgramData\obs-studio\plugins\`

   插件文件是 `C:\ProgramData\obs-studio\plugins\obs-facebetter\bin\64bit\obs-facebetter.dll`。旁边的 `facebetter.dll` 要留在原处。

3. 打开 OBS。

`ProgramData` 默认是隐藏的。在资源管理器里打开**「查看 → 显示 → 隐藏的项目」**。复制时如果 Windows 要求权限，选择允许。场景和日志在 `%APPDATA%\obs-studio\`，插件不要放到那里。

## 使用

1. 在要处理的源上右键（摄像头、窗口捕获、媒体源等都可以）。
2. 打开**「滤镜 → + → Facebetter 美颜」**。
3. 在面板里登录。浏览器里完成登录或注册后，回到 OBS。

面板可以关掉，之后从**「工具 → Facebetter」**再打开。

处理在这台电脑上完成，画面不会上传。

免费版包含全部效果，输出带水印。订阅后去掉水印。价格见[产品页](https://facebetter.net/zh/obs#pricing)。

## 支持

安装或账号问题：[hello@facebetter.net](mailto:hello@facebetter.net)
