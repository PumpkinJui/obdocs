# 常用工具软件

> 原始文本：  
> 有几个 app：小日常，天文通，天文观星指南，都可以办活动的时候用到——转自丁俊豪  
> *(来自郝晨辰，2021 届七光年天文社社长；丁俊豪为 2020 届七光年天文社社长)*

## 写在最前面

有一套非常有用的数据：

- 呼和浩特市近似经纬度：**40.8 N, 111.7 E**
- 天文台望远镜系统设定经纬度：**40° 48*'* 26*"* N, 111° 41*'* 09*"* E** (40.8072 N, 111.6858 E)
- 呼和浩特市近似海拔：**1051 m**

个人建议，最起码，把最前面那个背下来。非常有用。

至于什么 GCJ02、WGS84……呼市的坐标绝对是落在呼市二环内的，不用纠结太多；天文台的坐标通过反查，似乎是 WGS84 坐标系。  
关联阅读：[同一个坐标，谷歌、高德、百度地图居然指向了三个不同的地方。。。](https://mp.weixin.qq.com/s/eP-TK5yU4DceMKV7q-8UdA)

另外，latitude 是纬度，longitude 是经度，altitude 是海拔。

## 太长不看 (个人推荐)

基本来说，以下两个对大部分人已经够用了：

- 天文通
- 马褂爱天文的天象历

如果真的对天文感兴趣，还可以再选择性增加以下几个：

- 日出日落月相
- Stellarium Mobile 和/或 Star Walk 2
- 天文观星指南

不过，一切取决于你个人需求。

## 说明

### 概念界定

所谓的「软件」，在不同平台上称呼可能不同。例如 Windows 一般称为「软件」，而 Android 一般称为「应用」。

在本文中，以下概念被视为相同，不作特意区分：

- 软件 (software)
- 应用 (application)
- 程序 (program)
- 客户端 (client)
- 可执行文件 (executable file)
- 包 (package)

### 信息介绍

下方介绍了各种各样的常用工具软件。它们有些是网页版，有浏览器就能打开用；有些则需要自行安装到设备上再使用。**对于其中相当一部分来说，你需要会点英语。**

对于所有软件，至少会给出以下信息：

- 软件名称
- 官方网站
- 兼容平台 (优先采用官方数据，没有官方数据的用维护者已知的数据)
- 是否收费

#### 安卓应用的包名

对于安卓平台应用，本文还会给出包名。包名是 Android 应用的唯一标识。使用 [MT 管理器](https://mt2.cn/)等应用可以查看安装包和应用的包名。

包名通常以 `com` 开头，以 `.` 作为分隔符。例如，微信的包名是 `com.tencent.mm` (mm 是 micro message，「微信」直译的缩写)。

包名至少具有以下用途：

- **标识**：包名是 Android 应用的唯一标识。一个应用只能对应一个包名，一个包名也只能对应一个应用。
- **定位**：通过搜索包名，系统和用户可以反向找到其对应的应用。例如：
  - 在浏览器内直接搜索包名，就有可能直接搜出对应的应用。
  - 在大多数安卓手机上，可以通过浏览器访问网址 `market://details?id=PACKAGENAME` 实现应用商店跳转，前提是应用市场内存在该应用。下文部分「应用市场直达」链接即使用此方式实现。
  - 部分应用商店的网页版，以包名作为资源位置 (域名后面斜杠的后方内容) 的一部分来管理应用数据。例如：
    - 酷安：`https://coolapk.com/apk/PACKAGENAME`
    - 小米应用商店：`https://app.mi.com/details?id=PACKAGENAME`
    - 腾讯应用宝：`https://sj.qq.com/appdetail/PACKAGENAME`
    - Google Play Store：`https://play.google.com/store/apps/details?id=PACKAGENAME`

#### 安卓应用的谷歌商店标识

安卓平台应用中，标有「PLAY STORE」的需要从 Google Play Store 下载安装包。Google Play Store 因监管原因，在中国大陆内不可访问，需要「特殊方法」才可访问；除此以外，它还需要 Google 账号才可使用，该账号还需要满足 Google 的其他限制条件才可注册。

若无法注册，也可从 APKPure、APKMirror (同理监管) 等网站下载安装包，或从某些下载站等下载。请自行甄别这些第三方网站及其内容的安全性。

## 聚合

### 天文通

天气、天象、星图等集为一体，真正做到了「天文通」！

内嵌包括但不限于下文中的前三个气象预报源。

- 官方网站：[https://laysky.com/](https://laysky.com/)
- 已知兼容平台：Android, iOS, WeChat Mini Program
- 安卓包名：`com.twtapp` ([应用市场直达](market://details?id=com.twtapp))
- 是否收费：否，有广告

### 日出日落月相

日出日落月相查询、天气信息查询、天文现象查询等。

内嵌包括但不限于下文第一个气象预报源。

- 官方网站：[https://www.oulagongshi.com/](https://www.oulagongshi.com/)
- 兼容平台：Android
- 安卓包名：`com.xueping.solunar` ([应用市场直达](market://details?id=com.xueping.solunar))
- 是否收费：部分

### 天文观星指南

天体位置和升落情况计算、圆盘星图模拟等。感觉弄个星图也能搞定，而且很多数据用不上。

内嵌包括但不限于下文第一个气象预报源。

- 官方网站：[https://www.oulagongshi.com/](https://www.oulagongshi.com/)
- 兼容平台：Android
- 安卓包名：`com.xueping.astroguide` ([应用市场直达](market://details?id=com.xueping.astroguide))
- 是否收费：部分

## 星图

### Stellarium

开源免费的桌面端星图软件。

- 官方网站：
  - [https://stellarium.org/zh_CN/](https://stellarium.org/zh_CN/)
  - [https://github.com/Stellarium/stellarium](https://github.com/Stellarium/stellarium)
- 兼容平台：Windows, macOS, Linux
- 是否收费：否

### Stellarium Mobile

天文通内置的星图类似这个，但那个必须在线使用；这个安装以后可以离线使用。

Web 端地图有问题，定位可能会锁赤道和本初子午线。

分 Free 和 Plus 两版，社长有安卓的 Plus 版安装包 *(虽然是盗版的)*。

PS：和上面是相同的名字，但开发团队完全不同；除此以外，一个开源免费一个闭源付费。

- 官方网站
  - [https://www.stellarium-labs.com/](https://www.stellarium-labs.com/)
  - [https://stellarium-web.org/](https://stellarium-web.org/)
- 兼容平台：Android [PLAY STORE], iOS, Web
- 安卓包名
  - `com.noctuasoftware.stellarium_free`
  - `com.noctuasoftware.stellarium_plus`
- 是否收费：部分

### Star Walk 2

也是星图软件，比 Stellarium Mobile 好看。  
功能有交织，但不完全相同，一者也不能把另一者完全包含。但相比之下，似乎 Star Walk 2 更偏向初学者。

分 Free (Ads+) 和 Premium 两版。社长有安卓的 Premium 版安装包 *(虽然也是盗版的)*。

- 官方网站：[https://starwalk.space/zh-Hans](https://starwalk.space/zh-Hans)
- 兼容平台：Android [PLAY STORE], iOS
- 安卓包名：
  - `com.vitotechnology.StarWalk2Free`
  - `com.vitotechnology.StarWalk2`
- 是否收费：部分

### 北京天文馆活动星图

实体星图，含 4.5 等及以上恒星，不含日、月、行星 (因为它们的自行相当明显，没法画)。

- 官方网站：[https://weidian.com/item.html?itemID=3562387231](https://weidian.com/item.html?itemID=3562387231)，或前往北京天文馆购买

## 天象历

### 马褂爱天文

- 官方网站：
  - 微信公众号「马褂爱天文」
  - [http://magua.china-vo.org/](http://magua.china-vo.org/)
  - [https://www.weibo.com/ls0255](https://www.weibo.com/ls0255)
- 兼容平台：WeChat, Weibo, Web
- 是否收费：否
- 使用方法：按介绍操作，将天象历导入手机日历即可

## 天气

国内气象预报通常不包括云量……不知道为什么。  
想看云量，中国天气网、彩云天气什么的都用不了，最多只能看看卫星云图……  
在这一点上，国外的软件做得比国内好多了。

### 晴天钟

这个网站的地图有问题，建议先点「直接看看你当前所在地的预报吧！」(但这个是用 IP 查询的，位置相当不准)，再划到页面最下方，用上面的坐标查询。

查询后，建议选择「天文用途」预报一项。

- 官方网站：[https://7timer.info/](https://7timer.info/)
- 兼容平台：Web
- 是否收费：否

### meteoblue

这个网站的定位有时也会偏移，此时建议搜索「Hohhot」，或输入坐标。

侧边栏的「7-Day Weather」(主页)、「Outdoor & Sports - Astronomy Seeing」和「Forecast - Meteogram, MultiModel, MultiModel Ensemble」参考价值较大。

- 官方网站：[https://www.meteoblue.com/](https://www.meteoblue.com/)
- 兼容平台：Android [PLAY STORE], iOS, Web
- 安卓包名：`com.meteoblue.droid`
- 是否收费：部分

### ClearOutside

进去输坐标就对了。如果输坐标以后变成了一个 Error 页面，就退回上一步，直接修改当前网址里面的两个数字。

- 官方网站：[https://clearoutside.com/](https://clearoutside.com/)
- 兼容平台：Android [PLAY STORE], iOS, Web
- 安卓包名：`com.firstlightoptics.clearoutside`
- 是否收费：否

### Windy.com

偏专业向。*但是就咱们需求而言，也没有那么难用……*

- 官方网站：[https://www.windy.com/](https://www.windy.com/)
- 兼容平台：Android [PLAY STORE], iOS, Web
- 安卓包名：`com.windyty.android`
- 是否收费：部分

### Windy.app

和上面的不是一家，但没有找到明确的功能对比。同样偏专业向。*我个人会更喜欢用 Windy.com 一点。*

- 官方网站：[https://windy.app/](https://windy.app/)
- 兼容平台：Android [PLAY STORE], iOS, Web
- 安卓包名：`co.windyapp.android`
- 是否收费：部分

### 日常天气查询

你能想到的各种方式都可以用了：手机自带天气、中国天气网、彩云天气，甚至央视一套新闻联播后面的天气预报……我就不多嘴了。
