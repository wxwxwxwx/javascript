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

dom对象  dom集合

### 选取元素

* var el = document.getElementById()
* var el = document.getElementsByClassName()
* var el = document.getElementsByTagName()
* var el = document.getElenemtsByName()

###  筛选元素

* el.parentNode
* el.childsNode
* el.firseChild
* el.lastChild
* el.nextSibling
* el.

###  操作样式

* el.style


###  获取位置信息

* el.current("attr",null).attr
* el.getComputedStyle()
* e.screenX
* e.scrrenY
* e.layerX
* e.layerY
* e.offsetTop
* e.offsetY
* document.documentElement.clientX
* document.documentElement.clientY

###  操作属性
* el.style.ClassName=""
* el.style.Id=""
*  e.style.widht
*  e.style.height
*  e.style.src
*  e.style.title
*  e.style.href
*  e.style.margin
*  e.style.padding
*  e.style.position
*  e.style.border


###  节点操作

* el.
* el.ValueNode
* el.TypeNode

###  其他


<!-- * 三
* 四

```javascript
var a=12;
var c=function(){
	console.log(1)
} -->