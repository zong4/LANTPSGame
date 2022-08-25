# 使用指南

1. 源代码中有一个地图文件由于体积过大，所以放在了 **Release** 的 **AddFile** 中，需要下载并解压到如下目录中。

    LANTPSGame\Content\Assets\GMGame\Maps\

2. 安卓的 **.apk** 文件在 **Release** 里，可以根绝相应的版本号下载安装。

3. 目前没有打包其他平台的安装包，如有需要可以自行打包，记得修改 **Input** 里的 **Joysticks** 。

# 玩法

如果下载项目源码可以自行在项目设置的 **Input** 中查看。

如果使用 **Apk** 游玩，操作界面如下。

<img src="https://zong4.github.io/img/LANTPSGame/ControlUI1.jpg" width="700px" title="操作界面">

![操作界面](/MDSource/ControlUI1.jpg)

所有按键均需滑动触发（ **Joysticks** 特性）。

左半边分别为返回，积分板，开门（门前才有用），人物移动摇杆（从上到下，从左到右）。

右半边分别为视角移动摇杆，积分板，开门（门前才有用），移动摇杆（从上到下，从左到右）。

# TODO List

- [x] 联机大厅及相关 UI 。
- [x] 人物动画逻辑及射击。
- [x] 训练营地图
- [x] 积分板
- [x] 对战地图
- [x] **AI**
- [x] 多种武器
- [ ] 移植到安卓
- [ ] 完善动画细节
- [ ] 设置界面完善UI

# 相关资料

## [文章](https://zong4.github.io/2022/05/22/15SpaceCollider/)

## [视频](https://zong4.github.io/gallery/media/#Space-Collider-Demo)


# 改进

游戏依然在测试与改进中，如果在游玩中遇到任何问题或改进意见，请提交 **issue** 至我的 **Projects（Todo Lsit）** 中，非常感谢您的宝贵意见。
