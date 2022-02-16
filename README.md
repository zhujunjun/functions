# functions
小功能收集
+ Android中跳转系统特定设置界面(https://www.jianshu.com/p/7c7acc132ca8)
+ kotlin 语法文档（https://www.kotlincn.net/docs/kotlin-docs.pdf）
     + ![kotlin 操作符](https://p1-jj.byteimg.com/tos-cn-i-t2oaga2asx/gold-user-assets/2017/11/27/15ffcf5b7d7896c7~tplv-t2oaga2asx-watermark.awebp "操作符区别图")
+ 安卓自定义View基础-角度与弧度
     +  角度和弧度一样都是描述角的一种度量单位，下面是它们的定义：
     +  角度：两条射线从圆心向圆周射出，形成一个夹角和夹角正对的一段弧。当这段弧长正好等于圆周长的360分之一时，两条射线的夹角的大小为1度.
     +  弧度：两条射线从圆心向圆周射出，形成一个夹角和夹角正对的一段弧。当这段弧长正好等于圆的半径时，两条射线的夹角大小为1弧度.
     +  ![角度示意图](http://gcsblog.oss-cn-shanghai.aliyuncs.com/blog/2019-04-29-071103.jpg?gcssloop)
     +  ![弧度示意图](http://gcsblog.oss-cn-shanghai.aliyuncs.com/blog/2019-04-29-071104.jpg?gcssloop)
+ 角度和弧度的换算关系:
     + 圆一周对应的角度为360度(角度)，对应的弧度为2π弧度。
     + 故得等价关系:360(角度) = 2π(弧度) ==> 180(角度) = π(弧度)
     + 由等价关系可得如下换算公式:

  
  | 公式       | 例子  |
    | --------   | -----   |
    | rad = deg x π / 180        | 2π ＝ 360 x π / 180     | 
    | deg = rad x 180 / π        |360 ＝ 2π x 180 / π     | 
+ 维基百科的公式：rad 是弧度， deg 是角度
     ![百科公示](http://gcsblog.oss-cn-shanghai.aliyuncs.com/blog/2019-04-29-071106.jpg?gcssloop) 
+ 在常见的数学坐标系中角度增大方向为逆时针，在默认的屏幕坐标系中角度增大方向为顺时针。
     + ![角度方向](http://gcsblog.oss-cn-shanghai.aliyuncs.com/blog/2019-04-29-71107.jpg?gcssloop)
+ 在drawArc中 startAngle 是弧形的起始角度 sweepAngle 是弧形划过的角度
      ![示意图](https://www.pianshen.com/images/743/a76d4e7cf43074e813f696d49cfb4d9f.png)
    + 以这张图为例  startAngle的角度是从x轴的右侧开始为0度 也就是说 当我们给定startAngle角度为90度时，那么他就是从图上90度的地方开始画 
    + sweepAngle其实就是所画的弧度范围  打个比方 我们startAngle为90 sweepAngle 为100
      ![示意图](https://www.pianshen.com/images/14/7f8dbd977ce128e57e7ded4310960dfe.png)
    + 那么绘制的形状就是图上黄色区域部分（以连接到圆心为例）  这里要说一下 sweepAngle为100度 也就是从起始角度开始
    + 顺时针画100度 这也就是说 sweepAngle的0度位置其实就是startAngle的位置 ，以下图为例sweepAngle的0度就是startAngle的起始角度所以 从这个角度开始顺时针画100度，那么就是这个形状了
      ![示意图](https://www.pianshen.com/images/623/fc3329dd43b13c0712851879d09ff617.png)
 + Spannable对象 设置textview的各种样式(https://www.cnblogs.com/tianzhijiexian/p/4222393.html)
 + Android ADB 命令大全(https://github.com/mzlogin/awesome-adb/)
