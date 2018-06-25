# PlusMenu
仿微博、酷安点击加号揭露动画弹出菜单+背景模糊效果
------
### 截图

![](https://github.com/DuShuYuan/PlusMenu/blob/master/screenshot/20180625_173334.gif)

-------
没有像酷安那样扩展到导航栏，以后有机会可以再研究吧。

使用的PopupWindow实现的，主要部分有
背景揭露动画；＋ 旋转动画；菜单项弹出动画；背景模糊效果

注意：在gradle中开启renderscript，支持模糊效果（高斯模糊也叫毛玻璃）
```
defaultConfig {
        applicationId "com.dsy.plusmenu"
        ...
        renderscriptTargetApi 25
        renderscriptSupportModeEnabled true
    }
```
### 参考项目

https://blog.csdn.net/SilenceOO/article/details/78976477

https://github.com/Manabu-GT/EtsyBlur
