# 网易云音乐无版权歌曲 去灰+播放+下载（安卓+IOS+PC教程）

**目录(点击以下链接跳转)**

* [说明](#说明)
* [PC使用教程](#PC使用教程)
* [安卓使用教程](#安卓使用教程)
* [IOS使用教程](#IOS使用教程)
* [PC下载不限速教程](#PC下载不限速教程)
* [效果展示](#效果展示)
  * [PC](#PC)
  * [安卓](#安卓)
  * [IOS](#IOS)
* [项目地址](#项目地址)

### 说明
 * 仅适用于网易云音乐，`请勿广泛传播,请勿广泛传播,请勿广泛传播`（服务器资源有限，下载峰值仅为每秒640KB左右，按下载人数平摊）。
 * `仅在需要时使用,仅在需要时使用,仅在需要时使用。（特指安卓和IOS,不用的时候请务必关闭wifi代理）`**否则可能出现网页打不开或app网络连接错误等情况(只有安卓和IOS会有这个问题,PC端不会)**
 * 不是所有歌曲都能播放或下载，存在播放的歌曲和原曲不是同一首的情况
 * 安卓和IOS必须连接wifi,只能使用wifi代理（不能使用流量）,更换wifi须重新配置
 * 音乐下载好之后上传到我的音乐云盘即可永久保存(安卓,PC,IOS 都可以听)
 * 下载的歌曲为`128K`的音源

### PC使用教程
* `服务器：lwguang.com,端口：8888,下载峰值640kb左右每秒`

![image](http://47.102.84.37:6081/api/public/dl/z3hGWwj6/pc-config.jpg)


### 安卓使用教程
WLAN > 修改网络(修改当前连接的wifi) > 高级选项 > 代理  (由于手机品牌不同描述可能存在差异)
* `主机名：lwguang.com,端口：8888,下载峰值640kb左右每秒`
* __按下图配置好之后你就打不开这个网站了。不用了一定一定一定要把代理设置为无（别怪我没提醒）__
<img src="http://47.102.84.37:6081/api/public/dl/b_2QjS_R/ad.jpg" width="50%"></img>

### IOS使用教程
无线局域网 > HTTP 代理 > 配置代理
* `服务器：lwguang.com,端口：8887,下载峰值640kb左右每秒`
* __按下图配置好之后你就打不开这个网站了。不用了一定一定一定要把代理设置为无（别怪我没提醒）__
![图片？没有！同上面安卓配置 端口改成：8887]()

### PC下载不限速教程
* `下载峰值 用户当前网速的峰值`

* 下载这个文件 https://wws.lanzous.com/iYdOCdl942j
* 下载好文件后解压该文件，进入解压后的文件，右键config.ini 打开方式->记事本（详见下图）。
![](http://47.102.84.37:6081/api/public/dl/pgieY0B7/pcwxz-1.png)

* 配置如下

![](http://47.102.84.37:6081/api/public/dl/ocqWokmS/pcwxz-2.png)

* 双击`网易云代理.exe `成功打开网易云说明配置成功了,没反应或提示配置错误请返回上一步检查路径是否错误。
* 下图如果点击 `测试` 提示 该代理不可使用 说明上一步配置错误请检查

![](http://47.102.84.37:6081/api/public/dl/vKmJAfaV/pcwxz-3.png)
* 点击`确定`后重启网易云音乐即可生效

* 最后附上原贴地址 https://www.52pojie.cn/thread-1013038-1-1.html

# 效果展示
### PC
![image](http://47.102.84.37:6081/api/public/dl/CKXIFOJK/pc-preview.jpg)

### 安卓
<img src="http://47.102.84.37:6081/api/public/dl/RRzqMIqk/ad-preview.jpg" width="50%"></img>

### IOS
![图片？没有！别找了]()

# 项目地址
**原理以及以上所有代码均出自 https://github.com/nondanee/UnblockNeteaseMusic 向大佬致敬（感兴趣可以去看看）**
