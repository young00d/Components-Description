# Tabs

> Tabs用来切换不同的页面, 或者切换不同的数据内容





### Types

##### Mono Space

“等分型” Tabs会在屏幕宽度内完全展示, 其子Tab宽度为 “屏幕宽度/Tab数量” . “等分型” Tabs位置固定, 子Tab数量为2到4个, 一般来说不会超过4个.

![Tab_MonoSpace](/Users/admin/Library/Mobile Documents/com~apple~CloudDocs/MOOMOO💎/✒️20190220moomoo界面设计规范/moomoo组件说明Component Description/Tab_Asset/Tab_MonoSpace.png)



##### Flexible

灵活型的Tab没有固定宽度. 每个子Tab的宽度, 由文本长度和Padding相加得出. 当子Tab的个数增多, 直到超出屏幕宽度时, 该Tab由固定变为可滚动. 右边超出屏幕宽度的子Tab, 可以通过滚动手势展现. 默认情况下, 此类型的Tab是从左往右排列的. 

![Tab_Flexible](/Users/admin/Library/Mobile Documents/com~apple~CloudDocs/MOOMOO💎/✒️20190220moomoo界面设计规范/moomoo组件说明Component Description/Tab_Asset/Tab_Flexible.png)







### Anatomy

![Tab_Anatomy](/Users/admin/Library/Mobile Documents/com~apple~CloudDocs/MOOMOO💎/✒️20190220moomoo界面设计规范/moomoo组件说明Component Description/Tab_Asset/Tab_Anatomy.png)

1. Container 背景
2. Indicator 滑块
3. Tab Item 子tab
4. Active Text 选中文字
5. Resting Text 普通文字
6. Line 分割线







### Text Label

Tab文本应该单行显示. 标题文本有两种, 第一种是应用内定义的标题文本, 该文本由产品设计决定, 产品文案上应该确保文本可读性强且长度合适; 第二种是用户自定义的标题, 该文本由用户自主输入, 在产品的交互设计上, 应该对输入长度进行一定的限制. 

![Text_Label](/Users/admin/Library/Mobile Documents/com~apple~CloudDocs/MOOMOO💎/✒️20190220moomoo界面设计规范/moomoo组件说明Component Description/Tab_Asset/Text_Label.png)

1. 不可以折行
2. 不可以缩小文本字号
3. 不可以用 “…” 缺省内容







### Gesture

##### Tap a Tab

通过点击切换Tab, 点击范围为该Tab所占的整块区域

点击区域图



##### Swipe within the Content Area

\1.顶部Tabs

顶部Tabs导领整屏内容, 通过横向滑动内容区域的屏幕, 可以切换到上一个或者下一个Tab. 

图

\2. 页面中部Tabs

页面中部的Tabs仅导领一定区域的内容, 无法通过滑动手势进行切换.

图



### States

选中的Tab有normal和pressed两种状态

图

未选中的Tab有normal和pressed两种状态

图



### Color

图

| 元素 | 色值 |
| :---: | :----: |
| aaaa | bbbbbb |
| a | b |



### Typography

图

| Category层级 | Font | Weight | Size | Case大小写 |
| :---: | :----: | :----: | :----: | :----: |
| Title | Din - 2014 | Regular | 42 | 首字母大写 |



### Spec

图

图