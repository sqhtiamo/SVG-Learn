SVG绘制

矩形 - rect元素
x：矩形左上角的坐标(用户坐标系)的x值。
y：矩形左上角的坐标(用户坐标系)的y值。
width：矩形宽度。
height：矩形高度。
rx：实现圆角效果时，圆角沿x轴的半径。
ry：实现圆角效果时，圆角沿y轴的半径。

圆 - circle元素
r：圆的半径。
cx：圆心坐标x值。
cy：圆心坐标y值。

椭圆 - ellipse元素
rx：半长轴(x半径)。
ry：半短轴(y半径)。
cx：圆心坐标x值。
cy：圆心坐标y值。

直线 - line元素
x1：起点x坐标。
y1：起点y坐标。
x2：终点x坐标。
y2：终点y坐标。

折线 - polyline元素
points：一系列的用空格，逗号，换行符等分隔开的点。"0 0, 1 1, 2 2"。

多边形 - polygon元素
points：一系列的用空格，逗号，换行符等分隔开的点。"0 0, 1 1, 2 2"。

路径 - path元素
d：一系列绘制指令和绘制参数(点)组合成。
绝对坐标绘制指令
M(move)        x y      M20,230
L(line)        x y
H(horizantal)  x
V(vertical)    y
A(Arc)         rx ry xar lf sf x y 
(x半轴长 y半轴长 椭圆x轴与水平方向夹角 1大弧0小弧 1顺0逆)
C              x1 y1 x2 y2 x y   三次贝塞尔曲线
S
Q
T
Z                                封闭曲线
参考文献:
1. http://www.cnblogs.com/dxy1982/archive/2012/04/06/2395729.html