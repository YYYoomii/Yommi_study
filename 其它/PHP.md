# HTML

~~~shell
# 标签的分类：
1、单标签：<br>,<hr>,<img src="路径" alt="">,<input>,<meta>,<link>
2、双标签：<html>,<body>,<footer>,<title>,<head>,<span>,<div>,<p>,<h1>-<h6>,<a>,<strong>,<center>
# 标签的属性
	各属性之间无先后次序，属性值应该被包含在引号中常用双引号，但是单引号也可以使用。
常见的属性值有：align，size，width，height，href，url，src，type等，属性可以省略（即取省略值）。
//href是Hypertext Reference的缩写
# 标签：
1、标题标签 <hn>(共六个)
2、段落标签 <p></p>
3、换行标签 <br>
4、文本加粗标签<b>或者<strong>
5、文本倾斜<em>或者<i>
6、预格式化标签 <pre>
7、定义水平线的标签 <hr/>
8、<div></div>标签:可以在里面设置颜色
9、<span>
# 列表标签
1、无序列表<ul></ul>
2、有序列表<ol></ol>
3、自定义列表<dl></dl>
# 表格标签
     <table> 
            <tr>用来创建表格中的一行
                <td></td>创建行中的一列
                <td></td>
            </tr>
        </table>
 常用属性：
1) border:设置表格线的宽度（粗细)，单位为像素，n =0为默认值，表示无边框。
2) width:设置表格宽度，取值为像素或相对于窗口的百分比。
3）height:设置表格高度,取值为像素或相对于宽度的百分比。
4) colspan:合并列。colspan = "2"，表示合并同行的相邻两个单元格。
5) rowspan:合并行。rowspan = "2"，表示合并同列的相邻两个单元格。
6）<caption>：它常常作为<table>的第一个子元素出现，作为一个表格的标题，同时显示在表格内容的最前面。（可以在css中设置 caption-side属性，调整标题的位置）。
# 多媒体标签
1、图像标签：<img src="" alt="">，使用该标签可以在当前位置插入图片
	eg：<img src="1.jpg" alt="" width="400px" height="400px">
2、视频标签：<video src="视频文件的路径"></video>
3、链接标签：<a href="" target="" ></a>
	eg：<a href="https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/video">HTML</a
~~~

## CSS

​		CSS (Cascading Style Sheets，层叠样式表）是一种样式表语言，用于描述网页的外观和样式。它定义了页面中元素的外观、布局、颜色、字体等方面的样式。通过使用CSS，可以对HTML元素进行样式化，使网页具有更加吸引人的外观和设计。

~~~shell
# CSS和HTML的区别
CSS（层叠样式表）和HTML（超文本标记语言）是两种不同的技术。HTML提供了标记和结构，而CSS提供了样式和布局。通过将两者结合使用，可以实现对网页的完整控制。
1、分离关注点：
	HTML负责描述页面的结构和内容，而CSS负责描述页面的样式和外观。这种分离的设计原则使得开发者可以更好地管理和维护代码。
2、关联方式：
	HTML和CSS之间通过选择器和属性进行关联。在HTML中，通过指定元素的class或id等属性，可以将特定的样式应用于相应的元素。CSS中使用选择器来选择需要样式化的HTML元素，并使用属性来定义元素的样式。
3、层叠机制：
	CSS中的"Cascade"（层叠）指的是多个样式规则同时作用于同一个元素时，根据优先级和特定的层叠规则来决定最终应用的样式。这种层叠机制允许开发者对相同元素应用不同的样式，并按照一定规则进行组合。
	
//通过使用CSS，可以轻松地改变网页的外观和样式，而无需修改HTML的结构。这种分离的设计模式提供了更好的可维护性、可扩展性和可重用性。同时，CSS还支持响应式设计和媒体查询等功能，使得网页可以根据不同的设备和屏幕尺寸自适应布局和样式。
# 关于标签：
	CSS（层叠样式表）可以应用于 HTML（超文本标记语言）中的各种标签和元素，以实现样式化和外观控制。
~~~



# PHP

## 一、php基础

php：php Hypertxt Preprosessor超文本预处理器，是一种服务器端，跨平台，HTML嵌入式脚本语言。其独特的语法混合了C语言，Java语言，Perl语言的特点。是一种广泛运用于开源的多用途语言。

php主要应用方向：
1、创建动态网站
2、命令行编程

~~~shell
php不区分大小写，推荐写小写
# 环境搭建
PHP本身是一门服务端语言，所以其需要运行在服务端。
# 基础
1、cmd语句：php -S 127.0.0.1:9999
2、jsp、asp、json、js、node.js(可以做后端)区别
3、框架：vue.js(js做交互)、bootstrap、jquery（早期）
4、API：后端的接口（json数据格式返回数据）
5、go语言：Go是Google开发的一种静态强类型、编译型、并发型，并具有垃圾回收功能的编程语言。 
6、代码思维：动静分离
pdd（预编译）
# 关于标签
asp：<% %>
短标签：<? ?> (使用短标签，需要在php.ini中进行配置， short_open_tag = Off)
# jsp、asp、json、js、node.js(可以做后端)区别
1、JSP（JavaServer Pages）：JSP是一种基于Java的服务器端技术，用于创建动态网页。
2、ASP是一种由Microsoft开发的服务器端技术，用于创建动态网页。原始的ASP使用VBScript作为脚本语言，后来发展为ASP.NET，可以使用多种语言（如C#、VB.NET）进行开发。ASP通常与Microsoft的Internet Information Services（IIS）服务器一起使用。
3、Node.js是一个基于JavaScript的服务器端运行环境，用于构建可扩展的网络应用程序。Node.js使用事件驱动、非阻塞I/O模型，使得它能够高效地处理大量并发请求。它采用V8 JavaScript引擎，使得开发者可以使用JavaScript语言进行服务器端开发。Node.js生态系统丰富，具有大量的模块和工具，适用于构建各种类型的应用程序。
~~~

示例

~~~php
<b>hello</b>
<button onclick="alert('hahaha')" style="color: red">Click</button>
~~~



### 1、php常用规则

~~~shell
# php常用规则
1、注释
	1）// #
	2）/* */
2、分隔符：以分号结尾
3、结束符：单独使用php可以省略，不单独使用需要使用？>
# 变量
变量之前放$
1、命名规则：
	变量必须由字母表中的字母开头或由_（下划线）字符开始。 _
	变量名只能包含字符a~z，A~Z，0～9，以及（下划线）
	变量名不能包含空格。如果一个变量名必须由多个单词构成，那么各单词间必须由_（下划线）分隔（如$user_name）
2、可变变量：
	如果一个变量保存的值刚好是另外一个变量的名字，那么可以直接通过访问一个变量得到另外一个变量的值; 在变量前面再多加一个$符号。
	<?php
	$hi = 'hello';
	$$hi = 'world';
	echo "$hi $hello";
	echo "$hi ${$hi}";
3、unset()：销毁变量
4、字符串用单引号会更快，双引号可以解析变量
~~~

### **2、变量的类型**

* 四种标量类型
  * boolen（布尔）
  * integer（整型）
  * float（浮点型）
  * string（字符串）
* 两种符合类型
  * array（数组）
  * object（对象）
* 两种特殊类型
  * resource（资源）：文件、数据库
  * NULL

~~~shell 
1、var_dump()：输出
2、强制转换：可以把一种类型强制转换为另一种类型。
	 隐式转换：
3、类型测试函数：is_xxx
4、array数组和object底层很像
# FastCGI（解析php）：
	FastCGI（Fast Common Gateway Interface）是一种用于扩展服务器端应用程序性能的协议。它是对标准的CGI（Common Gateway Interface）的改进和扩展。
	CGI是一种标准的服务器端接口协议，它定义了Web服务器与应用程序之间的通信方式。通过CGI，Web服务器可以调用外部的可执行程序来处理客户端请求并生成动态内容。每次请求都需要启动一个新的进程或线程来处理，这会导致额外的开销和性能问题。
	FastCGI解决了CGI的性能问题。它通过在Web服务器和应用程序之间建立一个持久的连接，使得应用程序可以长时间运行，不需要重复启动。这样，FastCGI可以更高效地处理多个请求，减少了进程或线程的创建和销毁开销，提高了服务器的性能和响应速度。
# Memcached：
	Memcached是一种高性能的分布式内存对象缓存系统。它被广泛用于加速动态网站和应用程序的数据访问速度，特别是在处理大量并发请求时。Memcached将数据存储在内存中，并通过提供简单的键值对接口来访问和检索数据。
//缓存：redis为什么适合存放缓存
# 常量
1、define('常量名'，常量值)
	const 常量名 = 值；（5.3之后才有的）
2、预定义常量：（系统常量）
	__LINE__：文件的当前行号
	__FILE__：文件的完整路径
	__DIR__：文件目录
	__METHOD__：类方法名
	__class__：类名（php5.0种加入的）
	__namespace__：当前名称空间的名字
# 其它
1、"."用来拼接，如果调用需要用->
2、自增自减：echo $a++,++$a;
3、逻辑运算符：===（三个等号表示类型和值都要相等）
# 三目运算符
	表达式1 ？ 表达式2 ：表达式3（如果表达式1成立，那么执行表达式2，否则执行表达式3；）
~~~



### 3、重要的函数和逻辑语句

#### 1）类型判断的几个函数说明

~~~shell
gettype（）获得数据类型
empty（）判断是否为空【范围更宽】
is_null（）判断是否为null
isset（）判断是否不为空值（和isnull刚好相反）
boolean（）布尔值
# 关于empty
	如果值为 null，false，0，0.0，空字符串 ""，空数组 []，空对象 new stdClass()，或者一个没有任何属性或元素的空对象，则返回 true。
	如果值为其他任何非空值（包括字符串 "0"，空格字符等），则返回 false。
~~~

#### 2）条件语句

~~~php
# if
单独条件
if(){}else{}
多条件
if(){}elseif(){}elseif(){}
# switch
switch(){
  case value1:语句块1;break;
  case value2:语句块2;break;
    ...
  default:语句块；
}
~~~

#### 3）循环

~~~php
# while循环：
while(条件表达式){循环体;}
# do-while循环：
do{}while(条件表达式);
# for循环：
for(初始化;条件表达式;增量){语句块}
# foreach循环：专门针对数组
# 循环控制：
循环控制主要是 continue 和 break
	continue 在某一次循环的过程当中退出循环，并进入到下一次循环
	break 退出循环
~~~

## 二、数组

### 1、基础

~~~shell
1、内置数组：$_server, $_GET, $_COOKIE, $GLOBALS(包含所有), $_FILE, $_REQUEST
	//$GLOBALS 是一个超全局变量，用于在任何作用域中访问和操作全局变量，而 global 关键字用于在函数内部与全局变量进行关联，允许对全局变量进行修改。（参考“三、函数”）
2、print_r(输出数组)：用于打印变量的函数，它可以以可读的形式输出变量的内容，包括数组、对象等复杂数据结构。
# 例子
<php?
 var_dump($_GET)	
 $a=100
 echo $GLOBLS['a'];
# 关联数组(key value)、索引数组(0，1，2)
# 创建数组
1、第一种方式
	$arr[] = 'tom';
	$arr['name']='tom';
 2、第二种方式（只能创建索引数组）
  $arr = ['name','age'];
	$arr = ['name'=>'tom','age'=>'18'];
   echo $arr[0], $arr[1];
  $arr = [['name','age']];
   echo $arr[0], $arr[1];
# 其它
1、count 得到数组的长度
2、list() 是一个语言结构，用于将数组中的值赋给一组变量。它允许你以一种便捷的方式从数组中提取值并赋给多个变量。
3、each() 返回当前键值对，并且指针向后移动一位
4、foreach() 循环遍历数组
~~~

例子：

~~~php
# foreach
$arr = ['name'=>'tom','age'=>'18'];
foreach ($arr as $value){
  echo $value . '<br>';
}
foreach ($arr as $key=>$value){
  echo $key. $value . '<br>';
}
# list
list($var1, $var2, $var3, ...) = $array;
~~~

### 2、数组函数

~~~shell
1、array_keys()
2、in_array()
3、array_key_exist()
4、sort()从小到大
	rsort()从大到小
5、array_slice：取出一段
6、array_merge：拼接（key值唯一）
7、array_pop：将数组中最后的元素弹出
	array_push：将元素压入数组中
~~~

## 三、函数

关键点：function、函数名、参数、函数体和返回值

~~~shell
function 函数名(参数1、参数2...){
	函数体
	return 返回值
}
# 作用域
全局变量：变量可以在普通代码中定义
局部变量：变量也可以在函数内部定义(动态储存变量和静态储存两类，有static就是静态)
1、global声明全局变量：
	global $one,$two;
2、GLOBLAS数组：
	$one=100; $two=1;
	$GLOBALS['two']=$GLOBALS['two']+$GLOBALS['one']
~~~

### 1、函数

~~~shell
# 变量函数
当前有一个变量所保存到值，刚好是一个函数的名字，那么就可以使用 变量() 来充当函数的调用
1、例子
$变量 = 'display';
Function display(){ }
$变量()；
2、call_user_Function, call_user_function_array()等可以接受回调函数作为参数
# 匿名函数
1、例子
变量名=Function(){函数体}；
2、闭包
	闭包，在PHP中，闭包和匿名函数基本同义，当作为闭包是，内部函数如果需要使用外部函数的参数，需要使用关键字use。
3、例子
$innerfunction = function() use($name){echo $name};
~~~



### 2、表单

之前是ajax，异步请求

~~~shell
编写form表单提交POST请求
关于数组 $_GET, $_POST, $_REQUEST
# GET请求
1. form表单
<form method="GET">表单元素</form>
2. a标签
<a href="">
3. location对象的href属性
4. location对象的assign()方法
# POST 请求
<form method="POST">表单元素</form>
复选框提交数据
#重定向：header('location:4.php');
<script type="text/javascript">
	location.href='www.baidu.com';
</script>
~~~

例子

~~~shell
<form method="post" action="1.php">
	username:<input type="text" name="username">
	password:<input type="password" name="123456">
	<input type="button">【<input type="submit">】
</form>
~~~



### 3、文件包含

文件包含：在一个PHP脚本中，去将另外一个文件（PHP）包含进来，去合作完成一件事情。
文件包含的意义：使用被包含文件中的内容，实现代码的共享（重用）

~~~shell
# php文件的包含有四种形式：
include:
include_once:
require:
require_once:
# 语法：
include '文件名'；
include ('文件名字');
# 方式
1、以上方式：是先包含文件，后使用文件中的内容（向上包含）
2、向下包含：先准备内容，然后包含另外的文件，在另外的文件中，使用当前的内容
~~~

## 四、字符串

~~~shell
1、索引访问字符串
2、例子：
$str = 'hello world';
echo $str[0],$str[3],$str[-1],$str[-3];
# 格式化字符串值：
# 1、sprintf
$name = "Alice";
$age = 25;
$formattedString = sprintf("My name is %s and I'm %d years old.", $name, $age);
echo $formattedString;
# 2、{$变量}
$name = "Alice";
$age = 25;
$formattedString = "My name is {$name} and I'm {$age} years old.";
echo $formattedString;
~~~

### 常用的函数

~~~shell
# 常用字符串函数
trim() 去除字符串两端的空格
strtolower() 将大写字母转为小写字母
strtoupper() 将小写字母转为大写字母
nltobr() 将字符串换行符转换为html中换行符 <br>
htmlentities() 将字符转换为html实体
htmlspecialchars() 将一些预定义字符转换为html实体
md5() md5计算
# 其它函数
explode() 按指定字符切割字符串
substr() 从指定位置开始截取字符串
strpos() 判断字符在目标字符串中出现的位置（首次）
strcmp() 比较两个字符str1, str2 串大小，相同为0，str1>str2 1否则 -1
strcasecmp() 比较大小，忽略大小写
strnatcmp() 自然排序法比较两个字符串大小
~~~

## 五、文件处理

~~~shell
# 文件属性相关的函数
file_exists() 判断文件是否存在
filesize() 文件大小
is_readable() 文件是否可读
is_writable() 文件是否可写
is_executable() 文件是否可执行
filectime() 文件创建时间
fileatime() 文件访问时间
filemtime() 文件修改时间
stat() 文件属性
# 目录处理
1、DIRECTORY_SEPARATOR 查看当前系统路径的默认分隔符
2、关于Windows 和 Linux 的路径
	windows 中使用 / 或者 \\ 进行分割
	linux 中使用 / 进行分割
3、basename()：返回当前路径的文件名
4、dirname()：返回文件的路径
5、opendir(）：打开目录
6、readdir()：返回目录名，需要可操作的目录句柄作为参数
7、closedir()：关闭目录，需要可操作的目录句柄作为参数
8、rewinddir()：倒回目录句柄
9、mkdir()：创建目录
10、rmdir()：删除目录
11、unlink()：将目录中的每个文件都删掉
12、copy($srcFile, $toFile)：复制文件
# @mkdir('a')，语句前加@，不显示报错
# 正则表达式（匹配）match(从头匹配)、search(中间)、findall(数组)
一、单个字符
	过滤，为了检索自己想要的东西（匹配）
	import re【re是用于处理正则表达式的】
1、\w(匹配数字、字母、下划线) \d(匹配数字) \s(匹配空白字符) \W \D \S(大写和小写刚好相反) 
	[]匹配[]中的字符
二、多个字符
1、*(匹配0个或多个，直到遇到不能匹配的字符) +(匹配1个或者多个) ？(匹配1个或者0个)
# 例子
1、电话号码过滤：/^(?:\+?86)?1[3-9]\d{9}$/
2、URL验证：/^https?:\/\/[\w.-]+\.[a-zA-Z]{2,6}[\/\w.-]*$/
#flask、django（python框架）
~~~

关于 $_FILES

~~~shell
$_FILES 是一个 PHP 的超全局数组，用于存储通过 HTTP POST 方法上传的文件的相关信息。它是一个关联数组，包含了上传文件的各种属性和临时存储的位置。
当你在 HTML 表单中使用 <input type="file"> 元素进行文件上传时，表单数据会被发送到服务器，而文件数据会被存储在服务器上的临时位置。PHP 将上传的文件的相关信息存储在 $_FILES 数组中，你可以使用该数组来访问和处理上传的文件。
$_FILES 数组中的每个元素都对应一个上传文件字段的信息。通常情况下，一个上传字段包含以下信息：

name：上传文件的原始文件名。
type：上传文件的 MIME 类型。
tmp_name：上传文件的临时存储位置。
error：上传文件时产生的错误代码（如果有错误发生）。
size：上传文件的大小（字节数）。
# 例子：表单
<form action="upload.php" method="post" enctype="multipart/form-data">
  <input type="file" name="fileUpload">
  <input type="submit" value="上传文件">
</form>
# 例子：php
$file = $_FILES['fileUpload'];

if ($file['error'] === UPLOAD_ERR_OK) {
  $filename = $file['name'];
  $tempPath = $file['tmp_name'];
  $fileSize = $file['size'];

  // 处理文件，例如移动到指定目录
  move_uploaded_file($tempPath, 'uploads/' . $filename);

  echo "文件上传成功！";
} else {
  echo "文件上传失败！";
}
~~~



案例：

~~~php
# 把open_door转换成Open_Door
<?php
	function func($s){
  	$arr = explode('_',$s);
  foreach ($arr as $value){
    $new_s .= ucfirst($value);
  }
  return array_map(implode,'',$arr);
  //return call_user_func_array(implode,array('',$arr));
}
echo func('open_door');
~~~



## 六、面向对象

类与对象：

* 类是同属性的一组对象的集合（属性+方法）
* 对象是具体的事物

特点：封装、继承、多态

~~~shell
# 基础
1、定义一个类:class Name{}（名字第一个字母大写）
2、用“->”来访问属性或方法
3、类的实例化使用 “new”
3、属性：
	public：类中和类的外面都可以访问该属性(公有属性)【方法签名的public可以省略，属性前面的public不能省略】
	private：只能在类中访问（私有属性）
	static：（静态属性）
	protected：可以在继承链上访问
4、构造方法：__construct()
5、$this 实例化后的对象
# 例子：
class student{
	public $name;
	public function __construct($name,$age){（使用了方法之后就可以直接在外面给它赋值）
		$this->name=$name;
		$this->age=$age
	}
	public function get_age(){
		return $this->age;（私有属性要这样才能访问）
	}
	public function set_propertty($property, $value){
		$this->$property= $value;
	}
}
$stu1 = new student('tom',18);
$stu1->name= 'tom';
$stu1->set_property('age',20);
var_dump($stu1);
~~~

### 静态

~~~shell
# static 
	类外访问：类名::方法名 类名::属性名
	类内访问：self::属性名 self::方法名
# 在类中还可以用 self 访问
# 例子：
访问静态属性方法：：
class Myclass{
	static $count;
	public function __construct(){
		//Myclass::$count +=1;
		self::$count +=1;
		$this -> num +=1;
	}
}
Myclass::$count=0;
$my1 =new Myclass;(不能这样访问)
echo $my1->count;
var_dump($my1);
# 对象的属性、类的属性
	静态不能用this，直接用类名调用：Myclass::class()
~~~

### 继承 & 克隆

~~~shell
1、继承 extends
2、子类重写父类方法，覆盖父类中的方法
3、子类中调用父类方法，类名::方法名
4、clone：$a2 = clone $a1;（创建的a2与a1没有关系，可以认为是a1的副本）【会自动调用_clone方法】
# 例子：
class A{
	puclic $name;
	puclic $age;
	piclic function __construct(){
		$this->name=$name;
		$this->age=$age;
	}
	public function func(){
	echo "A...";
}
class B extends A{
	public function func(){
		A::func();
	}
}
$b =new B('tom',18);
var_dump($b);
~~~

## 七、数据库

### 1、Mysql

~~~shell
# 连接数据库
$host = '127.0.0.1';
$user = 'root';
$password = 'root';
$dbname ='grade';

$conn = new Mysqli($host, $user, $password, $dbname);
//var_dump($conn);
$sql = 'SELECT * FROM class';
$res = $conn->query($sql);
var_dump($res);
# 浏览器 xdebug/phpinfo
[xdebug] 
zend_extension=php_xdebug.dll 
xdebug.remote_enable = On 
xdebug.remote_handler = dbgp    
xdebug.remote_host= localhost 
xdebug.remote_port = 9000 
xdebug.idekey = PHPSTORM
~~~

### 2、PDO

PDO（PHP Data Objects）是 PHP 的一个数据库访问抽象层，用于在 PHP 中进行数据库操作。它提供了一组统一的接口和方法，使开发者可以与多种不同的数据库系统进行交互，而无需针对特定的数据库使用特定的扩展或库。

~~~shell
<?php
	$dsn = 'mysql:host=127.0.0.1;dbname=grade';
	$user = 'root';
	$password = 'root';
	
	try{
		$pdo = new PDO($dsn, $user, $password);
	}catch(PDOException $e){
		die('连接失败'. $e->getMessage());
	}
	$sql = 'SELECT * FROM classes';
	$pdostmt = $pdo->query($sql);
	//var_dump($pdostmt->fetch(PDO::FETCH_ASSOC));
	var_dump($pdostmt->fetchAll(PDO::FETCH_ASSOC));
~~~

### 3、预编译

SQL命令只向数据库服务器发送一次，参数发生变化，数据库服务器只对命令结构做一次分析，编译一次，多次执行，防止SQL注入。

~~~shell
#sqlite
SQLite是一种嵌入式关系型数据库管理系统（RDBMS）。它是一个零配置、服务器无关的数据库引擎，以库的形式集成到应用程序中，无需单独的服务器进程。
# 关键词
exec：不能执行select语句
prepare：
query：
# 过程：
1、处理没有值的语句成为框架
2、传参数直接执行
写语句-->prepare-->传参（可以加一步绑定值）
# 方法：
参数占位、问号占位
# 例子：
$sql = 'SELECT';
$pdostmt = $pdo->prepare($sql);
$pdostmt->execute(array($_POST[],md5()));
if($pdostmt->rowcount() >0){ 遍历 }//里面要有内容
# 遍历使用 fetchAll和fetch的区别
~~~



## 八、会话控制---cookie

**什么是会话控制：**
面向连接的可靠通信方式，根据会话控制记录，判断用户的登录行为
能够在网站中跟踪用户，处理同一个网站同一个用户在多个页面共享数据的机制

~~~shell
1、设置cookie：setcookie('username','tom',time()+60);
2、var_DUMP($_COOKIE);
3、删除cookie：setcookie('username','',time()-1);
~~~



### 会话控制--session

1、存储位置
2、形式：sessionID 是一个不容易重复且不容易找到规律的32位十六进制数

~~~shell
# 设置
1、php.ini-->session-->PHPSESSID
2、php.ini-->gc_divisor：（1000）定义在每次初始化会话时，启动垃圾回收程序的概率
3、gc_maxlifetime ：（24）超过此参数所指的秒数后，保存的数据将被视为“垃圾”并由垃圾回收程序清理
# session转递方式：
	1、用cookie传递
	2、用URL参数进行传递
# session的声明和使用
# 注册会话变量
# 注销变量与销毁session
	session_destory()
# redis放缓存的原因：有失效的限制
# 设置session
session_start();
$_SESSION['username']='tom';
var_dump($_SESSION);
session_destroy();
~~~



## 九、命名空间、接口

### 1、命名空间

​		命名空间在PHP5.3.0中引入，是一个很重要的工具，其作用是按照一种虚拟的层次结构组织PHP代码，这种层次结构类似操作系统中文件系统的目录结构。现代的PHP组件和框架都放在各自全局唯一的厂商命名空间中，以免与其他厂商使用的常见类名冲突。

~~~shell
【放在php标签后的第一行】namespace app\index\controller
1、规则：首先，是厂商命名空间（厂商命名空间是最顶层命名空间）。后面还有一个子命名空间index。其后依然是一个子命名空间。
命名空间（或子命名空间）的作用是封装和组织相关的PHP类，就像在文件系统中把相关的文件放在同一个目录中一样
2、注意：namespace需要写在PHP脚本的顶部，必须是第一个PHP指令（declare 除外）。不要在namespace前面出现非PHP代码、HTML或空格。
3、魔法方法，获取当前空间的名称
echo __NAMESPACE__;
# 作用
1、避免命名冲突
命名空间可以将相同名称的类、函数和常量封装在不同的命名空间中，防止它们之间的冲突。这在多人协作开发或使用第三方库时特别有用。
2、组织和分组代码
命名空间可以将相关的类、函数和常量组织在一起，使代码更加结构化和可读。它提供了一种逻辑上的分组机制，帮助开发者更好地组织和管理代码。
3、提供更好的可维护性
通过使用命名空间，代码的结构和关系更清晰，易于维护和理解。它提供了一种封装和隔离的机制，使得修改或扩展代码更加方便和安全。
~~~



### 2、接口

​		接口是两个PHP对象之间的契约，接口将代码和依赖进行解耦。简单来讲，使用接口，只需要知道接口实现了什么功能呢，不需要知道接口具体是怎么实现的。

~~~shell
# 抽象类
		抽象类需要使用 abstract 关键字进行修饰，抽象类当中具有抽象方法。由abstract 修饰的方法可称之为抽象方法，抽象方法只有方法名，没有方法体。抽象方法是必须由抽象类的子类进行重写。
abstract function func1()
# 接口
	接口需要使用 interface 进行修饰在接口中只能有抽象方法和常量，常量用 const 进行修饰
	实现接口的类必须使用 implements 关键字
#例子：
interface MyInterface {
    public function method1();
    public function method2($param);
}
class MyClass implements MyInterface {
    public function method1() {
        // 方法1的具体实现}
    public function method2($param) {
        // 方法2的具体实现}
}
# 如何选择
如果你希望定义一组方法的契约，可以使用接口；如果你需要定义一个基础类，并为子类提供共享的行为和方法，可以使用抽象类。

# DocumentStore（非内置）
1、DocunmentStore类：
	这个类的作用是从不同的源收集文本；可以从远程URL读取HTML，可以读取流资源，也可以收集终端命令的输出。
	实现Documentable接口的任何对象都必须提供一个公开的getId（）方法和一个公开的getContent（）方法。
~~~



## 十、安全编码

不要相信任何来自不受自己直接控制的数据源中的数据

安全编码建议是∶过滤输入、验证数据，以及转义输出。

~~~shell
# 过滤输入：
	转义或删除不安全的字符。但是htmlentities()不会转义单双引号，在此时需要设置参数ENT_QUOTES。
1、html：htmlentities函数
	1）不要使用正则表达式函数过滤HTML：preg_replace() 、 preg_replace_all() 和 preg_replace_call back()
2、SQL查询：
3、用户资料信息
4、电子邮件地址、URL编码字符串、整数、浮点数、HTML字符、URL和特定范围内的ASCII字符
# 验证数据：
1、使用 filter_var() 函数，用某个 FILTER_VALIDATE_ * 标志验证用户的输入。
# 转义输出：
1、可以使用 htmlentities() 函数转义输出。第二个参数一定要使用ENT QUOTES，让这个函数转义单引号和双引号。

# 密码
1、password_hash( ) 可以对密码进行哈希，采用的 bcrypt 来计算密码的哈希值
2、bcrypt：
	自动加盐、故意设计的很慢；bcrypt算法会花费大量时间（以秒计）反复处理数据，生成特别安全的哈希值在这个过程中，处理数据的次数叫工作因子（work factor）。 工作因子的值越高，破解密码哈希值所需的时间会成指数倍增长
3、password_verify() 可以用来验证密码的正确性

~~~





## 十一、流（PHP伪协议）

流在PHP 4.3.0中引入，作用是使用统一的方式处理文件、网络和数据压缩等共用同一套函数和用法的操作。简单而言，流是具有流式行为的资源对象。因此，流可以线性读写，或许还能使用 fseek() 函数定位到流中的任何位置。

~~~shell
1、php://file协议：
	使用 file_get_contents() 、fopen() 、fwrite() 和 fclose( ) 函数读写文件系统。因为PHP默认使用的流封装协议是 file://，而这些函数使用的是PHP流。
例子：$fileContent = file_get_contents('php://file?filename=path/to/file');
2、php://filter协议：对数据进行过滤
3、php://input协议：
	可以访问请求的原始数据的只读流, allow_url_include=On 。
2、data://协议（可以执行代码）
# 流封装协议
	流封装协议（Stream Wrapper Protocol）是一种在编程语言中访问各种数据源和资源的统一接口。它通过封装不同的数据源，如文件系统、网络资源、内存等，使得这些数据源可以以统一的方式进行读取和写入操作。
	流封装协议可以用于访问各种数据源，例如：
1）文件系统：可以通过文件系统流封装协议（如 file://）访问本地文件系统中的文件。
2）网络资源：可以通过网络流封装协议（如 http://、ftp://）访问远程服务器上的文件或资源。
3）内存：可以通过内存流封装协议（如 php://memory、php://temp）在内存中创建临时数据流。
4）数据库：可以通过数据库流封装协议（如 mysql://、pgsql://）访问数据库中的数据。
	在PHP中，php:// 是一个特殊的流封装协议前缀，用于访问各种资源和数据源。例如，php://input用于读取来自HTTP请求的原始请求体数据，php://stdout用于写入标准输出等。
~~~

### php的伪协议

~~~shell
# PHP 提供了多种伪协议（Wrapper Protocols），用于访问不同类型的资源。以下是一些常见的 PHP 伪协议：
1. `file://`: 访问本地文件系统中的文件。
2. `http://` 和 `https://`: 通过 HTTP 或 HTTPS 协议访问远程网络资源。
3. `ftp://`: 通过 FTP 协议访问远程 FTP 服务器。
4. `ssh2://`: 通过 SSH2 协议访问远程服务器。
5. `php://`: 访问各种 PHP 的输入/输出流（如标准输入输出、内存缓冲区等）。
6. `data://`: 访问数据 URI，用于直接嵌入数据而不需要网络请求。
7. `compress.zlib://` 和 `compress.bzip2://`: 访问经过 zlib 或 bzip2 压缩的文件。
8. `zip://`: 访问 ZIP 压缩文件中的文件。
9. `phar://`: 访问 PHAR (PHP Archive) 归档文件中的文件。
10. `glob://`: 匹配文件系统中的文件路径模式。
11. `rar://`: 访问 RAR 压缩文件中的文件。
12. `ogg://`: 访问 Ogg 媒体文件中的音频或视频流。
13. `expect://`: 通过 Expect 扩展与其他进程进行交互。
这些伪协议提供了一种统一的语法和接口，使开发人员能够以类似于文件操作的方式访问各种不同类型的资源。请注意，可用的伪协议取决于你的 PHP 配置和已安装的扩展。
~~~



### 例子

~~~shell
# 1
<?php
	include $_GET('file')
~~~

命令执行函数

~~~shell
1、system
2、shell_exec()
3、popen()和
~~~

代码执行函数

防范：把命令写死，而不是任由用户写命令

~~~shell
1、preg_repalce()【正则表达式】
	magic_quotes_gas关闭的情况下才能用
	('/<>php(.*?)'.$_GET['reg'],'\\1','<php>phpinfo()<php>')
2、array_map($_GET['test'],array(0,1,2));
3、assert()
~~~



### **php.ini部分配置（设置完要重启）**

1、安全模式：safe_mode

2、禁用函数：disable_function（黑名单）

3、魔术函数：magic_quotes_gpc（自动加引号进行转义）相当于addslashes

4、包含远程文件

5、可访问目录：open_basedir
	会将PHP所能打开的文件限制在指定的目录下

6、全局变量注册：register_globals
	register_globals 被设置为on时，传递过来的值会被注册为全局变量。从而造成全局变量的
覆盖问题



### 变量覆盖

变量覆盖漏洞通常是使用外来参数替换或初始化程序中原有变量的值

~~~shell
1、extract
2、parse_str
3、import_request_variables()
# 查询字符串解析到变量中
parse_str(name=Peter&age=43);
echo $name."<br>"
echo $age
~~~

# JavaScript

​		javascript是web页面的脚本编程语言，是一种通用的，跨平台的，基于对象和事件驱动的脚本语言。不需要编译，直接嵌入到HTMl页面中。把静态页面转变成支持用户交互响应的动态页面。
​		1995年JavaScript首次出现在Netscape Navigator浏览器上。与PHP类似，javascript也是弱类型语
言。

# 1、基础规则

~~~shell
# JS的特点
1、解释性：不需要编译
2、基于对象：
3、事件驱动：可以直接对用户或客户的输入做出响应，无须经过Web服务程序。它对用户的响应是以事件驱动的方式进行的。比如，按下鼠标按键、移动窗口、选择菜单等都可以视为事件。【依赖于浏览器本身，与操作环境无关】
4、安全性：是一种安全性语言，它不允许访问本地的硬盘，且不能将数据存储到服务器上，不允许对网络文档进行修改和删除，只能通过浏览器实现信息浏览或动态交互。
# 使用JS代码
1、直接在html中嵌入
	<script type="text/javascript">alert(1)</script>
2、外部连接js：使用src包含文件
	<script type="text/javascript" src="demo1.js"></script>
3、写在html里面
	<a href="javascript:alert('hello')">点击</a>【这样写不好】
	<input type="button" value="点击按钮" onclick="alert('hi')">
# 数据类型
1、infinity
2、NaN：not a number
3、undefined
4、查看类型：typeof
# 对象
1、创建对象：
	var 对象名={属性名1：属性值1，属性名1：属性值2，...}
2、prototype属性：
	prototype 属性是JavaScript 中所有函数都有的一个属性。该属性可以向对象中添加属性或方法.可以理解为类似静态属性，在javascript 中，将此称之为原型属性。同时，可以通过 in 来判断实例属性或原型属性
3、通过object自定义对象：
	Object对象是JavaScript中的内部对象，它提供了对象的最基本功能，这些功能构成了所有其他对象的基础。
4、with：
	with 语句用于在访问一个对象的属性或方法时避免重复引用指定对象名。使用with 语句可以简化对象属性调用的层次。
	with(stu){}
# JS内置对象：document
在 JavaScript 中，document 是一个内置对象，代表当前 HTML 文档。它提供了访问和操作 HTML 文档中元素的方法和属性。
1、获取元素【document.getElementById】
	var myElement = document.getElementById('myElementId');
2、修改元素内容【innerHTML】
	var myElement = document.getElementById('myElementId');
	myElement.innerHTML = '新的内容';
3、修改元素样式【style】
	var myElement = document.getElementById('myElementId');
	myElement.style.color = 'red';
4、添加事件监听器【addEventListener()】
	var myButton = document.getElementById('myButtonId');
	myButton.addEventListener('click', function() {
  alert('按钮被点击了！');});
# 数组
	数组也是一种对象，被称为数组对象。因此，在定义数组时，也可以使用构造函数。JavaScript中定义数组的方法有以下几种
1、定义空数组
	var arr = new Array()
2、定义有参数组
	var arr = new Array(value1, value2, value3...)
3、直接定义数组
	var arr = [value1, value2, value3...]
# console.log
console.log(typeof(n))：输出标签类型还有其它值（属性、方法都可以查看）【在控制台查看】
# JS与php的不同
1、0的布尔值
2、作用域：外面定义的变量可以用在函数里面
3、变量：不用$符号
4、对象
# <!DOCTYPE html>
< ! DOCTYPE html >是html5标准网页声明,全称为Document Type HyperText Mark-up Language，意思为文档种类为超文本标记性语言或超文本链接标示语言，现在是这个简洁形式，支持html5标准的主流浏览器都认识这个声明。
~~~

BOM和DOM

* 浏览器对象模型（**B**rowser **O**bject **M**odel (BOM)）。

* 文档对象模型（DOM，Document Object Model）是 HTML 和 XML 文档的编程接口。

~~~shell
# BOM
1、window对象：
	网页中定义的所有对象、变量和函数都以 window 作为其 Global 对象，都可以访问其上定义的parseInt()等全局方法
2、location对象：
	提供了当前窗口中加载文档的信息，以及通常的导航功能。它既是 window 的属性，也是 document 的属性。
# DOM（区分父标签和子标签）
1、Document类型：
	是 JavaScript 中表示文档节点的类型。在浏览器中，文档对象 document 是HTMLDocument 的实例（HTMLDocument 继承 Document），表示整个 HTML 页面。
css
# Ajax
	Ajax和form一样可以提交数据，但是Ajax是异步方式提交。
	Asynchronous JavaScript and XML的缩写，即异步的JavaScript和XML。AJAX是JavaScript、XML、CSS、DOM等多种已有技术的组合，可以实现客户端的异步请求操作，这样可以实现在不需要刷新页面的情况下与服务器进行通信，从而减少了用户的等待时间。
1、XMLHttpRequest
	在AJAX使用的技术中，最核心的技术就是XMLHttpRequest，它是一个具有应用程序接口的JavaScript对象，能够使用超文本传输协议（HTTP）连接一台服务器，
2、属性
3、方法：
1）open()方法
	open()方法进行异步请求
	open(method, url, true)
2）send() 方法
	用于向服务器发送请求
3）setRequestHeader()
	setRequestHeader('header', 'value')
4）abort()
	停止当前请求
	http_request.abort()
5）获取http响应头信息
	http_request.getResponseHeader('Content-Type')
	http_request.getAllResponseHeaders()
~~~

## JSON

​		JSON是一种数据格式，而JS是一种编程语言。JSON用于数据交换和存储，而JS用于创建交互式网页和应用程序。		JSON（JavaScript Object Notation）是一种轻量级的数据交换格式，JSON格式的数据，主要是为了跨平台交流数据用的。

​		但JSON和JavaScript确实存在渊源，可以说这种数据格式是从JavaScript对象中演变出来的，它是JavaScript的一个子集。JSON本身的意思就是JavaScript对象表示法（JavaScript Object Notation），它用严格的JavaScript对象表示法来表示结构化的数据

​		它是一种严格的js对象的格式，JSON的属性名必须有双引号，如果值是字符串，也必须是双引号；
JSON只是一种数据格式（或者叫数据形式），数据格式其实就是一种规范，格式、形式、规范是不能用来存诸数据的。我们不能把以下的对象叫JSON，



~~~shell
# JS和java的区别：
Java 与JavaScript 之间的主要区别： Java 是一种OOP 编程语言，而Java Script 是一种OOP 脚本语言。 Java 创建在虚拟机或浏览器中运行的应用程序，而JavaScript 代码仅在浏览器中运行。 Java 代码需要进行编译，而JavaScript 代码都在文本中。
~~~

~~~shell
header
input-post
使用 json_encode() 将数组转换为 JSON 字符串。
使用 json_decode() 将 JSON 字符串转换为数组。
#python代码
https://www.sonarsource.com/blog/10-unknown-security-pitfalls-for-python/
~~~

## JQuery

jQuery是一个流行的开源JavaScript库，旨在简化JavaScript编程。它提供了简洁而强大的API，用于处理DOM操作、事件处理、动画效果、AJAX交互等常见的前端开发任务。

~~~shell
# JS、jQuery和JSON之间的区别：
JS是一种编程语言，jQuery是JS库，提供了简化了常见任务的功能，旨在简化开发者的编程工作，提供了易于使用的API。而JSON是一种轻量级的数据交换格式，用于将结构化数据以文本形式进行表示和传输
~~~

# Sqlite

SQLite是一种嵌入式关系型数据库管理系统（RDBMS），它提供了轻量级、独立的数据库引擎，无需独立的服务器进程或配置。SQLite以C语言库的形式提供，并在许多编程语言中可使用。

SQLite的主要特点包括：

1. **嵌入式数据库引擎**：SQLite数据库引擎以静态库的形式嵌入到应用程序中，应用程序可以直接访问和管理数据库，无需与独立的数据库服务器进行通信。

2. **无服务器架构**：与传统的数据库管理系统不同，SQLite没有独立的服务器进程。所有的数据库操作都在应用程序的上下文中进行，使得SQLite非常适合嵌入式设备和单用户应用程序。

3. **轻量级和高性能**：SQLite的设计目标之一是提供轻量级的数据库解决方案，它具有小巧的代码库和低内存占用。尽管如此，SQLite仍然具有良好的性能和较高的吞吐量。

4. **零配置和易用性**：使用SQLite不需要进行复杂的数据库配置和管理。创建和连接数据库非常简单，并且支持标准的SQL查询语言。

5. **跨平台支持**：SQLite是跨平台的，可在各种操作系统上使用，包括Windows、macOS、Linux和移动平台如Android和iOS。

SQLite广泛应用于许多领域，特别适合小型项目、移动应用程序和嵌入式设备，其中需要一个简单、快速、易于使用和管理的数据库解决方案。

# MVC

MVC就是一种非常重要的设计模式，分别为模型（Model）、视图（View）和控制器（Controller）。

~~~shell
#View 视图
视图代表用户交互界面，对Web应用来说，可以概括为HTML界面，也可以理解为模板，还可以认为是API的客户端。
#Model 模型
模型就是业务流程/状态的处理及业务规则的制定
#Controller 控制器
控制器的作用可以理解为从用户接收请求，将模型与视图匹配在一起，共同完成用户的请求。
~~~



# Python

~~~shell
# 基础规则
1、可以不用分号
2、拼接不用“.”，而是用“+”
3、序列：
	1）元组：（）内容不能被修改
	2）列表（类似数组）用[]，内容可以修改
	list=['hello',112,['a']]
	print('a' in list)
	3）其它：字符串、范围、字节数组
4、定义变量不用x
5、append、pop、remove、insert、index是对象的方法
	x=list.pop(2)
6、python要用缩进，不用括号
# with
	with语句用于处理一些需要进行资源管理和清理的场景，例如文件操作、网络连接等。它提供了一种上下文管理器的机制，确保资源在使用完毕后被正确释放。
例：with context_expression as target:
# 格式化输出 %d %f %s
name='tom'
age=18
	1）print('name:%s, age:%d'%(name,age))
	2）print(f'name:{name}, age:{age}')
	3）print('name:{1}, age:{0}'.format(name,age))
# 切片：
	print(list[::-1])
# 序列
1、序列用for...in...遍历
	for i in range(2,10,2):
		print(i)
	s='hello'
	for i in s:
		print(i)
# if语句
if ：
elif：
elif：
else：
# 字典
dic={'name':'tom','age':18}
for key in dic:
	print(key)
for key in dic.keys()
	print(key)
for key.value in dic.items()
print(key)
//items
# 集合
# Django
Django是一个高级Python Web框架，它基于MVC架构模式，可以快速开发Web应用程序。
~~~

## 函数

~~~shell
# 语法：
def func()
	return 'a'
# pip 爬虫
pip install requests -i http://pypi.douban.com/simple
# 端口扫描
1、模块：socket
2、导入模块：import socket
# 线程和进程
if __name__ == '__main__':
    worker1()
    worker1()
# 消息队列（应用于线程）
Q=queue.queue()
##########################
import socket
udp=socket.socket(socket.AF_INET,socket.SOCK_DGRAM)
udp.bind(('',8080))
udp.sendto('你好'.encode('gbk'),('127.0.0.1',8081))
data=udp.recvfrom(1024)
print(data[0].decode('gbk'))

~~~

python链接：https://www.sonarsource.com/blog/10-unknown-security-pitfalls-for-python/



## spider

~~~shell
# urllib、requests、BS4（beautifulsoup）解析
# requests、bs4、re
# scrapy
pip install bs4 -i https:pypi.douban.com/simple
~~~



~~~shell
# res.text 解析文本 res.content针对图片或者
import requests
res.encoding='utf8'
# 设置编码：res.encoding =res.apparent_encoding
print(res.srarus_code)
print(res.headers)
res=requests.get('http://www.baidu.com')
print(res.text)
~~~

例子：下载图片

~~~shell
url ='图片链接'
res=requests.get(url)
with open('a.png',wb) as f:
	f.write(res.content)
# 链接：

~~~

提取

~~~python
# 链接
https://beautifulsoup.readthedocs.io/zh_CN/v4.4.0/
# 例子
from bs4 import BeautifulSoup
import requests

res = requests.get('http://www.baidu.com')【res = requests.get('http://www.baidu.com')，verify=False】
res.encoding = res.apparent_encoding
html = res.text

soup = BeautifulSoup(html,'html.parser')
print(soup.title.string)
print(soup.title.get_text)
print(soup.find(id='wrapper'))
print(soup.find('a',{'class':'mnav'}))
a_list = soup.find_all('a')【所有的a标签】
print([a["href"] for a in a_list])【a标签的某个属性】
# 爬虫练习
https://ssr1.scrape.center
max hackbar
# json_dumps 字典->json数据 json_loads 相反
~~~

















