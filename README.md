<img src="https://s3.ax1x.com/2021/01/27/szmFC6.png" alt="lee_con_logo" height=150>

# iOSObfuscator - 代码混淆加固大幅提高AppStore过审率

<img src="https://img.shields.io/badge/platform-ios%7Cmac%7CEgret%7Ccocos2dx%2BLua-orange" alt="platform">&emsp;<img src="https://img.shields.io/badge/version-v1.2.0-ff69b4" alt="version">

混淆器 `iOSObfuscator` 是集合了<b>代码混淆、一键打包提审、审核监控、内跳SDK 和 常用开发提审工具集</b> 五个模块构建出来的 Mac 软件。<br><br>

**相关链接：**

Mac 软件下载地址:[https://github.com/lee-617/Obfuscator](https://github.com/lee-617/Obfuscator)<br />
官方文档-使用说明:[http://118.31.36.105/docs/index.html](http://118.31.36.105/docs/index.html)<br />

> 软件并非开源，如有混淆需求、马甲包开发、TF签名等需求，请联系在线详谈QQ:2480619280

-------

**软件截图：**

<img src="http://118.31.36.105/docs/src_pics/group.png" alt="szKOo9.png" border="0" />

**围绕提审 AppStore 应用市场，本软件专门针对以下需求：**

- 因为工程代码重复问题，提交 AppStore 被驳回4.3，无论如何修改再过审很困难；
- 希望一个工程能够经混淆之后多次提交 AppStore，重复利用，节省开发时间和成本；
- 工程写完之后，证书签名打包编辑元数据进行提审步骤繁琐耗时，希望能一键打包快速提审；
- app 提交审核之后，希望随时能够快速查看到 app 的审核状态；
- 马甲包开发中内置跳转功能部分审核严格，加跳转之后一般会导致会被2.3驳回或账号被调查等；

**软件功能概览：**

- 项目工程翻新：工程项目文件及文件夹名修改、代码混淆、资源翻新、注入具有强调用关系的代码、删除注释和log、三十九种分类词库选择等；
- 一键打包提审：iOS 自动化部署发布，处理所有繁琐的提审流程，做到让你的工作实现并发；
- app 审核状态监控：一次登录，快速查看提交 app 的审核状态，并生成提交记录和汇总统计；
- 内跳 SDK：满足马甲包跳转这一核心需求，经过加密稳定可靠的SDK。内跳 SDK已经过内部超过 300+ 个马甲包的测试，除账号问题外，安全率极高；

**软件细节展示：**
<img src="https://s3.ax1x.com/2021/01/27/szQAnU.png" alt="d_options" />

<font color=blue>混淆前后展示：</font>

<img src="https://s3.ax1x.com/2021/01/27/szQSts.png" alt="sz_add_m" />
<img src="https://s3.ax1x.com/2021/01/27/szMCLD.png" alt="szMCLD.png" border="0" />

**混淆日志：**

<img src="https://s3.ax1x.com/2021/01/27/szQW3q.png" alt="log_ins" />


**为了提升开发效率，我们在混淆软件中预置了十一种常用的开发工具以供使用：**

|功能列表|功能描述|
|--|--|
|**[1.AppIcon 快速替换](#9_1_developing_tool_1)**|一键替换工程中的AppIcon，支持本地替换和从iconfont下载替换<br><font color=gray size=4>注：iconfont 是阿里提供的一个icon资源下载的站点，登录之后即可免费下载使用</font>|
|**[2.工程 icon 快速替换](#9_1_developing_tool_2)**|一键替换工程中icon，支持本地替换和从iconfont下载替换|
|**[3.更改 icon 背景颜色和尺寸](#9_1_developing_tool_3)**|为选中的icon，一键生成背景颜色并改变其尺寸|
|**[4.ipa重签名工具](#9_1_developing_tool_4)**|对ipa包进行重签名|
|**[5.描述文件管理器](#9_1_developing_tool_5)**|管理你所有的描述文件：查看、删除和导出 provisioning profile|
|**[6.项目本地化工具](#9_1_developing_tool_6)**|读取所有语言的.strings，直接添加条目进行本地化，或一键完成本地化|
|**[7.Json转Model类](#9_1_developing_tool_7)**|复制或导入json，一键转为 OC 的 Model 类代码，支持json校验和json的格式化|
|**[8.xib文件转oc代码](#9_1_developing_tool_8)**|一键将xib文件解析为oc纯代码视图创建的方式|
|**[9.色值小工具](#9_1_developing_tool_9)**|RGB和Hex十六进制互转|
|**[10.字符串和文档翻译工具](#9_1_developing_tool_10)**|为方便开发查询和本地化处理，随时进行字符串的翻译|
|**[11.一键提取Assets中的资源图片](#9_1_developing_tool_11)**|导入任意的后缀的.car、.app、.ipa即可导出其中所有的资源文件|
<br>
<a-alert type="warning" showIcon>
    <span slot="message">
        <!-- <font color="53C519"> -->
            <b>我们的开发工具还正在维护持续开发中，若使用过程中有任何意见或发现bug请通过issue反馈给我们,我们会及时修复定时更新。<br>issue提交地址：<a href="https://github.com/obfuscator/issue/">https://github.com/obfuscator/issue/</a></b>
        <!-- </font> -->
    </span>
</a-alert>
<br>

**以下是各个功能的详细介绍：**
<span id="9_1_developing_tool_1"></span><br>
## 1. App logo 快速替换

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/appicon_op_1.png" width="1000px"></span>

现在你可以直接使用该工具一键替换 app 中的 AppIcon 图标了。

支持两种替换：

**<font color="#EC542D" size=3>1.1 本地导入新 AppIcon 图片进行替换</font>**

选择 “本地图片快速替换”，直接导入新logo，并选择要支持生成的设备，即可一键生成满足要求的各个设备（`iPhone` `iPad`）尺寸的 AppIcon。

如果 icon 的背景透明，你还可以最后更改 AppIcon 的背景颜色。

> 注：因提交到 ITC 上的 logo 必须关闭 Alpha 通道，工具已自动为你选择的 icon 做了此操作。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/appicon_op_2.png" width="1000px"></span>

**<font color="#EC542D" size=3>1.2 从iconfont网站下载图片进行替换</font>**

如果您希望从网上找一张图片作为 AppIcon 的话，此方式则内置了 iconfont（一个免费下载各种图标资源的网站），你只需要在打开的网站列表中选择一张 icon，然后点击&emsp;<img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/appicon_op_4.png" width="44px" height="50px">&emsp;下载按钮，在如下 icon 的详情卡片中，选择颜色和尺寸，点击 `PNG 下载` 即可一键下载并替换工程中的 AppIcon 了。

> 注：iconfont 网站是需要登录之后才能免费下载资源，请使用推荐的登录方式登录此网站

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/appicon_op_3.png" width="1000px"></span>


<span id="9_1_developing_tool_2"></span><br>
## 2. 工程 icon 快速替换

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/icon_op_1.png" width="1000px"></span>

该工具提供对整体工程中 Assets 目录下的某些或全部 icon 资源进行一键替换的便利操作。

导入工程的根目录 之后，软件将会自动导入工程目录下所有 icon 资源，如上图你将看到所有图片资源的列表。
点击你希望替换的icon，即进入 iconfont 网站（一个免费下载各种图标资源的网站），只需要在打开的网站列表中点击下载按钮即可实现 icon 的替换操作。

> 提示：
> icon 替换也是从 iconfont 网站下载，需要登录
> 
> 1.若您的一个icon中含有@1x或@2x或@3x等多个尺寸的，下载替换的时候会默认生成对应的文件；
> 
> 2.新 icon 资源名不会改变；
> 
> 3.旧 icon 资源将会被覆盖；

<span id="9_1_developing_tool_3"></span><br>
## 3. 更改 icon 背景色和尺寸

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/icon2_op_1.png" width="1000px"></span>

该功能允许你直接对工程中某些或所有 icon 资源进行调整，主要包括 `更改图片背景颜色` 和 `调整尺寸`。

使用说明：
1. 点击右上角进行配置，可直接设置背景色和尺寸大小，然后保存配置即可。
2. 在 icon 的列表中点击某个图片即会对该图片按照配置的进行更改到本地。

同时，在配置的时候，支持 **一键调整所有资源的背景色** 和 **一键调整所有资源的尺寸**。

> 注：
> 调整 icon 的背景颜色，目前仅支持初始无背景色的 icon，所以若一键更改的话，部分已有背景色的 icon 不会被更改。

<span id="9_1_developing_tool_4"></span><br>
## 4. ipa 重签名工具

iOS 通常打包时，需要证书和配置文件进行签名，对于逆向的朋友有可能需要对一个 ipa 进行重签名操作，这个工具提供了界面化操作，只要将需要换签的 ipa 文件导入，选择新的证书和配置文件即可一键替换 ipa 包中的签名文件。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/resign_op_1.png" width="1000px"></span>

<span id="9_1_developing_tool_5"></span><br>
## 5. profile 描述文件管理

这里罗列了本机 Mac 中所有由你创建和Xcode自动生成的配置文件，目前仅支持查看、删除等基本操作，后续我们会根据需求逐步完善对描述文件的管理。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/profile_op_1.png" width="1000px"></span>


<span id="9_1_developing_tool_6"></span><br>
## 6. 翻译工具

在开发学习中，翻译工具是必备的，为了不脱离开发环境，我们内置了翻译工具支持30多国家的语言，方便多语言开发或文档一键翻译。

文本的翻译如下：

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/trans_op_1.png" width="1000px"></span>

除此之外，在右上角功能按键中，我们支持一键对导入的文档进行翻译并导出，支持导入的文件类型有：`.doc`、`.docx`、`.txt`、`.plist`（<font color=red>其中plist文件已经过解析，会忽略key而只翻译其key对应的值</font>），文档翻译区域如下：

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/trans_op_2.png" width="1000px"></span>

使用步骤：
1. 导入已支持类型的源文件：.doc或.docx或.txt或.plist；
2. ☑️勾选需要翻译的目标语言，可多选国家语言；
3. 设置导出的目标路径，并开启一键翻译；

> 根据源文件内容量大小和勾选目标语言的数量，翻译可能需要一定的时间等待，请耐心等待完成。


<span id="9_1_developing_tool_7"></span><br>
## 7. JSON 转 Model 代码

Json 是开发中最常见到的数据结构，在 iOS 开发中，无论是MVC、MVVM、MVCS架构的工程，获取到 Json 之后都需要将其转为我们便于访问和操作的模型类 Model，为了方便校验、格式化 Json、快速的生成与 Json 一一对应的属性键和准确嵌套模型类的层级，工具箱中加入了可视化的 Json 转 OC 模型类代码的小工功能，希望能节省你的开发时间。

你现在可以：
1. 拷贝一段 Json 数据（或从本地导入 json 文件），自动生成对应的 OC 模型类代码；

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/jm_local_1.png" width="1000px"></span>

2. 支持 get 和 post 配置请求参数，发起请求后，直接在右边生成 Model 类代码；

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/jm_requ_2.png" width="1000px"></span>
<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/jm_requ_1.png" width="1000px"></span>


<span id="9_1_developing_tool_8"></span><br>
## 8. xib 文件一键生成 oc 纯代码

iOS 开发中，一般有两种编写代码的方式：通过xib布局 或 纯代码，前者本质是使用 xml 标记了视图对象的各个属性和彼此间的层级关系。对于马甲包开发中，为了应对代码重复，使用xib和纯代码布局导致的是两份不重复的代码。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/xibtocode_op_1.png" width="1000px"></span>

如图，这个工具能够罗列工程中所有的 `xib` 视图布局文件，通过解析其中的对象和层级关系，准确地将可视化的 `xib` 转为纯代码文本，目前支持输出 frame 的布局，尚不支持输出 Autolayout 约束代码。


<span id="9_1_developing_tool_9"></span><br>
## 9. 色值小工具

这是一个简单的可视化色值转换工具：
1. 支持 `RGB` 和 `Hex十六进制` 色值的相互转换；
2. 支持颜色板取色获取 RGB、Hex、CMYK值。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/colorT_op_1.png" width="1000px"></span>



<span id="9_1_developing_tool_10"></span><br>
## 10. 本地化

在提交马甲包的过程中，经常要设置多语言，为了更稳当地通过审核，开发者应该尽可能做好工程中本地化部分的处理，通过添加支持的语言选项、对每个语言文件.strings添加翻译之后的key-value，若有xib布局的界面也需要处理各个语言文件中的字符串。

现在我们尝试将工程中涉及本地化的文件：Localizable.strings InfoPlist.strings xxxxib.strings 等摘出来，集中处理这几个文件对应的多语言的本地化，如下图，导入工程根目录之后，会罗列对应工程中所有需要本地化的系统文件（其中添加语言、添加各个语言的.strings你应该首先都创建好），然后你可以选择在工作区新增、删除、修改某个条目，亦可以单独管理某个条目中某些语言下的值。

只需要点击某条目最右边的本地化按钮，即可完成所有已勾选的语言的翻译工作，你也可以直接点击一键本地化处理，这将会直接根据主语言的key-value，自动翻译为所有目标语言的key-value对。

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/localize_op_1.png" width="1000px"></span>

添加一个新的key：

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/localize_op_2.png" width="1000px"></span>

对一个条目进行所有语言的翻译处理：

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/localize_op_3.png" width="1000px"></span>

<span id="9_1_developing_tool_11"></span><br>
## 11. 一键提取Assets.car/.app/.ipa中的资源图片

<span><img src="http://118.31.36.105/docs/src_pics/9_1_tools_src/assets_op_1.png" width="1000px"></span>

独立开发者在开发过程中经常需要各种素材资源，为此我们加入了提取 Assets.car/.app/.ipa 中资源的功能，从中可以提取出优秀的icon设计用以作为设计参考之用。

只需要下载一个格式为 `.car` `.app` `.ipa` 的包即可拖入左边的区域，再设置目标导出的路径，点击转换按钮即可实现资源提取。


<a-divider />
<div class="mobile-adapt">工具箱中其余开发工具正在开发补充中，即将更新上线...</div> 



## 更新日志

软件正在努力维护测试中，当前版本已修复之前版本的各种问题。<br/><br/>

<template>
    <a-timeline mode="left">
        <a-timeline-item>
            <b>当前线上版本 - v1.2.0</b>
            <a-tag color="red">正式版</a-tag>
            <p></p>
            <p>
                &emsp;当前版本存在以下『已知问题』，请注意：
                <br /><p></p>
                ld: framework not found XXX.framework framework路径改变；<br/>
                pch文件位于工程根目录下，导致import的文件名未被修改；<br/>
                若对象创建时指向的是子类对象，在注入的时候可能导致调用到子类注入的方法而抛出异常；<br/><br/>
                &emsp;<font color=gray><b>针对已知问题，若出现，请参考《常见问题 FAQ》手动进行修复</b></font>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.9
            <p>
                优化查找替换属性和方法的逻辑；<br/>
                优化写入文件之前的存储逻辑；<br/>
                资源文件以及Assets和AppIcon图片优化；<br/>
                优化代码缩进和注入代码格式；<br/>
                调整ui交互；<br/>
                优化状态栏ui交互；<br/>
                优化白名单引用；<br/>
                修复非法混淆词、关键字、标识符引起的问题；<br/>
                修复工程目录引用错误的问题；<br/>
                修复程序运行假死的问题；<br/>
                修复资源修改时的逻辑漏洞；<br/>
                修复崩溃问题, 修复pch和info.plist文件路径引入错误的问题, 调整扩展文件名称创建逻辑；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.8
            <p>
                新增文件头注释替换；<br/>
                新增目录名和文件名替换；<br/>
                新增文件通配后缀过滤；<br/>
                新增混淆日志导出；<br/>
                添加快捷键；<br/>
                修复plist文件为空的bug；<br/>
                修复白名单子目录和非白名单子目录中含同名被同步修改的问题；<br/>
                修复实际目录和工程中的目录引用不同步的问题；<br/>
                修复通过点语法访问setter和getter但未声明属性，从而setter被替换错误的bug；<br/>
                修复截取一个文件多个类时发生的错误；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.7
            <p>
                添加属性限定符、修饰语义符的安全过滤；<br/>
                支持软件快捷键组合；<br/>
                新增四十个混淆分类词库；<br/>
                新增注释和NSLog删除；<br/>
                兼容LaunchScreen文件内容被替换的bug；<br/>
                修复font资源加载不了的bug；<br/>
                修复其他可能存在问题的bug；<br/>
                修复工程中 info.plist 引入路径的错误；<br/>
                变更目录路径crash；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.6
            <p>
                添加属性名混淆、方法名混淆；<br/>
                添加系统api和常见三方sdk方法签名的安全过滤；<br/>
                修复工程配置选项缓存的问题；<br/>
                修复资源文件引入错误的问题；<br/>
                修复注入的资源文件未被正确生成的问题；<br/>
                修复main函数被替换的问题；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.5
            <p>
                修改log输出逻辑错误的问题；<br/>
                修复自定义bundle下资源获取不到的bug；<br/>
                修复api修改导致属性变化, 属性修改导致api变化的bug；<br/>
                修复getter方法内部实例变量ivar没有同步被更换的bug；<br/>
                修复系统方法被自定义重写之后导致被替换的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.4
            <p>
                优化代码块、行内代码等显示效果；<br/>
                新增工程目录变更白名单重置弹窗提示；<br/>
                修复一个文件中多个类定义和实现，插入methods和properties的位置有误的bug；<br/>
                修复了 Model 模型类中的属性在被调用时被修改的问题；<br/>
                修复了setter方法被子类重写之后被修改了出错的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.0
            <p>
                添加注入调用关系功能；<br/>
                添加资源hash值更改；<br/>
                修复import的分类名和实际category的文件名不一致的问题；<br/>
                修复protocol中方法声明部分只替换一部分的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.0.2
            <p>
                优化log输出；<br/>
                新增terminal,终端打开当前工程目录的窗口；<br/>
                新增打开工程选项；<br/>
                新增打开工程的Finder目录选项；<br/>
                修复工程中插注入方法引用资源错误的问题；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v0.0.1
            <p>
                添加对OC代码的混淆功能；<br/>
            </p>
        </a-timeline-item>
    </a-timeline>
</template>
