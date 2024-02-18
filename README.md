# Godot XR Template

![GitHub forks](https://img.shields.io/github/forks/godotvr/godot-xr-template?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/godotvr/godot-xr-template?style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/godotvr/godot-xr-template?style=plastic)
![GitHub](https://img.shields.io/github/license/godotvr/godot-xr-template?style=plastic)

This repository contains a template Godot project for building a simple VR game.
这个存储库包含一个用于构建简单 VR 游戏的 Godot 项目模板。


## Versions

Official releases are tagged and can be found [here](https://github.com/GodotVR/godot-xr-template/releases).

The following branches are in active development:
|  Branch  |  Description                  |  Godot version  |
|----------|-------------------------------|-----------------|
|   main   | Current development branch    |  Godot 4.2+     |
|    4.1   | Godot 4.1 development branch  |  Godot 4.1      |
|    3.x   | Godot 3.x development branch  |  Godot 3.5+     |


# Assets

This project uses the following assets:
这个项目使用以下资源：

 - [Godot XR Tools](https://godotengine.org/asset-library/asset/1515)
 - [OpenXR Loaders](https://github.com/GodotVR/godot_openxr_loaders)


# Getting Started

Start by downloading this asset from github; or by installing it from the Godot
Asset Library.

The game should be playable with a splash screen and two example scenes the player
can move between.

The game should be customized by:
 - Modifying the splash-screen texture to represent the game
 - Modifying the icon.png for the game
 - Add game state variables to the game_state.gd singleton class
 - Replacing the demo zones with zones suitable to the game



通过从 GitHub 下载这个资产开始，或者通过在 Godot 资产库中安装它。

游戏应该是可玩的，有一个启动画面和两个示例场景，玩家可以在它们之间移动。

游戏应该通过以下方式进行定制：
 - 修改启动画面的纹理以代表游戏
 - 修改游戏的 icon.png
 - 在 game_state.gd 单例类中添加游戏状态变量
 - 用适合游戏的区域替换演示区域

# Exporting to Android

The template contains a copy of the XR loaders plugin
and preconfigured exports for android based headsets that support OpenXR.

Before this can be used you do need to install the android build template.
Select the menu `Editor->Manage Export Templates...` to download the templates.
Select the menu `Project->Install Android Build Template...` to install the template.

Make sure you set the correct entry in the export templates to runable
if you want to use one click deploy to your device.

Please refer to the official documentation for Godots prerequisits for exporting to android:
https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_android.html



该模板包含 XR loaders 插件的副本
并针对支持 OpenXR 的基于 Android 的头戴式显示器进行了预配置的导出设置。

在使用之前，您需要安装 Android 构建模板。
选择菜单 `Editor->Manage Export Templates...` 下载模板。
选择菜单 `Project->Install Android Build Template...` 安装模板。

确保在导出模板中设置正确的条目，以便在使用一键部署到设备时可以运行。

请参考 Godot 导出到 Android 的官方文档以获取导出到 Android 所需的先决条件：
 https://docs.godotengine.org/en/stable/tutorials/export/exporting_for_android.html

# Recommended Asset Locations

Common areas to find assets are:
 - [Godot Asset Library](https://godotengine.org/asset-library/asset)
 - [AmbientCG](https://ambientcg.com/) for object and sky textures
 - [FreePD.com](https://freepd.com/) for sound tracks
 - [FreeSound](https://freesound.org/) for sound effects
 - [Kenney.nl](https://kenney.nl/) 



常见的寻找资产的地方包括：

- [Godot Asset Library](https://godotengine.org/asset-library/asset)
- [AmbientCG](https://ambientcg.com/) 用于物体和天空纹理
- [FreePD.com](https://freepd.com/) 用于音轨
- [FreeSound](https://freesound.org/) 用于音效
- [Kenney.nl](https://kenney.nl/)


# More Information

Information on the Godot XR Tools can be found on [the website](https://godotvr.github.io/godot-xr-tools/).

关于 Godot XR Tools 的信息可以在 [官方网站](https://godotvr.github.io/godot-xr-tools/) 上找到。
