# Cinemagraph

Cinemagraph ，一种局部呈现动态而其余部分凝固以突出视觉感受的动静结合的摄影作品。<br /> 
<br /> 
是视觉设计师 Kevin Burg 与摄影师 Jamie Beck 在大约三年前发现的一种很有意思的图片展示模式。<br /> 
<br /> 
右边链接有具体的介绍，该网站上也有很多他们的作品。→ [The History of Cinemagraphs](http://cinemagraphs.com/about/) <br /> 
<br /> 

今天实验了一下，粗略的完成了一幅。大致讲一下自己拍的这张杯子是如何做的，其他的就举一反三了。<br />
<br />

1) 拍摄 <br /> 

感觉手机应该不是很适合拍摄这种，也不是完全不可能，就是快门可能稍微慢了点，没有 iPhone 5S，不知道传说中的机关枪快门如何，但是手持的话肯定不行，每张差的稍微多，就很难结合起来了，而且 iPhone 应该也不好锁定曝光参数，动的部分如果稍微多点光线变化，就难结合了。

我只有入门单反，随便拍拍也是能出的，M 档是必须的了，最好有三脚架&快门线/遥控（本穷货就没有，，，搭在书上，还垫了点东西倾斜的，一个手拿杯子一个手按快门），建议手动对焦，先拍几张试试光线，然后固定好相机对好大概的焦点快门设为连拍。然后摇一下杯子，水动起来以后手马上保持静止，最好有东西依靠，然后迅速控制快门，按他个十几二十多张。拍摄部分就做完了。<br /> 
<br /> 

2) 制作 <br /> 

绝对的体力活。。。抠的很麻烦。<br /> 

建议部分：由于我忘记了，，所以自己没做，，，第一，单反出来的图，，，都是 4k 多乘好几 k 的图，先批量缩放小一些比如到 1920之类的宽度也好的多，省得后面生成 gif 的时候动作很慢，也别太小，免得以后想生成大一些图还得重做，后期我尝试了一下用 Lightroom，但是发现原图每张图光线是差不多的，但是用滤镜的话，可能是平均什么的算法，个别图会出现明显的亮度区别。忘记s试试只手动拉拉曲线然后粘贴照片设置了，有兴趣可以自己试试，用看图软件过一遍看看会不会有明显的亮度之类的差距。<br /> 
<br /> 

接着就是 Photoshop 发挥的时候了，以第一张照片做为背景图层，然后依次打开后面的照片，把水面波动的部分抠下来，依次贴在我们的待完成品项目里，抠的时候可以抠大一点，因为好利用那些边缘对齐背景图，手不可能完全的纹丝不动，的图尽量对齐还是不容易被看出来的。然后用橡皮擦，选那种边缘比较羽化的那种头子来擦比较容易融入背景图，尽量只保留水面变动的部分，抠的时候图层里只用眼睛标记该层和第一张背景图层，时不时打开关闭背景图的眼睛来看看效果，最好再利用打开关闭当前编辑的图层并打开前一个编辑的图层来进行对比，以免帧直接变化太突兀。这部分非常耗时，也比较枯燥，熬过去就好。。。<br />
<br />

{% img http://Cinemagraph/readme_imgs/all_layer.png %}

{% img http://Cinemagraph/readme_imgs/cover_layer.png %}

<br />
<br />
体力活干完后面就很轻松了，PS 只要不是版本太低，都是可以直接制作 GIF 的，点击  ***菜单>窗口>时间轴***。<br />
<br />

可能第一次打开看到下面是这样的界面，我们要用另外一种。点击左下角那 3 个方框连在一起的按钮。<br />
<br />
{% img http://Cinemagraph/readme_imgs/time_line_01.png %}
<br />

然后就看到下图这样的界面了。<br />
{% img http://Cinemagraph/readme_imgs/time_line_02.png %}
<br />

后面没什么特别要说的，就是点击红色箭头那里多复制几个帧，然后分别处理每个帧的事件和时常，以及把「一次」那里点选为永远，即自动循环播放。每一帧的事件即背景图层在每一帧都用眼睛打开，然后第一帧只显示背景图层，后面依次打开该帧相应的图层以覆盖背景图层。即 1-2、1-3、1-4 ...... 这样顺序显示图层。<br />
<br />

最后就是生成并保存了， 点击 菜单>文件>存储为 Web 所用格式... 。<br />

如类似下图参数来保存 GIF 图，红色箭头部分选择格式，以及调整分辨率即可。<br />
{% img http://Cinemagraph/readme_imgs/export.png %}

<br />
点击存储，选择位置，打完手工。
<br />



成品如下图 <br />
{% img http://Cinemagraph/a_glass_of_water/a_glass_of_water.gif %}
