# javascript 概述

## 程序语言

* 基础逻辑处理部分

  *变量 数据类型     (数据存储)
  *分支和循环运算符  (逻辑操作)
  *函数(对语言的扩展)

  ### 变量类型
 ```javascript
 	var vr=1;          //num
 	var vr=1.2;        //num
 	var vr="11";       //string
 	var vr="abc";      //string
 	var vr=null;       //null
 	var vr=true;		//Boolean
 	var vr=undefined;  //undefined
 	var vr=[1,2,3]     //Array
 	var vr={a:1,b:2}   //object
 	var vr=function(){}//function
```
 ### 运算符
	+ - * / %
	===  !==   <   >  <=  >=  
	&&   ||   !

 ### 分支语句
 ```javascript
	if ()
	if()else()
	if()else if()else if()
	swith(x)(
		case1:
		break;
		case2:
		break;
		default:
		break
		)

 	
 	for(var i=0;i<10;i++){
 	alert(i);
 	}

 	var aa=[1,2,3,4];
 	for(var i in aa){
 	 alert(i);
 	}

 	while(var i=0;i=10;1++){
 	alert(i);
 	}

 	do{

 	}while()
 	```
 ### 函数
 	function xx(){

 	}
 	var fn=function(x1,x2){
		//arguments
 	}

 	fn(a,c)
 	```
 ### 函数的常用方法
 ### 字符串中的 常用方法
 ### 函数对象中的方法
 ### 对象的增删改查 原型链
 ### 数字对象身上的方法 toFixed()
 ### Math对象身上的方法
 	(以上需常回顾)
 	function A(c){
 	 this.x=c;
 	}
 	A.prototype.console=function(){
 		console.log(this.x)
 	}

## 针对特定用途的部分
> 当js来浏览器运行的那一刻
> 浏览器会创建一个window对象
> window对象中很多属性和方法
> 这些属性和方法不用加window.就可以使用
	
	dom对象
	dom集合

### 选取元素

* var el=document.getElementById("") 返回拥有指定id名的一个对象引用
* var el=document.getElementsClassName("")返回拥有指定类名的对象的集合 存在兼容性问题 函数 getclass
* var el=document.getElementsTagName("")
返回拥有指定标签名的对象的集合


### 筛选元素
nextSibling
*el.parentNode
*el.childNodes
*el.childNode
*el.firstChild
*el.lastChild
nextSibling


### 操作样式
el.style.color='red' 只能对行内样式进行获取 设置
*el.className="one"
兼容性问题获取 函数getstyle
*curren
*get



###获取位置信息
el.clientX
el.clientY
el.screenX
el.clientHeight
el.clientWidth
el.clientLeft
el.clientTop
el.getEventLeft
el.getEventTop

兼容性问题
el.layerX
el.layerY
offsetHeight
offsetWidth
offsetLeft
offsetTop

scrollHeight
scrollWidth
scrollLeft
scrollTop




### 操作属性
el.style
el.className
el.id

el.title
el.tagName
<img><a>
el.src
el.name



### 节点操作
createElement
appendChilds
insertBefore
removeChild
replaceChild
cloneNode
nodeName
nodeValue
nodeType


### 获取元素信息
获取内容
innerHTML
innerText

textContent

* 三
* 四

### 声明

```javascript
var a=12;
var b=13;
var c=function(){
	alert(3);
}
```