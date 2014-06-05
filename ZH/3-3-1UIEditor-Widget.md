## UI编辑器控件

### 概述

ＵＩ编辑器控件是组成ＵＩ界面的基本元素。每一个种控件都有其特殊的属性，可以通过这些控件间的组合来设计出丰富的界面效果。

### 控件

*   [按钮](3-3-2UIEditor-Widget-UIButton.md)
*   [复选框](3-3-3UIEditor-Widget-UICheckBox.md)
*   [图片](3-3-4UIEditor-Widget-UIImageView.md)
*   [数字标签](3-3-6UIEditor-Widget-UILabelAtlas.md)
*   [自定义字体](3-3-7UIEditor-Widget-UILabelBMFont.md)
*   [进度条](3-3-8UIEditor-Widget-UILoadingBar.md)
*   [滑动条](3-3-11UIEditor-Widget-UISlider.md)
*   [文本框](3-3-12UIEditor-Widget-UILabel.md)
*   [输入框](3-3-14UIEditor-Widget-UIField.md)
*   [层容器](3-3-9UIEditor-Widget-UIPanel.md)
*   [滚动层](3-3-10UIEditor-Widget-UIScrollView.md)
*   [列表层](3-3-17UIEditor-Widget-UIListView.md)
*   [分页层](3-3-18UIEditor-Widget-UIPageView.md)
*   [自定义控件](3-3-19UIEditor-Widget-CustomWidget.md)
</div>

### 通用属性

#### 
交互

控制控件是否接受用户事件，如果该控件需要接受用户事件（如按钮），则需勾选。

#### Tag

设置控件的Tag，程序中可以通过该Tag值获取该控件。

#### 名字

设置控件的名称，程序中可以通过该名称获取该控件。

#### 渲染层级

设置控件渲染的先后顺序。值越小越先渲染，但是可能会被后渲染的覆盖。

#### 透明度

设置控件的透明度。取值范围为0到255。0 为纯透明，255为不透明。

#### 颜色混合

此属性设置控件的混合颜色。点击下拉菜单后会出现颜色选择框，选择颜色后会将原控件与该颜色进行混合渲染。

[UI控件常规属性](3-3-16UIEditor-General-Property.md)

<center>Copyright © 2013 [CocoStudio.org](http://www.cocostudio.org ""). All Rights Reserved. 版本:1.4.0.0</center>