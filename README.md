<img src="https://s3.ax1x.com/2021/01/27/szmFC6.png" alt="lee_con_logo" height=150>

# iOSObfuscator - 代码混淆加固大幅提高AppStore过审率

<img src="https://img.shields.io/badge/platform-ios%7Cmac%7CEgret%7Ccocos2dx%2BLua-orange" alt="platform">

混淆器 `iOSObfuscator` 是集合了<b>代码混淆、一键打包提审、审核监控、内跳SDK 和 常用开发提审工具集</b> 五个模块构建出来的 Mac 软件。<br><br>

**相关连接：**

Mac 软件下载地址:[https://github.com/lee-617/Obfuscator](https://github.com/lee-617/Obfuscator)<br />
官网地址:[http://118.31.36.105/index.html](http://118.31.36.105/index.html)<br />
官方文档-使用说明:[http://118.31.36.105/docs/index.html](http://118.31.36.105/docs/index.html)<br />

软件并非开源，如有混淆需求、马甲包开发、TF签名等需求，请联系我在线详谈QQ:2480619280

-------

**软件截图：**

<img src="https://s3.ax1x.com/2021/01/27/szKOo9.png" alt="szKOo9.png" border="0" />

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
                &emsp;- <a-tag color="blue">『已知问题』</a-tag>ld: framework not found XXX.framework framework路径改变；<br/>
                &emsp;- <a-tag color="blue">『已知问题』</a-tag>pch文件位于工程根目录下，导致import的文件名未被修改；<br/>
                &emsp;- <a-tag color="blue">『已知问题』</a-tag>若对象创建时指向的是子类对象，在注入的时候可能导致调用到子类注入的方法而抛出异常；<br/><br/>
                &emsp;<font color=gray><b>针对已知问题，若出现，请参考《常见问题 FAQ》手动进行修复</b></font>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.9
            <p>
                &emsp;- <a-tag color="green">优化</a-tag>优化查找替换属性和方法的逻辑；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>优化写入文件之前的存储逻辑；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>资源文件以及Assets和AppIcon图片优化；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>优化代码缩进和注入代码格式；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>调整ui交互；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>优化状态栏ui交互；<br/>
                &emsp;- <a-tag color="green">优化</a-tag>优化白名单引用；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复非法混淆词、关键字、标识符引起的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复工程目录引用错误的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复程序运行假死的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复资源修改时的逻辑漏洞；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复崩溃问题, 修复pch和info.plist文件路径引入错误的问题, 调整扩展文件名称创建逻辑；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.8
            <p>
                &emsp;- <a-tag color="orange">新增</a-tag>新增文件头注释替换；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增目录名和文件名替换；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增文件通配后缀过滤；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增混淆日志导出；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>添加快捷键；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复plist文件为空的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复白名单子目录和非白名单子目录中含同名被同步修改的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复实际目录和工程中的目录引用不同步的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复通过点语法访问setter和getter但未声明属性，从而setter被替换错误的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复截取一个文件多个类时发生的错误；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.7
            <p>
                &emsp;- <a-tag color="orange">新增</a-tag>添加属性限定符、修饰语义符的安全过滤；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>支持软件快捷键组合；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增四十个混淆分类词库；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增注释和NSLog删除；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>兼容LaunchScreen文件内容被替换的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复font资源加载不了的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复其他可能存在问题的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复工程中 info.plist 引入路径的错误；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>变更目录路径crash；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.6
            <p>
                &emsp;- <a-tag color="orange">新增</a-tag>添加属性名混淆、方法名混淆；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>添加系统api和常见三方sdk方法签名的安全过滤；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复工程配置选项缓存的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复资源文件引入错误的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复注入的资源文件未被正确生成的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复main函数被替换的问题；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.5
            <p>
                &emsp;- <a-tag color="purple">修复</a-tag>修改log输出逻辑错误的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复自定义bundle下资源获取不到的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复api修改导致属性变化, 属性修改导致api变化的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复getter方法内部实例变量ivar没有同步被更换的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复系统方法被自定义重写之后导致被替换的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.4
            <p>
                &emsp;- <a-tag color="green">优化</a-tag>优化代码块、行内代码等显示效果；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增工程目录变更白名单重置弹窗提示；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复一个文件中多个类定义和实现，插入methods和properties的位置有误的bug；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复了 Model 模型类中的属性在被调用时被修改的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复了setter方法被子类重写之后被修改了出错的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.1.0
            <p>
                &emsp;- <a-tag color="orange">新增</a-tag>添加注入调用关系功能；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>添加资源hash值更改；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复import的分类名和实际category的文件名不一致的问题；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复protocol中方法声明部分只替换一部分的bug；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v1.0.2
            <p>
                &emsp;- <a-tag color="green">优化</a-tag>优化log输出；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增terminal,终端打开当前工程目录的窗口；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增打开工程选项；<br/>
                &emsp;- <a-tag color="orange">新增</a-tag>新增打开工程的Finder目录选项；<br/>
                &emsp;- <a-tag color="purple">修复</a-tag>修复工程中插注入方法引用资源错误的问题；<br/>
            </p>
        </a-timeline-item>
        <a-timeline-item>
            v0.0.1
            <p>
                &emsp;- <a-tag color="orange">新增</a-tag>添加对OC代码的混淆功能；<br/>
            </p>
        </a-timeline-item>
    </a-timeline>
</template>
