---
aside: true
outline : 3

---
# :tada:插件特性：
### 01.两种封皮类型
可创建两种封面类型的书:  
**硬皮书**: 有厚度、可以有凹槽.  
**软皮书**: 无厚度、没凹槽,可以弯曲.

![两种书皮](/img/两种书皮.jpg)

### 02.自定义页数
可以自定义书本的页数. 100代表有100张纸, 即页码到200.
<div align=center><img src="/img/页数.png"></div> 

:::tip 书页参数
页数最多到100,即页码最多到200
:::

### 03.没有穿插
在翻页时页与页之间没有穿插。

![穿插](/img/穿插.gif "穿插") 

### 04.参数丰富
- #### 可以分别调节书本封面和内页的长，宽，高.
  (参数设置里有两部分,1.封面的长，宽，高，2.书页的长和宽)

<div align=center><img src="/img/封面长宽高.png"></div>  
<br />
<div align=center><img src="/img/书页长宽高.png"></div>  
<br />
<div align=center><img src="/img/长宽高.gif"></div> 



- #### 硬皮书可以选择是否需要封面的凹槽.
  :::tip 小贴士
  凹槽的制作原理是布尔运算，所以从原理上来讲，凹槽的位置,形状,大小,倒角等都可以充分自定义.
  :::
  <div align=center><img src="/img/封面凹槽.jpg"></div> 

- #### 可以自由调节硬皮封面的厚度和书脊的弯曲弧度.  
  <br />
  <div align=center><img src="/img/封面厚度与弯曲.png"></div> 
  <br />
  <div align=center><img src="/img/封面厚度.gif"></div> 

  :::tip 小贴士
  注意：调节厚度后要注意调整凹槽的形态和位置。
  :::

- #### 可以自由调节书页翻动时的弯曲强度.  

  ![弯曲效果器](/img/弯曲效果器.gif "弯曲效果器") 
  :::tip 小贴士
  书页翻起和落下时的弧度都可以调整,所有书页同时调整,还可以调整书页发生弯曲的位置，注意弯曲不能太大，太大在翻页时会出现穿插
  :::

- #### 书页拱形控制:可调节书页打开状态下两边书页的松散状态
  ![左右松散](/img/左右松散.gif)
  :::tip 小贴士
  在打开状态下调节松散程度后,有可能出现打开或关闭时书页穿出封面的情况,这时可以考虑在翻开状态和关闭状态下分别key帧,达到没有穿插的效果.
  :::
  等等......更多可见[参数解释](parameters.md)

### 05.材质直观
针对封面的正面，侧面，背面，内面和厚度部分都有对应的材质球来控制。  

![各面材质](/img/各面材质.jpg)

#### 不同的渲染器，材质设置不同。  
材质都是最基础的设置,对渲染器比较熟悉的话,一看就懂.有问题的也可以看我针对各个渲染器的讲解.
- **默认渲染器**>>>：  

每一张书页都有两个材质球，对应该书页的正反两面，分别控制该书页的正，反面贴图。
比如下图，Page.001和Page.002分别控制第一张纸的正面和反面，既页码1和页码2的材质贴图。
![第一页材质分配](/img/第一页材质分配.jpg)  

你可以在材质里手动替换贴图，也可以准备好你的贴图，并且按照既定的规则命名，批量替换所有贴图。  

针对不同的渲染器(Octane,Redshift,Arnold,Vray)，制作了替换贴图的方法：

[其他渲染器替换贴图](other-renders.md) (包括手动替换和批量替换)
- [Octane](Octane.md)  
- [Redshift](Redshift.md)  
- [Arnold](Arnold.md)  
- [Vray](Vray.md)  
- [Corona](Corona.md)  
:::tip 小贴士
C4D渲染器比较多，作者不可能全部精通，目前的方法均测试过多次，但使用过程中若有错漏，敬请指正。
:::
 
 

### 06.动画方便
书页的封面和内页都有单独的关键帧控制翻页动画：  
可以很方便直观得调节书页的翻开动画。  
封面,封底和内页每一页都有单独的关键帧控制翻开的动画,所以你可以自由控制每一页打开的时间,很方便得设置先翻一页,再翻一页,或者几页一起翻的动画.
![关键帧](/img/关键帧.png) 


### 07.可以实现书页参差不齐的效果
![参差动画](/img/参差动画.gif)

### 08.兼容各大常用渲染器
插件制作了Octane,Redshift,Arnold,Vray的版本.  
还制作了针对各个渲染器的材质替换的使用说明.  

[其他渲染器替换贴图说明](other-renders.md) (包括手动替换和批量替换)
- [Octane](Octane.md)  
- [Redshift](Redshift.md)  
- [Arnold](Arnold.md)  
- [Vray](Vray.md)  
- [Corona](Corona.md)  

### 09.详细的常见问题总结
中英文的详细使用说明.一站式解决问题.  
[←左侧常见问题收集列表](question.md)
