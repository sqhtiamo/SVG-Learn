SVG重用与引用

组合 - g元素 <br>
g元素是一种容器，它组合一组相关的图形元素成为一个整体；这样，我们就可以对这个整体进行操作。这个元素通常可以和desc和title元素配合使用，提供文档的结构信息。<br>
g元素是可以嵌套的。 <br>
组合起来的图形元素就和单个的元素一样，可以给id值。 <br>

模板 - symbol元素 <br>
可以被use元素实例化。<br>
symbol元素本身是不会被渲染的，只有symbol模板的实例会被渲染。<br>
symbol元素可以拥有属性viewBox和preserveAspectRatio，这些允许symbol缩放图形元素。?? <br>

定义 - defs元素 <br>
 SVG允许定义一组对象，然后重用这组对象，不仅仅是图形对象。最常见的例子如定义渐变色，然后再其他的图形对象中赋给fill属性。<br>
 这些对象通常是：altGlyphDef,clipPath,cursor,filter, marker,mask,pattern,linearGradient,radialGradient，symbol和图形对象等。 <br>

引用 - use元素 <br>
use元素的作用过程就相当于把被引用的对象深拷贝一份到独立的非公开的DOM树中；这棵树的父节点是use元素。<br>