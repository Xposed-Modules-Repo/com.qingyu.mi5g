# FiveGSwitcher 5G开关
仅适用于MIUI，在状态栏的快捷开关中添加 5G网络 开关

### 特点
1. 无后台服务
2. 无图标，无配置，即装即用

### 使用
1. 在Xposed管理器(LSPosed, EdXposed...)中激活模块 (推荐使用LSP)
2. 作用域勾选 系统界面`(com.android.systemui)`、电话服务`(com.android.phone)`
3. 重启手机
+ ❗电话服务为可选作用域，其作用于老版本的 MIUI(12) 自动打开 5G 的 SA 服务，正常情况下无需勾选

### 下载
[LSPosed 仓库](https://github.com/Xposed-Modules-Repo/com.qingyu.mi5g/releases)

### 无效
请先检查模块是否正常激活，并且作用域是否勾选。如果排查后仍有错误，请提交issue。或联系酷安[@yangyiyu08](http://www.coolapk.com/u/1188320)

### 致谢
模块使用 [Yuki Hook API](https://github.com/fankes/YukiHookAPI) 构建
