# U校园自动挂机脚本

这是一个为 [U校园](https://u.unipus.cn/) 设计的Tampermonkey（油猴）脚本，旨在帮助用户自动处理"长时间未操作"的挂机检测弹窗，从而确保学习时长能够持续有效计算。

## ✨ 功能特性

- **🚀 专注核心**：精准检测并自动点击"由于你长时间未操作，请点确定继续使用。"弹窗的确认按钮。
- **🕒 自定义时长**：可自由设定需要挂机的总时长（分钟）。
- **📊 状态面板**：提供一个简洁、可拖动、可收起/展开的控制面板，实时显示运行状态和已挂机时间。

## 🖥️ 界面一览

控制面板是一个简洁的浮动窗口，包含时长设置、启停按钮和状态显示。您可以随意拖动它，或者通过点击标题栏的 `-`/`+` 来收放。

## 📦 安装步骤

1.  **安装用户脚本管理器**
    首先，你的浏览器需要安装一个用户脚本管理器扩展。推荐使用 [Tampermonkey](https://www.tampermonkey.net/)。
    - [Chrome 安装地址](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    - [Firefox 安装地址](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
    - [Edge 安装地址](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)

2.  **安装本脚本**
    点击下方的链接，Tampermonkey会自动弹出安装页面，点击"安装"即可。
    - **[从 GitHub 安装](https://github.com/Yishun3762/UnipusAutoScript/raw/main/script.user.js)**

## 🕹️ 使用方法

1.  安装成功后，在U校园的任意学习页面，脚本会自动加载并显示控制面板。**注意**：最好不要在考试/unit test等相关单元打开，否则可能失效。
2.  在"挂机时长"输入框中设置你想要挂机的分钟数。
3.  点击"开始挂机"按钮，脚本将开始工作。
4.  脚本运行时，会自动检测并处理"长时间未操作"的提示。
5.  你可以随时点击"停止挂机"，或等待达到设定时长后脚本自动停止。
6.  控制面板可以随意拖动，也可以点击标题栏的 `-` / `+` 按钮进行收起和展开。

## 📄 许可协议

本脚本基于 [MIT License](https://github.com/Yishun3762/UnipusAutoScript/blob/main/LICENSE) 发布。 
