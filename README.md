# LAN TPS Game

## [Introduce](http://zong4.github.io/2025/01/29/TPS游戏开发/)

由于 **Github MD** 现在不支持嵌入视频，所以以下仅是一个链接（点击跳转至 **B** 站），当然也可以在 [**Release**](https://github.com/zong4/LANTPSGame/releases/tag/Media_v1.0.0) 中下载该视频。

[![Bilibili视频](/MDSource/LANTPSGame.jpg)](https://www.bilibili.com/video/BV1gt4y177cP/?vd_source=0b6d3684e93bbb6631e1931c0c00f657)

## 使用指南

1. 源代码中有一个地图文件由于体积过大，所以放在了 [**Release** 的 **AddFile**](https://github.com/zong4/LANTPSGame/releases/tag/Demonstration_BuiltData.uasset_v1.0.0) 中，需要下载并解压到如下目录中。

        LANTPSGame\Content\Assets\GMGame\Maps\

2. [安卓的 **.apk** 文件](https://github.com/zong4/LANTPSGame/releases/tag/Android_v1.0.0)在 **Release** 里，可以根据相应的版本号下载安装。

3. [**Windows** 平台](https://github.com/zong4/LANTPSGame/releases/tag/Windows_v1.0.0)也一样。

## 操作玩法

### Windows

* 左 **Ctrl**   ：下蹲
* 左 **Alt**    ：静步
* 左 **Shift**  ：快跑
* **Tab**       ：积分板
* **F**         ：交互（目前只有门）
* **Q**         ：打开手电筒
* **H**         ：换手雷
* **G**         ：换枪

其他按键均与常规 **FPS** 游戏相同。

### Android

![操作界面](/MDSource/ControlUI1.jpg)

所有按键均需滑动触发（ **Joysticks** 特性）。

左半边分别为返回，积分板，开门（门前才有用），人物移动摇杆（从上到下，从左到右）。

右半边分别为视角移动摇杆，瞄准（开镜），打开手电筒，攻击，跳跃，换手雷（如果有），换枪，换弹，跑步，下蹲，静步（从上到下，从左到右）。

## Bug

**Apk** 中开手电筒好像没反应，猜测是因为手机是低渲染，可能被过滤了。

## TODO List

- [x] 联机大厅及相关 **UI** 
- [x] 人物动画逻辑及射击
- [x] 训练营地图
- [x] 积分板
- [x] 对战地图
- [x] **AI**
- [x] 多种武器
- [x] 不同打击效果
- [x] 移植到安卓
- [ ] 完善动画细节

## 代码结构

**Content** 中除了 **Asserts** ，其他均来自 **UE** 现有的资源。

**Asserts** 存放游戏中调用的人物、地图、武器等文件（ **GMGame** ），大厅中调用的人物、地图、 **UI** 等文件（ **GMLobby** ），全局的控制文件，如 **GameMode** 、 **PlayerController** 、 **GameInstance** （ **Gameplayer** ）。

（大厅和游戏中用不同的人物可以保证大厅的独立性，下次复用方便，所以游戏的键位在大厅中不能使用）。

## 改进

游戏依然在测试与改进中，如果在游玩中遇到任何问题或改进意见，请提交 **issue** ，非常感谢您的宝贵意见。
