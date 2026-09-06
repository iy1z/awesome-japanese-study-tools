# 日语辞典软件

先说我的推荐：Android 端 欧路词典+ EBPocket，电脑端 GoldenDic。

下面按照软件上手难度递增，介绍下接触过的同类软件。

## Android 端

### 网易

基础释义免费，会员才可使用《新世纪日汉双解大辞典》（2009 年出版，近 17 万词条）的词库

年卡 168（买一年送一年），半年卡 128，月卡 25，连续包月首月 6 元，次月 18

### 沪江小 D

完全免费，词库数据是《现代日汉双解词典》（2012 年出版，4 万 2 千余条词库），

### MOJi

基础释义免费，词库数据未知，由于支持用户自己创词，搜索结果和前面的相比会好一点（个人主观评价）。

基础会员 78，高级会员每月 8 元，半年 25 元，1 年 35 元

与上面的相比，接下来介绍的词典都是由出版社和软件公司共同出品的软件，都没有丰富的拓展功能，但胜在解释权威可靠更新及时。

### 版权词典

### [海笛词典公司](https://haidii.com/hdmcenter.html)

整体质量都比较一般，功能单一

#### 日语大词典

[官网下载链接](https://pkgdl.haidii.com/pkg/25200/lnrm_xrhhrcd_25200_fxxz.apk)
买断制：98
数据是新日汉辞典和
[新汉日辞典](https://book.douban.com/subject/26991436/)，其中新日汉辞典在 2017 年出了修订版，有兴趣的话可以去验证一下看看是不是最新版。

#### 外研社日语词典

[官网下载链接](https://pkgdl.haidii.com/pkg/8015/wys_rhhr_8015_fxxz.apk)
软件买断制：45 元
数据是《现代日汉汉日词典》
收词：日汉一万八千，汉日一万八千

### Google Play Store 上架的日语词典 App

虽然[该网站](http://blog.sina.cn/dpool/blog/u/3704881170#type=-1)给出了原文词典 App 的文件，但要安装到手机上，还有很多繁琐的步骤，所以请根据自己的能力和时间决定是否要花时间来折腾。

不想折腾，要购买的话，可以参考这篇文章[跨境通 VISA/万事达借记卡介绍与网上支付体验](https://poplite.xyz/post/2018/03/05/boc-debit-card-guide-for-online-payment.html#8-%E6%9D%82%E9%A1%B9)办张卡,然后注意自己的代理位置——最好是一直都挂在日本。

接下来介绍的词典软件都需要自己导入词典资源才可使用，上手较为麻烦。

### [欧路词典](https://www.eudic.net/v4/en/app/eudic)

由于并非为日语设计的词典软件，对输入十分敏感，无法转换简体汉字和日语漢字，比如输入“踌躇”是无法查到「躊躇」，所以新手用起来会比较有压力。

买断制 78 元，不过不解锁会员，单「查词」功能而言，几乎没有影响影响（会员功能主要是云同步）

再提下欧路的在线词典，详细的操作步骤在[eudic_handbook_for_japanese](../websites/eudic_handbook_for_japanese.md)

### [EBPocket](http://ebstudio.info/manual/EBPocket_android/)

作者提供了免 Google 框架的免费版本的 APK 文件：[EBPocket.apk](http://ebstudio.info/download/ebpocket/1_15_0/EBPocket.apk)，但是这个非常旧了，虽然能用，但是不能加载太多的词典。

词典资源可以参考[【资源分享】史上最强词典 EBPocket 安装教程+24G 词典资源免费放送](https://mp.weixin.qq.com/s/RYUHtLszaD6I7enp518L-g)和知乎这个回答

### [AnkiHelper](https://github.com/mmjang/ankihelper)

这个实际上要与 Anki 搭配使用，上手难度极大。

### [Tomoshi 日语词典](https://tomoshi.app)

自带离线词典数据、装完即用的日语词典 App，Android 版已上架 Google Play（大陆用户可从腾讯应用宝安装），另有 iPhone 版与 Windows / macOS 桌面版。功能与桌面版一致，详见下方「Windows 端」一节。

## Windows 端

之前介绍的词典软件大都由有自己的网页版，在电脑上都能用。

下列介绍词典软件都需要自己下载词典文件的外壳软件，如果只需要一个可查词的网站，请参考[websites](../websites/README)部分的内容。

另外，接下来介绍的软件，都在不同程度上支持剪贴板查词，也就是像这样：

![](https://markdoen-1304943362.cos.ap-nanjing.myqcloud.com//_00_00_00-00_00_30.gif)

但就整体效果而言：

1. GoldenDict：需要借助[日本語非辞書辞書](https://github.com/NoHeartPen/JapaneseConjugation)项目的 v2 版本的`日本語非辞書辞書.mdx`文件 和[ hunspell_ja_JP](https://github.com/MrCorn0-0/hunspell_ja_JP)，才可以可以实现完美的划词体验
2. 欧陆词典：无法处理形容词，以及特殊标记，但是支持多重嵌套（使被态、部分简单的句型），
3. 沙拉查词：无法处理用言变形，但是可以借助 [日本語非辞書辞書](https://github.com/NoHeartPen/JapaneseConjugation) v3 版本来实现类似 GoldenDict 的查词体验
4. EBWin：无法处理用言变形，但是可以通过 [日本語非辞書辞書](https://github.com/NoHeartPen/JapaneseConjugation) v3 版本来实现类似 GoldenDict 的查词体验
5. MOJi 辞書 Plugin ： 准确率不稳定，向开发者反应过相关问题，以后也许会提高准确率
6. Yomichan 和 rikaikun ：支持简单的动词活用，没有第三方的工具来提高准确率

### 欧路词典

电脑付费 168，不付费就只能加载 3 本词典，但不影响同步。

不想折腾、愿意付费的用户的首选，但注意欧路词典不能加载 EBWin 格式的词典。

### [EBWin](http://ebstudio.info/manual/EBWin4/EBWin4.html)

免费，不支持云同步笔记和查词记录；

有很多独家词典，但都比较旧；不过也支持加载 mdx 格式词典（这种格式有很多比较新的词典）；切换字体很方便；

可以用第三方工具[ebwin2eudic](https://github.com/NoHeartPen/awesome-japanese-study-tools/tree/master/tools/ebwin2eudic)来同步查词记录

### GoldenDict

相关评价和教程在[README.md](https://github.com/NoHeartPen/awesome-japanese-study-tools/tree/master/tools/goldendict_for_japnese_portable/)。

### [Tomoshi 日语词典](https://tomoshi.app)

与上面几款「外壳 + 自备词典文件」的软件不同，Tomoshi 自带词典数据，装完即用，不需要导入任何词典。提供 Windows、macOS、Android 与 iPhone 版：桌面版从官网下载（Windows 也可从微软商店安装），Android 版上架 Google Play，iPhone 版上架 App Store；大陆用户可从境内站 [tomoshi.cn](https://tomoshi.cn) 下载桌面包，Android 版上架腾讯应用宝，iPhone 版上架中国区 App Store。

特点：

1. 核心查词完全离线，词典数据本地存储；查词记录不上传，查词不需要注册账号
2. 面向「说对、写对」的产出型功能：自他动词配对、近义词辨析、中日反查、口语/书面语对应
3. 词条附重音（音高）信息，常用词发音按使用频率持续人工核验
4. 支持用言活用形还原（输入「食べなかった」可查到「食べる」）
5. 云端朗读与 AI 释义扩展是联网功能，目前免费、有每日限额，作者已声明未来将转为付费以覆盖成本；**AI 释义扩展只在国际版提供，大陆版不含**。查词本身永久免费

基础释义来自 JMdict 等开源项目；源自开放项目的数据及其中文释义、辨析卡片按表以 CC BY-SA 等开放许可公开下载（[tomoshi-app/tomoshi-dict-data](https://github.com/tomoshi-app/tomoshi-dict-data)）。桌面应用本体暂未开源。

## 浏览器拓展

推荐使用 Microsoft Edge 浏览器，兼容 Chrome 的拓展，不用 FQ

### [沙拉查词](https://saladict.crimx.com/)

#### 优点

1. 国内开发者开发，上手难度较低
2. 可以和 Anki、欧路词典、扇贝单词等同步单词本，但需要自己动手
3. 内置沪江小 D 和 Weblio 辞書，基本满足日常需要

### [MOJi 辞書 Plugin](https://www.mojidict.com/article/1BvHLjMm8u)

还行，闲逛时也能学点日语，不过只能在浏览器内使用

### [rikaikun](https://github.com/melink14/rikaikun) 和 [Yomichan](https://foosoft.net/projects/yomichan/)

由于都是国外开发者开发，所以干脆放在一起说。

上手难度都比较大，作者也没怎么仔细研究，只是简单体验了下。由于是专门为了日语学习而设计，所以有些细节做得比沙拉查词好: 比如 Yomichan 除了可以与 Anki 搭配，还可以导入 EBwin 格式的词典，对于动词活用变形也有一定的支持。

### [Tomoshi 取词扩展](https://tomoshi.app/extensions/)

Tomoshi 桌面应用配套的划词取词扩展，**需要先启动 Tomoshi 桌面应用**——扩展只是前端，查询由本地桌面应用提供，因此整个取词过程离线完成、不经过任何服务器。

用法：选中日语文本后按住 Alt（可改为 Ctrl / Shift），页面内弹出悬浮窗显示释义、音高图、语法兜底与发音按钮，松开即关闭。支持用言活用形还原。

- Chrome 应用商店 / Microsoft Edge 加载项商店均有上架（Brave、Vivaldi 等 Chromium 系浏览器可用 Chrome 版）；Edge 加载项商店大陆可直接访问，Chrome 应用商店不可达时可从 [tomoshi.cn](https://tomoshi.cn) 下载离线包以「加载已解压的扩展程序」方式安装
- Safari 版随 macOS 桌面应用一并安装，在 Safari 扩展设置里启用
- 扩展以 AGPL-3.0 开源：[tomoshi-app/tomoshi-extension](https://github.com/tomoshi-app/tomoshi-extension)
