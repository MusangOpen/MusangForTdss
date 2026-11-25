# MusangForTdss

土豆史诗（bilibili toy potatoepic）辅助脚本的**安装产物**仓库。

本仓库只放经过混淆的编译产物，源码在私有仓库维护。

## 安装

在篡改猴（Tampermonkey）里新建脚本 → 用「通过 URL 安装」填入：

```
https://raw.githubusercontent.com/MusangOpen/MusangForTdss/main/MusangForTdss.user.js
```

或直接打开：

https://raw.githubusercontent.com/MusangOpen/MusangForTdss/main/MusangForTdss.user.js

脚本头部带 `@updateURL` / `@downloadURL`，装好后篡改猴会自动检查新版本。

## 当前版本

`2.8.0` · 295.6 KB

## 用法

装好后打开游戏 https://www.bilibili.com/toy/potatoepic ，脚本注入到游戏 iframe 内。
默认 **右 Shift** 呼出 ClickGUI；顶部 ≡ 按钮右键可改菜单键。

移动端按 UA + 触摸能力自动判定，只切换输入通道，界面与桌面完全一致：
轻点 = 左键，长按 500ms = 右键，长按 ≡ 600ms 重绑菜单键。

## 调试接口

控制台可用：`__TDS_UI` `__TDS_CFG` `__TDS_AC` `__TDS_ACSELF` `__TDS_FUNPROBE`
`__TDS_CAMINFO` `__TDS_FUNSNIFF(ms)` `__TDS_INTRO_REPLAY`
