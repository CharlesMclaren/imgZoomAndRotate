# imgZoomAndRotate
基于jQuery的图片展示插件，支持图片循环切换，缩放，旋转，拖拽。

本插件参考了imgZoom,在这个基础上添加了以下功能
+ 在iframe下全屏展示和操作图片；
+ 添加上一张，下一张，左旋，右旋，和关闭图片按钮的功能；
+ 添加十字键盘切换图片和进行缩放；
+ 支持图片元素在dom不同的层级下同时进行绑定；
+ 缩放(原有功能)

使用方法：
$(imgs).imgZoomAndRotate();
可选参数{'loop':true}，图片切换时可循环。

![](example.png)