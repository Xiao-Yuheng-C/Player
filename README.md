# 0voice_player

一个视频播放器，开源版 potplayer。  
用于学习和交流音视频技术。 

支持的功能：
- 播放暂停
- 逐帧
- 快进
- 快退
- 变速
- 支持设置缓存队列长度 


## 简介
- 使用 FFmpeg-4.2.1 (x86) 解码，SDL2-2.0.7 (x86) 渲染。  
- 在 Windows 下使用 Qt5.10.x (MinGW x86) 开发。  
- 项目目录下的 .pro 文件，支持在多平台（Windows、Linux、Mac）下 QtCreator 打开编译调试。  

![运行画面](http://gitlab.0voice.com/liaoqingfu/0voice_player/blob/master/0.jpg)
![运行画面](http://gitlab.0voice.com/liaoqingfu/0voice_player/blob/master/0.png)

 
## Windows平台编译调试
1. 下载 FFmpeg、SDL2 动态库，放在 bin 目录下。(直接从官网下载即可，亦可下载本项目最新release，安装后，从安装目录下拷贝动态库。)  

2. 使用 QtCreator 打开 0voice_player.pro。  
3. 编译运行。  

  

