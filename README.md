# 2019Demo-MusicPlayer
# 项目简介
## 项目结构
musicPlayer

|——index.html

|——css

      |——font.css
      
      |——common.css
      
      |——index.css
      
      |——media.css

|——js

      |——index.js

|——music

      |——music.mp3

|——README.md

## 功能介绍

aside：音乐侧边栏 音乐列表

music-intro：展示当前播放的歌曲图片

info：展示当前播放歌曲的信息

control： 上一首 下一首 暂停 播放

progress bar : 歌曲进度条 当前播放的时间 以及可以点击进度条改变歌曲播放进程

icon-me： 音量图标 以及csdn关于我的信息

***
## 技术介绍

原生javascript

主要功能区：

进度条 ：利用了currentTime 和 bar 的比例

时间： 利用了 定时器 和 时间基础转换 以及 dom操作

暂停 下一首等按钮 ： 利用了事件 以及audio的相关事件 如 ：pause ended 等

数据交互：利用了ajax 和 json
