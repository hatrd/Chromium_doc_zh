# zh

## Chromium\_doc\_zh

Chromium中文文档 for

https://www.chromium.org/developers/design-documents

翻译之加强对android webview理解

## 设计文档

* [Start Here: 背景阅读](Start\_Here\_Background\_Reading/): 描述Chromium的宏观架构
  *   [多进程架构](Start\_Here\_Background\_Reading/Multi-process\_Architecture.md)

      **Note**: 设计文档的大部分剩余部分都认为你对上面这个文档里的内容非常熟悉。
  * [Chromium如何展示web界面](Start\_Here\_Background\_Reading/How\_Chromium\_Displays\_Web\_Pages.md): 自底向上概述WebKit是如何嵌入到Chromium中的

### See Also: 源代码中的设计文档

```
https://chromium.googlesource.com/chromium/src/+/master/docs/
```

* \###[整体架构](General\_Architecture/)
  * [跨平台开发的约定与模式](General\_Architecture/Conventions\_and\_patterns\_for\_multi-platform\_development.md)
  * [扩展安全架构](General\_Architecture/Extension\_Security\_Architecture.md): 扩展系统是如何降低扩展脆弱性的严重程度的
  * [硬件视频加速](General\_Architecture/HW\_Video\_Acceleration\_in\_Chrom{eium}{OS}.md)
  * [跨进程通信](General\_Architecture/Inter-process\_Communication.md): 浏览进程，绘制器，插件进程是如何交流的
  * [多进程资源加载](General\_Architecture/Multi-process\_Resource\_Loading.md): 页面和图像是如何从网络加载到绘制器中的
  * [插件架构](General\_Architecture/Plugin\_Architecture.md)
  * [进程模型](General\_Architecture/Process\_Models.md): 创建新绘制进程的策略
  * [Profile架构](General\_Architecture/Profile\_Architecture.md)
  * [安全浏览](General\_Architecture/SafeBrowsing.md)
  * [沙箱](General\_Architecture/Sandbox.md)
    * [沙箱FAQ](General\_Architecture/Sandbox\_FAQ.md)
    * [OSX中的沙箱设计](General\_Architecture/OSX\_Sandbox\_design.md)
  * [安全架构](General\_Architecture/Security\_Architecture.md): Chromium沙箱绘制引擎是如何保护免受恶意软件侵害的
  * [启动](General\_Architecture/Startup.md)
  * [线程](General\_Architecture/Threading.md): 在chromium中如何使用线程

也可以看看 [V8](http://code.google.com/apis/v8/)的文档, 这是Chromium使用的Javascript引擎

* \###[UI Framework](Testing/Moving\_LayoutTests\_fully\_upstream.md)
  * [UI开发实践](UI\_Framework/NativeControls.md): 在Chrome的content区域内外开发的最佳实践
  * [Views framework](UI\_Framework/UI\_Development\_Practices.md): Windows和Chrome OS上使用的UI layout 层级
  * [views Windowing系统](UI\_Framework/Views\_framework.md): 如何用view构建对话框盒子和其他windowUI
  * [Aura](UI\_Framework/): Chrome下一代硬件加速UI框架，新的ChromeOS 系统由它构建而成
  * [Native控制](UI\_Framework/Aura.md): 在view中使用平台原生widget
  * 用View和Aura实现聚焦与激活
* \###[Graphics](Graphics/)
  * [概述](Graphics/Overview.md)
  * [Chrome中使用的GPU加速](Graphics/GPU\_Accelerated\_Compositing\_in\_Chrome.md)
  * [GPU特性状态仪表盘](Graphics/GPU\_Feature\_Status\_Dashboard.md)
  * [绘制架构图](Graphics/Rendering\_Architecture\_Diagrams.md)
  * [Graphics和Skia](Graphics/Graphics\_and\_Skia.md)
  * [绘制文本以及Chrome UI 文本绘制](Graphics/RenderText\_and\_Chrome\_UI\_text\_drawing.md)
  * [GPU命令缓冲区](Graphics/GPU\_Command\_Buffer.md)
  * [GPU程序缓冲区](Graphics/GPU\_Program\_Caching.md)
  * [Blink/WebCore中的组合](Graphics/Compositing\_in\_Blink\_WebCore.md)
  * [排版线程架构](Graphics/Compositor\_Thread\_Architecture.md)
  * [绘制标准](Graphics/Rendering\_Benchmarks.md)
  * [实现层绘制](Graphics/Impl-side\_Painting.md)
  * [视频回放与排版](Graphics/Video\_Playback\_and\_Compositor.md)
  * [ANGLE架构表示](Graphics/ANGLE\_architecture\_presentation.md)
* [网络栈](Network\_stack/)
  * [概述](Network\_stack/Overview.md)
  * [网络栈的目标](Network\_stack/Network\_Stack\_Objectives.md)
  * [Crypto](Network\_stack/Crypto.md)
  * [磁盘缓存](Network\_stack/Disk\_Cache.md)
  * [HTTP缓存](Network\_stack/HTTP\_Cache.md)
  * [进程外代理解决草案\[unimplemented\]](Network\_stack/Out\_of\_Process\_Proxy\_Resolving\_Draft\_\[unimplemented].md)
  * [代理设置与回退](Network\_stack/Proxy\_Settings\_and\_Fallback.md)
  * [调试网络代理问题](Network\_stack/Debugging\_network\_proxy\_problems.md)
  * [HTTP授权](Network\_stack/HTTP\_Authentication.md)
  * [查看网络内部情况的工具](Network\_stack/View\_network\_internals\_tool.md)
  * [用SPDY页面使得网络更快](Network\_stack/Make\_the\_web\_faster\_with\_SPDY\_pages.md)
  * [用OUIC页面使得网络更快](Network\_stack/\_the\_web\_even\_faster\_with\_QUIC\_pages.md)
  * [Cookie存储与获取](Network\_stack/Cookie\_storage\_and\_retrieval.md)
* [安全](Security/)
  * [概述](Security/Security\_Overview.md)
  * [保护缓存用户数据](Security/Protecting\_Cached\_User\_Data.md)
  * [系统强化](Security/System\_Hardening.md)
  * [Chaps技术设计](Security/Chaps\_Technical\_Design.md)
  * [TPM使用](Security/TPM\_Usage.md)
  * [每个页面的子源](Security/Per-page\_Suborigins.md)
  * [加密分割恢复](Security/Encrypted\_Partition\_Recovery.md)
* [Input](Input/)
  * 看这个文档[chromium input](Input/chromium\_input.md)（关于设计文档以及一些其他资源）
* [绘制](Rendering/)
  * [多列布局](Rendering/Multi-column\_layout.md)
  * [刷新时重置Style](Rendering/Style\_Invalidation\_in\_Blink.md)
  * [刷新与空间的协调](Rendering/Blink\_Coordinate\_Spaces.md)
* [构建](Building/)
  * [IDL构建](Building/IDL\_build.md)
  * [IDL编译器](Building/IDL\_compiler.md)
  * 也可以看这个文档，[GYP, the build script generation tool.](Building/GYP\_the\_build\_script\_generation\_tool..md)
* [测试](Start\_Here\_Background\_Reading/How\_Blink\_Works.md)
  * [Layout测试结果面板](Testing/Generic\_theme\_for\_Test\_Shell.md)
  * [Test shell中的真实主题](Testing/)
  * [完全回退移除layout测试](Testing/Layout\_test\_results\_dashboard.md)
* [特性相关](Feature-Specific/)
  * [关于冲突](Feature-Specific/aboutconflicts.md)
  * [可用性](Feature-Specific/Accessibility.md): 当前（以及将来）可用性支持的轮廓。
  * [自适应屏幕截图与镜像](Feature-Specific/Auto-Throttled\_Screen\_Capture\_and\_Mirroring.md)
  * [浏览器window](Feature-Specific/Browser\_Window.md)
  * [Chromium打印代理](Feature-Specific/Chromium\_Print\_Proxy.md): 为保留打印机与未来的云服务打印机使能云打印服务
  * [强制弹出窗口](Feature-Specific/Constrained\_Popup\_Windows.md)
  * [桌面通知](Feature-Specific/Desktop\_Notifications.md)
  * [Chrome on Windows的直写式Cache](Feature-Specific/DirectWrite\_Font\_Cache\_for\_Chrome\_on\_Windows.md)
  * [DNS预拉取](Feature-Specific/DNS\_Prefetching.md): 通过在用户打开链接前,预先解析域名,来减少延迟
  * [在浏览器窗口中,嵌入式Flash的全屏](Feature-Specific/Embedding\_Flash\_Fullscreen\_in\_the\_Browser\_Window.md)
  * [拓展: 设计文档与推荐的api ](Feature-Specific/Extensions\_Design\_documents\_and\_proposed\_APIs..md): Design documents and proposed APIs.
  * [查找栏](Feature-Specific/Find\_Bar.md)
  * [表单自动填充](Feature-Specific/Form\_Autofill.md): 用合适的数据自动填充一个html表单的特性
  * [地理信息](Feature-Specific/Geolocation.md): 添加对[W3C Geolocation API](http://www.w3.org/TR/geolocation-API/)的支持,使用native WebKit bindings.
  * [IDN in Google Chrome](Feature-Specific/IDN\_in\_Google\_Chrome.md)
  * [索引式DB(早期草稿)](Feature-Specific/IndexedDB\_\_early\_draft\_.md)
  * [信息栏](Feature-Specific/Info\_Bars.md)
  * [安装](Feature-Specific/Installer.md): 注册入口与快捷方式
  * [即时](Feature-Specific/Instant.md)
  * [独立网站](Feature-Specific/Isolated\_Sites.md)
  * [Linux资源与本地化字符串](Feature-Specific/Linux\_Resources\_and\_Localized\_Strings.md): Linux资源与本地化字符串的加载
  * [媒体路由 & Web Presentation API](Feature-Specific/Media\_Router\_&\_Web\_Presentation\_API.md)
  * [内存使用统计后端](Feature-Specific/Memory\_Usage\_Backgrounder.md): 我们在Chromium中如何测量内存的一些api
  * [鼠标锁定](Feature-Specific/Mouse\_Lock.md)
  * [地址栏自动完成](../en/OS-Specific/Mac\_OS\_X/Wrench\_Menu\_Buttons.md): 在地址栏中打字时,Chromium搜索并建议可能的结果
    * [快速提供历史](Feature-Specific/Omnibox\_Autocomplete/): 由用户历史访问网站提供建议
  * [搜索栏/IME协作](Feature-Specific/Omnibox\_IME\_Coordination.md)
  * [Ozone移植抽象](Feature-Specific/Ozone\_Porting\_Abstraction.md)
  * [密码生成](Feature-Specific/Password\_Generation.md)
  * [Pepper插件实现](Feature-Specific/Pepper\_plugin\_implementation.md)
  * [插件能力保存](Feature-Specific/Plugin\_Power\_Saver.md)
  * [选项](Feature-Specific/Preferences.md)
  * [预渲染](Feature-Specific/Prerender.md)
  * [打印预览](Feature-Specific/Print\_Preview.md)
  * [打印](Feature-Specific/Printing.md)
  * [view中基于矩形的事件目标](Feature-Specific/Rect-based\_event\_targeting\_in\_views.md): 使得触摸激发view元素更加容易
  * [替换语义cookie提示](Feature-Specific/Replace\_the\_modal\_cookie\_prompt.md)
  * [安全搜索](Feature-Specific/SafeSearch.md)
  * [Sane Time](Feature-Specific/Sane\_Time.md): 在Chrome中决定一个精确的时间
  * [安全web代理](Feature-Specific/Secure\_Web\_Proxy.md)
  * [服务进程](Feature-Specific/Service\_Processes.md)
  * [站点隔离](Feature-Specific/Site\_Isolation.md): 进程内的一些工作,提高Chromium在网站安全方面的进程模型
  * [软件更新: Courgette](Feature-Specific/Software\_Updates\_Courgette.md)
  * [同步](Feature-Specific/Sync.md)
  * [Tab助手](Feature-Specific/Tab\_Helpers.md)
  * [Tab搜索](Feature-Specific/Tab\_to\_search.md): 如果让地址栏自动提供标签来搜索你的网站
  * [Tabtastic2需求](Feature-Specific/Tabtastic2\_Requirements.md)
  * [临时下载](Feature-Specific/Temporary\_downloads.md)
  * [时间资源](Feature-Specific/Time\_Sources.md): 在一个Chrome OS设备上决定时间
  * [时钟](Feature-Specific/TimeTicks.md): 我们单一的时钟是如何在不同系统上工作的
  * [UI镜像基础设施](Feature-Specific/UI\_Mirroring\_Infrastructure.md): 描述ChromeViews中的UI框架,允许在希伯来与或阿拉伯语这样的RTL语言环境中镜像浏览器UI
  * [UI定位](Feature-Specific/UI\_Localization.md): 描述如何定位要加入chromium的字符串
  * [用户脚本](Feature-Specific/User\_scripts.md): Chrome对于用户脚本的一些支持信息
  * [视频](Feature-Specific/Video.md)
  * [WebSocket](Feature-Specific/WebSocket.md): 允许web应用程序与服务端进程维护一个双向的交流
  * [Web MIDI](Feature-Specific/Web\_MIDI.md)
  * [Web导航 API内部实现](Feature-Specific/WebNavigation\_API\_internals.md)
* [OS-相关](OS-Specific/)
  * [Android](OS-Specific/Android/)
    * [Android上的Java资源](OS-Specific/Android/Java\_Resources\_on\_Android.md)
    * [JNI绑定](OS-Specific/Android/JNI\_Bindings.md)
    * [WebView代码组织](OS-Specific/Android/WebView\_code\_organization.md)
  * [Chrome OS](OS-Specific/Chrome\_OS/)
    * 查看[Chrome OS设计文档相关章节](Feature-Specific/Omnibox\_Autocomplete/HistoryQuickProvider.md)
  * [Mac OS X](OS-Specific/Chrome\_OS/Chrome\_OS\_design\_documents\_section..md)
    * [Apple脚本Support](OS-Specific/Mac\_OS\_X/)
    * [BrowserWindowController对象所有权](OS-Specific/Mac\_OS\_X/AppleScript\_Support.md)
    * [确认退出](OS-Specific/Mac\_OS\_X/BrowserWindowController\_Object\_Ownership.md)
    * [Mac App模式(草案)](OS-Specific/Mac\_OS\_X/Confirm\_to\_Quit.md)
    * [Mac全屏模式(草案)](OS-Specific/Mac\_OS\_X/Mac\_App\_Mode\_\_Draft\_.md)
    * [Mac NPAPI插件托管](OS-Specific/Mac\_OS\_X/Mac\_Fullscreen\_Mode\_\_Draft\_.md)
    * [Mac上UI定位的相关记录](OS-Specific/Mac\_OS\_X/Mac\_NPAPI\_Plugin\_Hosting.md)
    * [菜单,快捷键和命令调度](OS-Specific/Mac\_OS\_X/Mac\_specific\_notes\_on\_UI\_Localization.md)
    * [IOSurface使用与语义相关会议的一些记录](OS-Specific/Mac\_OS\_X/Menus\_Hotkeys\_&\_Command\_Dispatch.md)
    * [OS X跨进程通信(已过时)](OS-Specific/Mac\_OS\_X/Notes\_from\_meeting\_on\_IOSurface\_usage\_and\_semantics.md)
    * [密码管理/密码链集成](OS-Specific/Mac\_OS\_X/OS\_X\_Interprocess\_Communication\_\_Obsolete\_.md)
    * [沙箱设计](OS-Specific/Mac\_OS\_X/Password\_Manager\_Keychain\_Integration.md)
    * [Tab切换设计(包括标签布局与标签拖动)](OS-Specific/Mac\_OS\_X/Sandboxing\_Design.md)
    * [扳手状菜单按钮](OS-Specific/Mac\_OS\_X/Tab\_Strip\_Design\_\_Includes\_tab\_layout\_and\_tab\_dragging\_.md)
* [Other](Other/)
  * [64位支持](Other/64-bit\_Support.md)
  * [浏览器组件/层级组件](Other/Browser\_Components\_\_\_Layered\_Components.md)
  * [闭合编译Chrome代码](Other/Closure\_Compiling\_Chrome\_Code.md)
  * [内容模块/内容API](Other/content\_module\_\_\_content\_API.md)
  * [正在编写的设计文档(wiki)](Other/Design\_docs\_that\_still\_need\_to\_be\_written\_\_wiki\_.md)
  * [可移植性:进程内重构关键浏览器进程架构](Other/In\_progress\_refactoring\_of\_key\_browser-process\_architecture\_for\_porting.md)
  * [网络实验](Other/Network\_Experiments.md)
  * [将float的inlinebox转为layout单元](Other/Transitioning\_InlineBoxes\_from\_floats\_to\_LayoutUnits.md)
