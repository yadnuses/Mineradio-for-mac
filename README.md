# Mineradio for macOS

> Mineradio macOS 测试版下载页。  
> 当前版本面向 Apple Silicon Mac 测试用户，不是正式签名发行版。

![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)
![Architecture](https://img.shields.io/badge/arch-Apple%20Silicon%20%28arm64%29-black)
![Version](https://img.shields.io/badge/version-1.1.1-blue)
![Status](https://img.shields.io/badge/status-test%20build-orange)

## 下载

请前往 GitHub Releases 下载最新版测试包：

[下载 Mineradio 1.1.1 macOS 测试版](https://github.com/yadnuses/Mineradio-for-mac/releases/download/v1.1.1-mac-test/Mineradio-1.1.1-mac-arm64-test.zip)

当前测试包文件名：

```text
Mineradio-1.1.1-mac-arm64-test.zip
```

解压后会得到：

```text
Mineradio.app
```

## 适用设备

当前测试包适用于：

- Apple Silicon Mac
  - M1
  - M2
  - M3
  - M4
- macOS 近期版本

暂不包含 Intel Mac 版本。

## 安装与打开方式

由于这是测试版，没有 Apple Developer ID 签名，macOS 第一次打开时可能会拦截。

推荐打开方式：

1. 下载 `Mineradio-1.1.1-mac-arm64-test.zip`
2. 双击解压
3. 将 `Mineradio.app` 拖到「应用程序」文件夹，或直接放在任意文件夹中测试
4. 第一次打开时，不要直接双击
5. 右键点击 `Mineradio.app`
6. 选择「打开」
7. 在弹窗中再次点击「打开」

如果仍然被拦截：

1. 打开「系统设置」
2. 进入「隐私与安全性」
3. 找到 Mineradio 的拦截提示
4. 点击「仍要打开」

## 重要说明

这是 macOS 测试构建版：

- 未签名
- 未公证
- 适合小范围测试
- 不等同于正式发布版

如果你担心安全性，请不要运行来自未知来源的应用。本测试包仅建议从本仓库下载。

## 功能简介

Mineradio 是一款沉浸式音乐播放器，包含：

- 天气电台
- 音乐搜索与播放
- 歌词舞台
- 粒子视觉效果
- 3D 歌单架
- 网易云音乐与 QQ 音乐相关体验接入

## 常见问题

### 提示“无法验证开发者”怎么办？

这是因为测试包没有 Apple 开发者签名。请使用「右键 → 打开」的方式启动。

### 为什么没有 `.dmg`？

当前版本优先提供简单测试包，因此使用 `.zip` 分发。正式版本后续可以提供 `.dmg`。

### Intel Mac 能用吗？

当前这个包不能保证可用。它是 `arm64` 架构，主要面向 M 系列芯片 Mac。

### 打开后没有反应怎么办？

可以尝试：

1. 确认已经完整解压，不要在压缩包内直接运行
2. 将 `Mineradio.app` 移到「应用程序」文件夹后再打开
3. 使用「右键 → 打开」
4. 如果仍然失败，请反馈你的 macOS 版本、Mac 型号和报错截图

## 测试反馈建议

反馈时请尽量包含：

- Mac 型号，例如 MacBook Air M2
- macOS 版本
- 是否能正常打开
- 是否能播放音乐
- 登录、搜索、歌词、视觉效果是否正常
- 报错截图或 Console 信息

## 版权与说明

Mineradio 原项目由 XxHuberrr 设计与打造。  
本仓库仅用于 macOS 测试包分发。
