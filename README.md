源码:https://github.com/NativeStar/DisableScreenshotSound

Xposed模块 用于屏蔽使用Android原生截屏功能时发出音效

开发原意是:某些高度定制UI(如HyperOS)在使用其他模块强行启用Android原生截屏后

其自带的截屏音效根本找不到地方关(设置里头改了没效)

因此采用Hook系统界面的方式去除它

已确认在Android14 15上可用 其他版本请自行测试

### 使用方法

在LSPosed作用域中勾选推荐应用(其实就一个系统界面)

然后重启系统或作用域
