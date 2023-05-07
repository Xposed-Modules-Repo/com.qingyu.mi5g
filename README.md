# 5G开关 -- FiveGSwitcher

仅适用于MIUI，在移动网络面板或快捷开关中添加 5G 开关

For MIUI only, add 5G switch in the network panel or qs tile.

## 特点

1. 无后台服务
2. 无图标，无配置，即装即用

## 使用

1. 在Xposed管理器(LSPosed, EdXposed...)中激活模块 (推荐使用LSP)
2. 作用域勾选 系统界面(**`com.android.systemui`**)、电话服务(`com.android.phone`)
3. **重启手机**

❗电话服务为可选作用域，其作用于老版本的 MIUI(12) 自动打开 5G 的 SA 服务，无此需求可不勾选

## 版本

- 文件以 `-tile` 结尾的为磁贴开关
- 文件以 `-panel` 结尾的为面板开关

## 下载

[LSPosed 仓库](https://github.com/Xposed-Modules-Repo/com.qingyu.mi5g/releases)

[蓝奏云](https://qyma.lanzout.com/b051np9gf) 密码:`miui`

## 截图

<table>
  <tr>
    <td>
      <img src="https://user-images.githubusercontent.com/42611305/236685136-788c230f-e21c-4083-aeb3-78d21616b481.png" alt="磁贴开关" />
    </td>
    <td>
      <img src="https://user-images.githubusercontent.com/42611305/236685166-9934747c-c98a-43a2-9301-2e82b0c82607.png" alt="面板开关" />
    </td>
  </tr>
  <tr>
    <td align="center">
      磁贴开关
    </td>
    <td align="center">
      面板开关
    </td>
  </tr>
</table>

## 无效

请先检查模块是否正常激活，并且作用域是否勾选。如果排查后仍有错误，请提交issue。或联系酷安[@yangyiyu08](http://www.coolapk.com/u/1188320)

## 致谢

模块使用 [Yuki Hook API](https://github.com/fankes/YukiHookAPI) 构建
