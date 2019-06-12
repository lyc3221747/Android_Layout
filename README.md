# 移动软件开发

##实验二 Android布局

主界面选择所要查看的布局


![](https://i.loli.net/2018/03/25/5ab7c39e5a2f1.png)

线性布局


实现：将总布局LinearLayout中的orientation属性设为vertical,再嵌套4个LinearLayout布局orientation属性设为horizontal，其中每个布局嵌套4个Button


![](https://i.loli.net/2018/03/25/5ab7c47b46511.png)

关系布局


将总布局RelativeLayout中的orientation属性设置为vertical，background背景色设为黑色，嵌套7个TextView。


(1)第一个红色TextView将控件的上边缘边缘和父控件的左边缘对齐layout_alignParentTop=true，将控件的左边缘和父控件的左边缘对齐layout_alignParentLeft=true。


(2)第二个橙色TextView将控件的上边缘和父控件的左边缘对齐layout_alignParentTop=true，将控件置于水平方向的中心位置layout_centerHorizontal="true" 。


(3)第三个黄色TextView将控件的上边缘和父控件的左边缘对齐layout_alignParentTop=true，将控件的右边缘和父控件的右边缘对齐layout_alignParentRight=true。


(4)第四个绿色TextView将控件放置于蓝色TextView的左侧layout_toLeftOf="@+id/blue"（要先实现蓝色Textview），同时将控件置于垂直方向的中心位置layout_centerVertical="true"，与右控件蓝色TextView产生一些间距layout_marginRight="20px"。


(5)第五个蓝色TextView将控件设置于父控件的中心位置layout_centerInParent="true"。


(6)第六个紫色TextView将控件放置于蓝色TextView的右侧layout_toRightOf="@+id/blue"（要先实现蓝色Textview），同时将控件置于垂直方向的中心位置layout_centerVertical="true"，与左侧控件蓝色TextView产生一些间距layout_marginLeft="20px"。


(7)第七个粉色TextView将控件的底部边缘和父控件的底部边缘对齐layout_alignParentButtom=true。


![](https://i.loli.net/2018/03/25/5ab7c4b4e55fa.png)

表格布局


利用总布局为LinearLayout设置为orientation="vertical"，嵌套一个TableLayout并设置成6行TableRow每行嵌套3个TextView,同时将TableLayout中stretchColumns="1"设置所用行的第二列为扩展列,如果有三列的话，剩余空间由第二列补齐。


![](https://i.loli.net/2018/03/25/5ab7c4d752dac.png)
