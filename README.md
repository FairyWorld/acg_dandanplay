# 弹弹play

####  :tw-25b6: 介绍
弹弹play播放器：全功能本地视频+弹幕播放器

####  :tw-1f310: 下载

[从网盘下载（推荐）](https://kaedei.lanzouo.com/s/dandanplay)

1. Windows版： [联想应用商店](https://lestore.lenovo.com/detail/10343)
2. 安卓版： [安卓概念版Gitee](https://gitee.com/xyoye/DanDanPlayForAndroid/releases) | [安卓概念版GitHub](https://github.com/xyoye/DanDanPlayForAndroid/releases)
3. iOS版（需要 TestFlight）： [AniXPlayer](https://testflight.apple.com/join/R6JotnNG)
4. UWP版： [微软商店](https://www.microsoft.com/store/productId/9nwpvd7t1hpw)
5. macOS版： [AniXPlayer](https://github.com/sunsx9316/DanDanPlay_Experience/releases) | [NipaPlay](https://github.com/MCDFsteve/NipaPlay)

####  :tw-1f4cb: 近期更新

[查看完整更新历史](https://www.dandanplay.com/blog.html)

**[Windows版][UWP版] v15.13.0**
1. 新增“修改播放器帧率上限”功能，可以配合其他软件对视频和弹幕补帧
2. 新增视频实时美颜功能
3. 画面优化界面中修改参数后会实时生效，不再需要点击“应用”按钮
4. 修复了弹幕来源页面加载时，弹幕偏移的分钟数显示错误的问题
5. 修复了部分情况下远程访问/安卓投屏播放视频时没有云同步观看历史的问题
6. 修复了多个 UI 细节问题

**[Windows版][UWP版] v15.12.0**
1. 适配弹弹play开放平台相关变更
2. 优化媒体库番剧信息刷新速度
3. SVP增加使用ffdshow（旧）的选项

**[Windows版][UWP版] v15.11.0**
1. 新增HDR手动开关
2. 新增视频色彩调整（动态范围修正、饱和度、对比度、亮度、伽马）
3. 支持在更多情况下（如串流）重新选择弹幕库并重新开始播放
4. 字幕翻译新增GPT-4o mini服务
5. 修复手动重新启动远程访问服务时报错的问题

**[Windows版][UWP版] v15.10.0**
1. VLC内核支持HDMI/SPDIF音频直通功能
2. VLC内核支持新增强制开启杜比环绕（Dolby Surround）检测
3. EVR内核调用SVP补帧时将使用AviSynth处理
4. 番剧详情页增加显示动画的预告片、PV等视频链接
5. 播放列表页、播放列表边栏支持拖拽排序
6. 媒体库中右键菜单可以将本地文件/文件夹加入待扫描队列
7. 个人中心等界面的筛选、排序菜单将记住上次的选择
8. 媒体库远程连接增加右键菜单编辑功能
9. 媒体库远程连接登录状态过期时将显示提示
10. 优化远程访问Web页图片加载方式，将优先读取本机缓存
11. 优化磁力链解析种子文件时的缓存机制
12. 优化网络检测与修复工具的相关功能
13. 修复调用SVP补帧时，重复加载视频时无法继续启用的问题
14. 修复部分情况下系统托盘图标和右键菜单显示异常的问题
15. 修复远程访问启动时可能提示“重复添加”错误的问题
16. 修复远程访问Web页选择字幕可能出错的问题
17. 修复了通过网页播放时播放历史没有上传至服务器的问题

**[Windows版][UWP版] v15.9.2**
1. 下载器模块启动时将预热与DHT网络的连接（而不是等到启动首个任务才开始）
2. 新增通过DHT网络将磁力链解析为种子文件
3. “自动下载”页预览结果时会显示此资源是否已经在下载列表中
4. 修复了批量下载时速度可能降低至0的问题
5. 修复了串流播放时，可能会残留连接未断开的问题
6. 修复了串流播放时，长时间暂停后可能无法继续播放的问题

**[Windows版][UWP版] v15.9.0**
1. 媒体库远程连接（smb/webdav/onedrive）支持播放时加载远程磁盘上的同名弹幕文件
2. 加载包含分P投稿的弹幕时，支持自动检测分P并编辑时间，可以将多个分P拼接为一份弹幕
3. 媒体库网页版支持渲染ass格式的字幕
4. 自动下载规则兼容nyaa的RSS格式
5. 更新简繁转换词库，支持转换繁体中文相关俗语，修复部分转换错误
6. 串流播放时支持保存音轨、字幕轨、本地弹幕的选择偏好
7. 串流播放停止时，可以点击左下角播放按钮重新加载
8. 改善了串流播放和m3u8在线播放的成功率
9. 添加了嗅探功能对WebView2的版本号检查和提示
10. 更新下载器内核至v3.0.2
11. 修复了播放器长时间运行时，无法检测到DNS变化的问题
12. 修复连接部分WebDAV服务器时无法开始播放的问题
13. 修复了初始化WebView2时可能报错的问题
14. 修复搜索弹幕库出错时会意外报错的问题

####  :tw-1f4ac: 用户反馈

[官方反馈社区](https://support.qq.com/products/104929)

[弹弹play文档站](https://doc.dandanplay.com/)
