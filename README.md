# 传送门增强 -- TaplusExtension

为 MIUI传送门 量身定做的增强模块

Enhanced modules tailored for MIUI Taplus

## 支持版本

原理上适配 `2.2.0 +`，建议升级到 **最新** 版本

## 功能

* 优化链接打开方式
* 优化链接识别能力
* 添加移除购物开关
* 优化复制，去除多余空格
* 添加长按批量复制，配合输入法的剪贴板使用
* 强化搜索，内置主流搜索引擎，并支持自定义

#### 老机型强制开启：

* 双指长按
* 区域选择
* 图片保存模式

## 使用

1. 在 LSPosed管理器 中激活模块
2. 作用域勾选 传送门(**`com.miui.contentextension`**)
3. **重启传送门** (即强行停止)
4. 更多配置请转到 `设置-更多设置(特色功能)-传送门`

## 注意事项

1. 自定义搜索引擎的 url 格式：

    1. 必须以 **http** 开头
    2. 必须包含 **%s** ，用于代替搜索词

    示例：`https://www.exmaple.com/s?q=%s`

2. 关于老机型的强制开启功能，会因设备底层不支持的原因从而不生效

## 下载

[LSPosed 仓库](https://github.com/Xposed-Modules-Repo/io.github.yangyiyu08.taplusext/releases)

[蓝奏云](https://qyma.lanzout.com/b051gtd3i) 密码:`miui`

## 无效

请先检查模块是否正常激活，并且作用域是否勾选。如果排查后仍有错误，请提交issue。或联系酷安[@yangyiyu08](http://www.coolapk.com/u/1188320)

## 致谢

模块使用 [Yuki Hook API](https://github.com/fankes/YukiHookAPI) 构建
