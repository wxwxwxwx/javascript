# javascript概述

## 基础逻辑处理部分



> 变量 数据类型         (数据存储)
> 分支和循环运算符           (逻辑操作)

  * 函数(对语言的扩展)

### 数据类型

```javascript
var vr = 1.2;           //number
var vr = "aa";          //string
var vr = [1,2,3];       //Array
var vr = {a:1,b:2};     //Object
var vr = function(){}   //Function
var vr = true           //Boolean
var vr = undefined        
var vr = null
+ - * / %
===  !== > < >= <= 
&& || !
```

### 分支语句

```javascript

if()
if()else
if()else if()else if()
swidth(x){
	case 1:
	break;
	case 2:
	break;
	default
}
```
### 循环语句

```javascript
for(var i=0;i<=vr;i++){
	
}
while(){
	
}
do{
	
}while()

```
### 函数

```javascript

function aa(){
	
}
var fn=function(x,y){
          //arguments	
}
fn(a,b)


function A(c){
	this.x=c;
}
A.prototype.console.log = function(){
	console.log()
}
var obj = new
```
###  数组的常用方法
###  字符串中的常用方法
###  函数对象中的方法
###  对象的增删改查 原形链
###  数字对象身上的方法  toFixed
###  Math对象身上的方法

## 针对特定用途的部分

> 当js拿浏览器运行的那一刻
> 浏览器会创建一个window对象
> window对象中有很多属性和方法
> 这些属性和方法不用加window.就可以调用使用

>dom对象  dom集合

>从document对象开始利用他的方法找出我们需要的元素，这种元素叫做(
>dom元素或者是dom集合)

 dom对象
```javascript
dom dx{
	attributes:NameNodeMap
}
```
js会有一个很大的对象来代表我们看到的那个元素

 dom集合
在一个类数组中对象中存储很多dom对象构成一个集合
```javascript
```

### 选取元素


* var el = document.createElement()
* var el = document.getElementById()
* var el = document.querySelector()//ie8


* var el = document.getElementsByClassName()
* var el = document.getElementsByTagName()
* var el = document.getElenemtsByName()//表单元素
* var el = document.querySelectorAll()//ie8
经过这一步我们会得到一个dom元素或者dom集合


###  筛选元素

从一个dom对象开始，根据逻辑关系再去寻找dom对
>父元素
* el.parentNode
* el.parentElement
> 子元素
* el.childNodes
* el.children
* el.firstChild
* el.firstElement
* el.lastChild
* el.lastElement
> 兄弟元素
* el.nextSibling
* el.nextElementSibling

* el.preciousSibling
* el.previousElementSibling






###  操作属性(element)
<div class="a" id="b"></div>
*  el.setAttribute()
*  el.getAttribute()
*  el.removeAttribute()
*  el.hasAttribute()

*  el.ClassName=""
*  el.Id=""
*  el.classList

###  节点操作(node)

* el.appendChild()
* el.removeChild()
* el.insertBefore()
* el.cloneNode()
* el.replaceChild()

###  获取信息(HTMLELEMENT)
* e.offsetTop
* e.offsetLeft
* e.offsetParent//具有定位属性的父元素
* e.offsetWidth
* e.offsetHeight
* e.getBoundingClietRect()//计算元素距离窗口位置
* e.innerHTML
* getComputedStyle(el,null).width//"100px"

###  操作样式

* el.style(读取行内样式的值，设置行内样式的值)

###  get和set在dom对象中的使用

```javascript
var obj = {
a:1,
b:2,
set c (x){ console.log(111)},
get c (){return 5;}
}
```
###  其他


<!-- * 三
* 四

```javascript
var a=12;
var c=function(){
	console.log(1)
} -->