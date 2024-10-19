# 常用工具软件 (未完成)

> 原始文本：  
> 有几个 app：小日常，天文通，天文观星指南，都可以办活动的时候用到——转自丁俊豪  
> *(来自郝晨辰，2021 届七光年天文社社长；丁俊豪为 2020 届七光年天文社社长)*

## 太长不看

个人推荐如下：

### 低配

- 天文通
- 马褂爱天文的天象历

### 中配

在上一条基础上：

- 日出日落月相
- Star Walk 2

### 高配

在上一条基础上：

- 天文观星指南
- Stellarium / Stellarium Mobile

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

下方介绍了各种各样的常用工具软件。它们有些是网页版，有浏览器就能打开用；有些则需要自行安装到设备上再使用。

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

内嵌但不限于下文中的前三个气象预报源。

- 官方网站：[https://laysky.com/](https://laysky.com/)
- 已知兼容平台：Android、iOS、微信小程序
- 安卓包名：com.twtapp ([应用市场直达](market://details?id=com.twtapp))
- 是否收费：否，有广告

### 日出日落月相

日出日落月相查询、天气信息查询、天文现象查询等。

内嵌但不限于下文第一个气象预报源。

- 官方网站：[https://www.oulagongshi.com/](https://www.oulagongshi.com/)
- 兼容平台：Android
- 安卓包名：com.xueping.solunar ([应用市场直达](market://details?id=com.xueping.solunar))
- 是否收费：部分

### 天文观星指南

提供所有已知天体查询、圆盘星图模拟等服务。

内嵌但不限于下文第一个气象预报源。

- 官方网站：[https://www.oulagongshi.com/](https://www.oulagongshi.com/)
- 兼容平台：Android
- 安卓包名：com.xueping.astroguide ([应用市场直达](market://details?id=com.xueping.astroguide))
- 是否收费：部分

## 天气

### 晴天钟

### meteoblue

### ClearOutside

### Windy.com

### Windy.app

### 中国天气网

## 星图

### Stellarium

- 官方网站：[https://stellarium.org/zh_CN/](https://stellarium.org/zh_CN/)
- 兼容平台：Windows、macOS、Linux
- 是否收费：否

### Stellarium Mobile

这俩是相同的名字，但开发团队完全不同；除此以外，一个开源免费一个闭源付费。

- 官方网站
  - [https://www.stellarium-labs.com/](https://www.stellarium-labs.com/)
  - [https://stellarium-web.org/](https://stellarium-web.org/)
- 兼容平台：Android (PLAY STORE)、iOS、Web
- 安卓包名
  - com.noctuasoftware.stellarium_free
  - com.noctuasoftware.stellarium_plus
- 是否收费：部分

### Star Walk 2

比 Stellarium 好看。

- 官方网站：[https://starwalk.space/zh-Hans](https://starwalk.space/zh-Hans)
- 兼容平台：Android (PLAY STORE)、iOS
- 安卓包名：
  - com.vitotechnology.StarWalk2Free
  - com.vitotechnology.StarWalk2
- 是否收费：部分

## 天象历

### 马褂爱天文

- 官方网站：
  - 微信公众号
  - [http://magua.china-vo.org/](http://magua.china-vo.org/)
  - [https://www.weibo.com/ls0255](https://www.weibo.com/ls0255)
- 兼容平台：WeChat、Weibo、Web
- 是否收费：否
- 使用方法：按介绍操作，将天象历导入手机日历即可

### 中国天文年历

实体书籍，中国科学院紫金山天文台编，科学出版社出版，每年一本，价格 300 元人民币以上。

这个其实又贵又没什么用……太专业了。
