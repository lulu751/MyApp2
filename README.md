# MyApp2

安卓开发中常见布局介绍：


1、 LinearLayout (线性布局)

说到LinearLayout, 我想说一下流式布局。其实LinearLayout就是流式布局，流式布局有个特点，就是下一个控件的坐标原点由上一个控件来决定，你可以沿水平方向或者垂直方向上来排列你的控件。 如果你的控件是垂直排列的，那么你可以给控件指定水平的居中方式。


2.RelativeLayout (相对布局)

上面也说了一下相对布局, 相对布局的本质就是以不变应万变。也就是说相对布局可以根据已经固定的控件来确定其他新加控件的位置。相对布局用的还是蛮多的。


3.帧布局 (FrameLayout)

说到帧布局, 就比较简单了，而且比较好理解，并且帧布局的用处不是很多，但他的存在还是有他的必要性的。FrameLayout中的Frame和iOS中的Frame不是一个概念，在iOS中的Frame你可以指定任意的坐标，而这个坐标点时相对于父视图的。FrameLayout中的Frame的坐标原点是屏幕的左上角，位置固定，你只需为控件指定大小即可。


4、表格布局（TableLayout）

如果你接触过Web前端的东西的话，虽然常用的时div + css , 但是Web前端也是有表格布局的。在安卓开发中的表格布局和Web前端中的表格布局的概念类似，也就是通过画表表格的方式来实现布局。 在表格布局中，整个页面就相当于一张大的表格，控件就放在每个Cell中。



题目一、利用线性布局实现如下界面：

![](https://img-blog.csdnimg.cn/20190313220105828.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

方法一：用线性布局里面嵌套表格布局
实现运行结果图如下：

![在这里插入图片描述](https://img-blog.csdnimg.cn/2019031322025175.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

方法二：直接使用线性布局嵌套线性布局

实现运行结果图如下：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190313220343360.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

题目二：利用ConstraintLayout实现如下界面：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190313220428278.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

实现运行结果图如下：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190313220450125.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

题目三：利用表格布局实现如下界面：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190313220516850.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)

 实现运行结果图如下：
 
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190313220556871.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x1X2x1X3poYW5n,size_16,color_FFFFFF,t_70)
