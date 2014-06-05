## 特殊文件

### Plist文件

Plist文件即属性列表（Property List），该文件是一种用来存储串行化后的对象的文件。属性列表文件的文件扩展名为.plist，因此通常被称为plist文件。也就是说该文件最初来自MAC系统，因Cocos2d-x起源于cocos2d-iphone，所以这一文件格式也被一同引入。&nbsp;

在cocostudio编辑器中，目前支持的plist文件有两种，一种以TexturePacker为代表导出的图像集合，另一种粒子（Particle）文件。plist图像文件都是两个文件（.plist/.png）同时存在的，并且文件名称相同，.plist负责图像文件信息存储，.png则存储整合后的图像。plist粒子文件则可能由一个或两个文件组成（.png是非必须存在的，当图片过小时图像将被base64转换成字符串存在.plist文件中）。&nbsp;

### PSD文件

PSD文件是Photoshop编辑器的源文件，可以直接使用Photoshop编辑，是photoshop专有的位图文件格式。PSD文件可以存储成RGB或CMYK模式，还能够自定义颜色数并加以存储，还可以保存Photoshop的层、通道、路径等信息，是目前惟一能够支持全部图像色彩模式的格式。 

![](style/light.gif)  
1：UI编辑器、动作编辑器、场景编辑器都支持plist图像和PSD图像。Plist粒子文件只有场景编辑器和动作编辑器可以使用。&nbsp;

2：Plist文件导入时必须将对应的.PNG图像一同导入到资源区。如果是直接放到项目的Resource文件夹内，可以通过刷新资源区更新数据。&nbsp;

3：Plist图像和PSD图像导入到资源区时都是以一个文件夹的形式显示（分别为&ldquo;PL&rdquo;和&ldquo;PS&rdquo;图标），文件夹内包含所有的子图。CocoStudio不提供对子图的编辑功能，你也不可以单独删除一个子图。&nbsp;

4：PSD图像的所有图层必须要做栅格化处理，未经栅格化的图像将不能被识别。&nbsp;

5：导出项目功能，不管你选择导出大图模式或导出小图模式，Plist图像将不会被再次编辑，而是直接导出。&nbsp;

6：导出项目时PSD则将所有使用的图层当做小图处理。如果导出大图将把需要的图层整合进plist图像中。&nbsp;

7：CocoStudio支持将Plist、PSD图形导出为碎图。（步骤：在资源区选中Plist图像，右键菜单选择&ldquo;导出为碎图&rdquo;选项。）&nbsp;

### CCB文件

CCB文件是CocosBuilder编辑器的源文件，CocosBuilder是一款MAC平台下的第三方可视化开发工具。CocoStudio提供对CocosBuilder的支持，对CocosBuilder文件可以使用导入功能。您可以在**UI编辑器** -&gt;**菜单栏**-&gt;**文件**-&gt;**导入CCB文件**选项选择需要导入的ccb文件。 

![](style/light.gif)CocosBuilder中部分控件在UI编辑器中将失效，转换完成后会显示转换统计。

### FLA文件

FLA文件是Flash编辑器的源文件，可以直接使用Flash编辑。为了利用已有资源CocoStudio提供对FLA 的支持。您可以在**动作编辑器**-&gt;**菜单栏**-&gt;**文件**-&gt;**打开Flash项目**选项来导入.fla文件。 

![](style/light.gif)  
1. 需要将 想要导入到动画编辑器的元件放入到主场景中&nbsp;。

2. 暂时不支持导入矢量图形，可以右键矢量图形转换为位图。

3. 暂不支持嵌套元件的元件作为骨骼部件&nbsp;&nbsp;。

<center>Copyright © 2013 [CocoStudio.org](http://www.cocostudio.org ""). All Rights Reserved. 版本:1.4.0.0</center>