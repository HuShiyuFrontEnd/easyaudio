<<<<<<< HEAD
# easyauido
一个简单易用的音频模块（施工中，请看develop分支）
=======
# 正在开发中的
你目前看到的版本并不完善，提供了基本的demo，但是还是值得参考的<br>
有关webaudio的问题，可以联系作者，他愿意和你一起探讨(894416038@qq.com)

# easyaudio(正在逐步完成的过程中)
一个简单易用的音频模块 无框架版本/VUE单文件组件版本<br>
一个由webAudio API搭建起来的功能强大的音频操作模块<br
本项目的示例基于Vue搭建

## 怎样的开发者可以参考下这个项目？
如果你需要的是，迅速的播放一般格式的音频，功能仅限于循环播放、自动播放等等，或者你需要使用自带的播放控件，又或者你是在搜寻一些类似于“IOS上如何自动播放”之类的问题，，那么你不太需要这个项目。你可能需要的是`<audio>`标签引入并操作音频，这个思路能解决绝大多数情况下的音频播放需求<br>
如果你不幸遇到了以下情况中的一种，我衷心希望这个项目能给你带来些许温暖：
* AAC格式/M4A格式等在某个平台上无法播放/无法缓冲播放
* 需要做音频可视化，需要获取音频数据
* 需要自己定制音频的交互UI，需要一个获取各种数据和数据更新的工具
* 想做点滤波器、声源位置改变、声道混合之类的
* 想了解一下Webaudio这门技术，找一个应用类的项目学习一下
* 制作声音类的交互（音乐游戏等），需要一个方便的控制器

## WebAudio
webaudio是audio标签后，一个对于开发者更为透明的音频处理方案，虽然学习成本提高了，但是开发者可以参与的过程也更多了，更加丰富的API。另外webaudio尚处于未完全制定完成的过程中，虽然现代浏览器的支持足够了，不过有些地方确实有些细节不同。<br>
这里推荐两个链接，非常有帮助：<br>
https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API  MDN上详尽易读的API文档<br>
https://www.html5rocks.com/en/tutorials/webaudio/intro/  一篇带你起飞的简单但详细的优秀指南

## 简单开始
```javascript
//导入最基本的Player模块
import { EasyPlayer as Player } from './easyaudio/easyaudio.core.js';
//最简单的注入url的播放
Player.singlePlay(url);
```
更多的内容，写在了demo的注释中，后面会陆续搬运到README中
>>>>>>> develop
