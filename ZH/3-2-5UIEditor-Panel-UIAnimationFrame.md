## UI动画帧面板

### 简介

![](img/3-2-5-img-01.png)

在UI编辑器中编辑UI动画，需要切换到动画模式进行编辑，动画编辑完成后，可以切换到普通模式进行面板的布局编辑。

### 功能

#### 帧操作

![](img/3-2-5-img-02.png)

##### 添加帧

1. 如上图所示：右键添加关键帧就会在鼠标位置创建一个灰色的椭圆作为关键帧的标记。                

2. 也可以通过左上角的添加关键帧按钮进行添加。

##### 删除帧

如上图所示：右键删除帧就会删除当前选中的关键帧，即删除当前选中的椭圆标记。

##### 移动帧

选中关键帧的椭圆标记经过鼠标拖拽可以移动你想要的位置。

#### 动画播放

![](img/3-2-5-img-03.png)

<table border="1" cellspacing="0" cellpadding="0" >
              
                <tr>
                  <td width="516" ><img src="style/b1.png" alt="" /> 播放动画：点击将开始播放当前选择动画。</td>
                </tr>
                <tr> </tr>
                <tr> </tr>
                <tr>
                  <td >    <img src="style/b2.png" alt="" />停止动画：停止当前播放动画</td>
                </tr>
                <tr> </tr>
                <tr> </tr>
                <tr>
                  <td ><img src="style/b3.png" alt="" />添加关键帧：鼠标选中需要添加关键帧的位置，点击将添加一个关键帧。</td>
                </tr>
                <tr> </tr>
                <tr> </tr>
                <tr> </tr>
                <tr>
                  <td colspan="3" rowspan="5"><img src="style/b4.png" alt="" />循环动画：勾选将循环播放动画</td>
                </tr>
                <tr> </tr>
                <tr> </tr>
                <tr> </tr>
                <tr> </tr>
                <tr>
                  <td colspan="3" rowspan="3"><img src="style/b5.png" alt="" />帧播放的间隔时间：可以通过设置间隔时间来控制动画运行的快慢。</td>
                </tr>
                <tr> </tr>
                <tr> </tr>
                <tr>
                  <td colspan="3" rowspan="3"><img src="style/b6.png" alt="" />鼠标位置在第几帧：显示鼠标放置在第几帧便于用户精确添加关键帧。<br /></td>
                </tr>
                <tr> </tr>
                <tr> </tr>
</table>

#### 缓动

&ldquo;缓动&rdquo;是指动画过程中的渐进加速或减速，它会使您的动画看起来更逼真、更自然。目前编辑器提供了30中默认缓动类型。另外提供自定义缓动曲线编辑功能，您可以按照自己的需求来编辑缓动曲线。

![](img/4-2-8-img-05.png)

自定义

自定义曲线是通过选择两个关键点绘制的_贝塞尔曲线_(B&eacute;zier curve)。有关_贝塞尔曲线_(B&eacute;zier curve)的内容您可以在[wikipedia](http://zh.wikipedia.org/wiki/%E8%B2%9D%E8%8C%B2%E6%9B%B2%E7%B7%9A#.E4.BA.8C.E6.AC.A1.E6.9B.B2.E7.B7.9A)上了解更详细的内容。

预设

cocostudio一共预设了30种缓动类型，你可以挑选一种作为该帧区间的缓动类型。默认为line，即无缓动。

<center>Copyright © 2013 [CocoStudio.org](http://www.cocostudio.org ""). All Rights Reserved. 版本:1.4.0.0</center>