# 弹弹play

#### ▶️ 介绍

弹弹play播放器：全功能本地视频+弹幕播放器

#### 🌐 下载

[从网盘下载各个平台版本（推荐）](https://kaedei.lanzouo.com/s/dandanplay)

1. Windows版： [联想应用商店](https://lestore.lenovo.com/detail/10343) | [GitHub发布页](https://github.com/kaedei/dandanplay/releases)
2. 安卓版： [安卓概念版Gitee](https://gitee.com/xyoye/DanDanPlayForAndroid/releases) | [安卓概念版GitHub](https://github.com/xyoye/DanDanPlayForAndroid/releases)
3. iOS版： [NipaPlay](https://apps.apple.com/cn/app/nipaplay/id6751284970) | [AniXPlayer测试版](https://testflight.apple.com/join/R6JotnNG) | [NipaPlay测试版](https://testflight.apple.com/join/4JMh3t44)
4. UWP版： [微软商店](https://www.microsoft.com/store/productId/9nwpvd7t1hpw)
5. macOS版： [AniXPlayer](https://github.com/sunsx9316/DanDanPlay_Experience/releases) | [NipaPlay](https://github.com/MCDFsteve/NipaPlay-Reload/releases)
6. Linux版： [NipaPlay](https://github.com/MCDFsteve/NipaPlay-Reload/releases)

#### 📜 近期更新

[查看完整更新历史](https://www.dandanplay.com/blog.html)

**Windows版 v17.0.0.0**

1. 推出新版弹弹play字幕渲染器，暂时仅支持本地文件。新版字幕渲染器使用了单独的模块，相比现有的字幕渲染（内核渲染）有以下改进：
    - 全部内核：
      - 可以按屏幕分辨率渲染字幕，大幅提升文字清晰度；
      - 支持将字幕显示到视频黑色边框中；
      - 支持编码自动识别；
      - 支持多种字幕文件搜索方式；
      - 支持自定义字幕样式（SRT格式）；
      - 支持硬件加速，性能优秀；
      - 支持修改字幕编码，实时生效；
    - 另外：
      - VLC内核：支持开启硬件加速同时启用字幕
      - FFMpeg内核：支持渲染ASS特效字幕，解决SRT格式的排版问题
      - EVR内核：不再依赖DirectVobSub滤镜
      - WMP内核：解决了无法显示字幕的问题
2. 新增"转码中心"，支持将视频文件转码为不同格式，支持批量转码，支持多任务管理功能；
3. 媒体库新增"文件重命名工具"，支持按照模板批量重命名多个文件或文件夹，支持预览重命名结果；
4. 在线观看功能支持显示上次播放时间，支持记录搜索历史；
5. 新增半星评分显示支持，新增评分数字显示；
6. 播放器界面新增字幕快捷切换菜单；
7. 截图窗口支持打开截图保存目录，新增ESC键关闭窗口功能；
8. 优化了自动下载列表的UI，改为树形结构，支持使用文件夹管理下载任务，支持拖拽移动和排序下载任务；
9. 设置-网络与更新页面新增文件完整性检查功能；
10. 重新设计播放器内核设置界面UI；
11. 优化了进度条小图标的展示效果；
12. 更新了播放器边栏首页、切换字幕边栏的UI样式；
13. 修复了番剧详情页更新历史记录按钮点击无效的问题；
14. 修复了新番时间表在周日首次进入时无法显示的问题；
15. 修复了特殊情况下弹幕可能残留在屏幕上的问题；


**Windows版 v16.5.0.0**

1. VLC内核更新至官方 3.0.23 版本
2. 更新番剧详情页等界面UI，优化emoji显示效果
3. 在线观看功能支持自动匹配文件名，支持保存弹幕库关联
4. 优化了在线观看页面的加载、搜索、跳转的流程
5. 远程媒体库增加FTP连接功能
6. 首页“继续播放”模块增加清空播放历史功能
7. 媒体库-番剧列表界面新增“关注”按钮，可以手动搜索添加关注番剧
8. 在线观看页面-剧集列表新增“显示全部剧集”开关
9. 播放列表页新增右键菜单
10. 搜索关注窗口增加数据库选择功能（弹弹play、TMDB），改进了交互体验
11. 支持部分加密m3u8源的串流播放
12. 增加了用户自己的弹幕高亮显示的功能
13. 修复了首页可能加载出错的问题
14. 修复了UWP版切换到新番时间表页面时报错的问题
15. 修复了特殊情况下调整宽高比至视频默认比例时报错的问题
16. 修复了『弹幕外挂』功能在英文版PotPlayer中，无法响应通过左右快捷键快进快退的问题
17. 修复了在线观看配置文件无法解压的问题
18. 修复了关闭“简洁模式下显示窗口边框”选项后，仍显示Windows11系统边框和阴影的问题

#### 💬 用户反馈

[官方反馈社区](https://support.qq.com/products/104929)

[弹弹play文档站](https://doc.dandanplay.com/)
