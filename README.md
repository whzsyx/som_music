#### 介绍
基本的音乐播放器功能,超小的运行环境不到2MB。

接口端依赖网易云音乐 API https://github.com/Binaryify/NeteaseCloudMusicApi 项目，需先启动接口端才可正常运行。

启动命令：`npm run dev`

编译命令：`npm run build`

2022-07-04

1. 新增搜索部分功能（未完工）
2. 新增支持二进制编译生成exe文件(dist\build)

2022-06-30

1. 新增设置功能：
    1. 自定义主题颜色，拖动选择器实时更新所有窗口颜色变化
    2. 程序配置支持退出、托盘
    3. 歌词主题自定义，支持实时更新变化
2. 新增托盘功能和托盘菜单功能（适应主题）
3. 新增MV视频
4. 优化歌词渲染方式

2022-06-22

目前实现了精选、排行榜、歌星、歌词


#### 截图预览
![主界面](preview/preview1.png)

![歌词](preview/preview2.png)

![设置](preview/preview3.png)

![托盘菜单](preview/preview4.png)

![MV视频](preview/preview5.png)