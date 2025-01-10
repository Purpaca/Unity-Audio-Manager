<div align="center">

# Unity Audio Manager

<a href="https://unity.com/releases/editor/whats-new/2022.3.20#notes">
<img src="./docs/images/badge_unity.png" alt="Unity 2022.3.20f1" height=22 />
</a>
<a href="https://space.bilibili.com/3546697445673471">
<img src="./docs/images/badge_btv.png" alt="bilibili_purpaca" height=22 />
</a>
</div>

### 概述

一个适用于Unity项目的音频管理器组件，尝试弥补 Unity 原生音频播放的一些不足：  

- 支持音频播放完毕时执行回调方法
- 支持序列播放多个音频，可以设置序列中每个音频的循环次数
- 直接通过代码播放音频，不再需要提前在场景里摆放挂有`AudioSource`组件的`GameObject`
- 提供了音乐、音效两个频道各自的播放音量管理，并且还可以通过主频道调整全局的音频播放音量

该项目使用的Unity版本为[2022.3.20f1](https://unity.com/releases/editor/whats-new/2022.3.20#notes)。

### 如何使用
- 把这个仓库克隆到本地，把项目适当修改后基于此直接进行你自己项目的开发！
- 把项目中的`Assets/Scripts`目录下的**所有脚本文件**以及整个`Assets/Resources`目录复制导入到你自己的项目中。
- 或者其它能帮助到你的使用方法...

### 答疑解惑
API文档正在编写中...