---
layout:     post
title:      Android Studio插件整理
subtitle:   android studio 插件
date:       2019-05-26
author:     BY chengzhen
header-img: img/post-bg-universe.jpg
catalog: true
tags:
    - Blog
---

来自:https://ydmmocoo.github.io/2016/06/28/Android-Studio%E6%8F%92%E4%BB%B6%E6%95%B4%E7%90%86/

现在Android的开发者基本上都使用Android Studio进行开发(如果你还在使用eclipse那也行，毕竟你乐意怎么样都行)。使用好Android Studio插件能大量的减少我们的工作量。

1.GsonFormat
快速将json字符串转换成一个Java Bean，免去我们根据json字符串手写对应Java Bean的过程。



使用方法：快捷键Alt+S也可以使用Alt+Insert选择GsonFormat

2.Android ButterKnife Zelezny
配合ButterKnife实现注解，从此不用写findViewById，想着就爽啊。在Activity，Fragment，Adapter中选中布局xml的资源id自动生成butterknife注解。



使用方法：Ctrl+Shift+B选择图上所示选项

3.Android Code Generator
根据布局文件快速生成对应的Activity，Fragment，Adapter，Menu。




4.Android Parcelable code generator
JavaBean序列化，快速实现Parcelable接口。



5.Android Methods Count
显示依赖库中得方法数



6.Lifecycle Sorter
可以根据Activity或者fragment的生命周期对其生命周期方法位置进行先后排序，快捷键Ctrl + alt + K




7.CodeGlance
在右边可以预览代码，实现快速定位




8.findBugs-IDEA
查找bug的插件，Android Studio也提供了代码审查的功能（Analyze-Inspect Code…）



9.ADB WIFI
使用wifi无线调试你的app，无需root权限
也可参考以下文章：
Android wifi无线调试App新玩法ADB WIFI



10.AndroidPixelDimenGenerator
Android Studio自动生成dimen.xml文件插件



11.JsonOnlineViewer
在Android Studio中请求、调试接口



12.Android Styler
根据xml自动生成style代码的插件





Usage:
a. copy lines with future style from your layout.xml file
b. paste it to styles.xml file with Ctrl+Shift+D (or context menu)
c. enter name of new style in the modal window
d. your style is prepared!

13.Android Drawable Importer
这是一个非常强大的图片导入插件。它导入Android图标与Material图标的Drawable ，批量导入Drawable ，多源导入Drawable（即导入某张图片各种dpi对应的图片）










14.SelectorChapek for Android
通过资源文件命名自动生成Selector文件。





15.GenerateSerialVersionUID
实现Serializable序列化bean

Adds a new action ‘SerialVersionUID’ in the generate menu (alt + ins). The action adds an serialVersionUID field in the current class or updates it if it already exists, and assigns it the same value the standard ‘serialver’ JDK tool would return. The action is only visible when IDEA is not rebuilding its indexes, the class is serializable and either no serialVersionUID field exists or its value is different from the one the ‘serialver’ tool would return.

16.genymotion
速度较快的android模拟器



17.SQLScout
在 Android Studio 上调试数据库 ( SQLite )

详细使用参考：在 Android Studio 上调试数据库 ( SQLite )



18.Android Postfix Completion
可根据后缀快速完成代码，这个属于拓展吧，系统已经有这些功能，如sout、notnull等，这个插件在原有的基础上增添了一些新的功能，我更想做的是通过原作者的代码自己定制功能，那就更爽了



19.Android Holo Colors Generator
通过自定义Holo主题颜色生成对应的Drawable和布局文件



20.dagger-intellij-plugin
dagger可视化辅助工具



21.GradleDependenciesHelperPlugin
maven gradle 依赖支持自动补全



22.RemoveButterKnife
ButterKnife这个第三方库每次更新之后，绑定view的注解都会改变，从bind,到inject，再到bindview，搞得很多人都不敢升级，一旦升级，就会有巨量的代码需要手动修改，非常痛苦
当我们有一些非常棒的代码需要拿到其他项目使用，但是我们发现，那个项目对第三方库的使用是有限制的，我们不能使用butterknife，这时候，我们又得从注解改回findviewbyid
针对上面的两种情况，如果view比较少还好说，如果有几十个view，那么我们一个个的手动删除注解，写findviewbyid语句，简直是一场噩梦（别问我为什么知道这是噩梦）
所以，这种有规律又重复简单的工作为什么不能用一个插件来实现呢？于是RemoveButterKnife的想法就出现了。

具体介绍



23.AndroidProguardPlugin
一键生成项目混淆代码插件，值得你安装~(不过目前可能有些第三方项目的混淆还未添加完全)



24.otto-intellij-plugin
otto事件导航工具。




25.eventbus-intellij-plugin
eventbus导航插件(对于最新版的 EventBus 3.0.0 好像无效,请替换为eventbus3-intellij-plugin此插件地址在本文第51个)



26.idea-markdown
markdown插件



27.Sexy Editor
设置AS代码编辑区的背景图

首先点击界面的设置按钮 进入设置界面，选中Plugins,右边选择 Browser … ，输入Sexy … 下面自动弹出候选插件，右边点击Install 安装

安装成功 后需要重启AS

重启完成之后 进入设置界面 选择other Setting 下的Sexy Editor ， 右侧 insert 一张或多张图片即可，上面的其他设置可以设置方位 间隔时间 透明度等等，设置完成后，要关闭打开的文件，重新打开项目文件即可在代码编辑区显示插入的图片，作为代码编辑区的背景图。


28.folding-plugin
布局文件分组的插件



29.Android-DPI-Calculator
DPI计算插件



使用：

或者


30.gradle-retrolambda
在java 6 7中使用 lambda表达式插件

修改编译的jdk为java8:


31.Android Studio Prettify
可以将代码中的字符串写在string.xml文件中

选中字符串鼠标右键选择图中所示


这个插件还可以自动书写findViewById










32.Material Theme UI
添加Material主题到你的AS







33..ignore
我们都知道在Git 中想要过滤掉一些不想提交的文件，可以把相应的文件添加到.gitignore 中，而.gitignore 这个Android Studio 插件根据不同的语言来选择模板，就不用自己在费事添加一些文件了，而且还有自动补全功能，过滤文件再也不要复制文件名了。我们做项目的时候，并不是所有文件都是要提交的，比如构建的build 文件夹，本地配置文件，每个Module 生成的iml 文件，但是我们每次add，commit 都会不小心把它们添加上去，而gitignore 就是解决这种痛点的，如果你不想提交的文件，就可以在创建项目的时候将这个文件中添加即可，将一些通用的东西屏蔽掉。







34.CheckStyle-IDEA
CheckStyle-IDEA 是一个检查代码风格的插件，比如像命名约定，Javadoc，类设计等方面进行代码规范和风格的检查，你们可以遵从像Google Oracle 的Java 代码指南 ，当然也可以按照自己的规则来设置配置文件，从而有效约束你自己更好地遵循代码编写规范。

35.Markdown Navigator
github:Markdown Navigator
Markdown插件



36.ECTranslation
Android Studio Plugin,Translate English to Chinese. Android Studio 翻译插件,可以将英文翻译为中文。



37.PermissionsDispatcher plugin
github:PermissionsDispatcher plugin
自动生成6.0权限的代码



38.WakaTime
github:WakaTime
记录你在IDE上的工作时间



39.AndroidWiFiADB
无线调试应用





40.AndroidLocalizationer
可用于将项目中的 string 资源自动翻译为其他语言的 Android Studio/IntelliJ IDEA 插件





41.TranslationPlugin
又一翻译插件,可中英互译。





42.SingletonTest
快速生成单例模式的预设







43.BorePlugin
Android Studio 自动生成布局代码插件



代码生成规则
a.自动遍历目标布局中所有带id的文件, 无id的不会识别处理
b.控件生成的变量名默认为id名称, 可以在弹出确认框右侧的名称输入栏中自行修改
c.所有的Button或者带clickable=true的控件, 都会自动在代码中生成setOnClickListener相关代码
d.所有EditText控件, 都会在代码中生成非空判断代码, 如果为空会提示EditText的hint内容, 如果hint为空则提示xxx字符串不能为空字样, 最后会把所有输入框的验证合并到一个submit方法中
e.会自动识别布局中的include标签, 并读取对应布局中的控件

44.jimu Mirror
能够实时预览Android布局，它会监听布局文件的改动，如果有代码变化，就会立即刷新UI。

45.jRebel For Android
不仅能够做到UI布局的实时预览，它甚至做到了让你更改java代码后就能实时替换apk中的类文件，达到应用实时刷新，官网的介绍是：Skip build, install and run，因此它可以节约我们很多很多的时间，它的效果也十分不错。







46.sdk-manager-plugin
SDK管理插件，自动检测更新并下载。(图片与插件无关哈)



47.Codota
搜索最好的Android代码。(Studio里面直接可以搜到此插件)

48.LayoutFormatter
drakeet 开发一个一键格式化你的 XML 文件的 Android Studio 插件，至于为什么不用 Android Studio 自带的格式化功能而用这个插件，可以看下作者的一篇 Blog -> 当我们谈 XML 布局文件代码的优雅性



49.android-strings-search-plugin
一个可以通过输入文字找到strings.xml资源的插件



50.ideaVim
vim 本身就是一款很优秀的文本编辑器，而Android Studio 更是一款编写APP应用的神器。如果两个款优秀的软件结合在一起感觉会怎样呢？
详细请看文章:Android Studio ＋Vim



51.eventbus3-intellij-plugin
引导 EventBus 的 post 和 event(对于最新版的 EventBus 3.0.0 有效)
主要Bug修复工作：
修改包名和方法名以适应 EventBus 3.X
替换一个在新版的 intellij plugin SDK 已经不存在的类
增加若干 try-catch ，防止插件崩溃



52.Exynap
Exynap 一个帮助开发者自动生成样板代码的 AndroidStudio 插件



53.gradle-cleaner-intellij-plugin
Force clear delaying & no longer needed Gradle tasks.



54.MVPHelper
一款Intellj IDEA 和Android Studio的插件，可以为MVP生成接口以及实现类，解放双手。
具体请查看Android Studio插件之MVPHelper，一键生成MVP代码一文



55.Matchmaker
这是一款专为微信小程序开发的插件，目前可在 IntelliJ IDEA 中使用。它可以帮你完成重复机械无趣麻烦的绑定方法的过程，自动的将需要新建的方法注入到 js 文件中去。



56.Emoji Support Plugin
让 Intellij 支持 Emoji 输入提醒



57.Open-Uploader
上传apk文件到指定的地址，提供自定义参数



58.MultiTypeTemplates
生成MultiType和itemviewprovider(关于MultiType请查看Android 复杂的列表视图新写法 MultiType)





59.Android-ButterKnife-Plugin-Plus
Android Studio 的插件，方便快速实现ButterKnife注解框架，包含了android-butterknife-zelezny 1.6版本的所有功能，并在此基础上新增如下功能：

1.可以自由选择是否在当前类中对ButterKnife进行初始化，避免了原版本只要使用插件初始化控件会自动在onCreate中进行ButterKnife.bind(this)的尴尬。



这样就可以在基类中进行ButterKnife的初始化，不必要每个类中都要初始化，对开发框架的搭建更加方便。

2.在Android Studio的设置界面，对在当前类中是否强制初始化提供了默认值设置，这样就可以让插件使用更符合自己的操作习惯。



60. ApkMultiChannelPlugin
这是一个为了方便 Android 多渠道打包的 Android Studio / IDEA 插件

安装:

打开 Android Studio: 打开 Setting/Preferences -> Plugins -> Browse repositories 然后搜索 ApkMultiChannel 安装重启
或者

下载 ApkMultiChannelPlugin.jar 然后 Setting/Preferences -> Plugins -> Install plugin from disk 选择 ApkMultiChannelPlugin.jar 安装重启
使用方式:

选择 apk

选择一个 apk 然后右键，点击 Build MultiChannel


配置

配置签名信息，打包方式和渠道等


配置说明：

Key Store Path: 签名文件的路径

Key Store Password: 签名文件的密码

Key Alias: 密钥别名

Key Password: 密钥密码

Zipalign Path: zipalign文件的路径（用于优化 apk；zipalign 可以确保所有未压缩的数据均是以相对于文件开始部分的特定字节对齐开始，这样可减少应用消耗的 RAM 量。）

Signer Version: 选择签名版本：apksigner 和 jarsigner

Build Type: 打包方式

Channels: 渠道列表，每行一个，最前面可加 > 或不加（保存信息的时候，程序会自行加上）

开始打包

配置完成之后按 OK 就会开始进行渠道打包，文件会输出在选中的apk的当前目录下的channels目录中


61.CodeMaker
一个 IDEA 的代码生成插件，通过 Velocity 支持自定义代码模板来生成代码。详细介绍IDEA代码生成插件CodeMaker



62.adb-idea
可以一键清理缓存并重启APP



此插件来自zhoutianling@ltbl.cn的分享，感谢zhoutianling@ltbl.cn的分享

63.JVM Debugger Memory View
Android Studio和IDEA中一个很有用的内存调试插件

详细可参考说一说Android Studio和IDEA中一个很有用的内存调试插件一文。



64.TinyPic
功能：压缩图片资源，一次最多压缩500张 压缩的核心功能是TinyPng这个网站提供的

https://tinypng.com/

但是这个网站一次只能上传20张图片，所以你需要上传下载，上传下载重复工作。 好在这个网站提供了api可以压缩图片。

在开发者页面下申请api key。对于一个key，每月有500次的免费压缩额度，如果压缩超过了 500张图片，就不能使用了。需要另外付费。但是申请这个api特别简单，填下邮箱，用户名就行，多申请 两个邮箱。1000张图片也妥妥够了。 这里推荐google个十分钟邮箱，不需要注册，只能使用十分钟，用来收一下验证码很方便。

使用方式：
1.在File->Settings->Plugins里下载插件 TinyPic

2.安装完后重启，在Tools目录下找到TinyPic



3.输入在 https://tinypng.com/developers 申请的api key



4.选择图片，可以选择图片，或者选择文件夹或者同时选中，反正是遍历文件夹下的图片，筛选jpg和png ，key的剩余次数



5.压缩进度


6.超过500次的提示（后续会考虑加入 生成压缩的信息的文件，因为大家都用git，其实也不是很必要）



65.ReciteWords
这是一个androidStudio翻译与陌生单词记录插件



你所翻译的单词会被记录在你当前用户目录下的ReciteWords.md文件中（如:C:\Users\Bolex\ReciteWords.md）。可以通过Markdown编辑器打开它进行学习。效果如下:


66.TemplateBuilder
TemplateBuilder是一款能够帮助我们快速生成Android Studio Template的AS插件，将通过逐个文件去配置模板的方式改进为通过插件来实现，对于简单的模板制作，只需要一键即可生成。



具体使用请参考TemplateBuilder(中文版)](TemplateBuilder

67.intellij-java2smali
将Java & Kotlin编译成smali



68.innerbuilder
InnerBuilder 一款Intellj IDEA 和Android Studio自动生成内部类Builder代码的插件。



69.Statistic
统计代码行数



使用可参考:Android studio插件Statistic的使用

70.create-intent-inspection
创建intent



71.color-manager
颜色管理



72.new-instance-inspection
创建fragment实例



73.Exynap
exynap是一个可以帮助你查找并实现您需要的代码的插件



74.databinding-support
一个可以快速实现databinding的插件



75.pomodoro-tm
番茄工作法的 Android Studio / IDEA 插件



76.freeline
Freeline 是 Android 平台上的秒级编译方案，Instant Run 的替代品



77.svgtoandroid
Intellij Platform插件，通过其可以完成从svg文件到Android VectorDrawable的自动化转换



78.instapk-studio-plugin
分享apk文件



79.here-be-dragons
加上@SideEffect注解的方法,在调用的地方会出现一只鸟



80.android-studio-proteus-plugin
将xml转化为json
