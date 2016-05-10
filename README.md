1/我是大标题(一级标题),文字下一行加 = ，等号不限制个数
====
我是中标题(二级标题)，文字下一行加 - ，不限制个数
-----
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

文字之间输入即可，换行需要用换行符\<br /> <br />
在文字末尾加两个tab就可以换行   
我是多行文字2   
我是多行文字3  
#####超链接
http://www.baiducom
如果想给文字加链接可以这样[我的博客](http://www.wuleiyang.com "我是提示的文字")    
如果想高亮某段文字或某个字母可以用两个上点号（就是1左侧的键）把文字包起来，for：    
My name is `吴雷洋`,就是这么`酷炫`！
#####插入符号
在这里如果想显示圆点符号需要输入`*`号并加一个空格，如果需要二级或三级，就在*前加一个tab
* 昵称：我是圆点
* 我也是圆点
  * 我是二级圆点
    * 我是三级（？？）如果想结束从属关系，请在我下面空一行

还有这样的`字符包围`结构    
#####字符包围   
>数据结构   
>>树    
>>>二叉树   
>>>>平衡二叉树    
>>>>>满二叉树  

####插入图片
插入图片有多种方法，下面一一列举    
1、叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL    
  `![](http://i1.sinaimg.cn/dy/deco/2013/0329/logo/LOGO_1x.png)`    
  在中括号里添加内容并不会对图片造成任何影响，我推测可能是给编者预留的注释的地方，如果想加鼠标悬停的效果，可以仿照链接的添加方式在后面添加    
  ![新浪微博Logo](http://i1.sinaimg.cn/dy/deco/2013/0329/logo/LOGO_1x.png "我是新浪微博")  
2、还可以加载Github仓库里的图片，格式和上边基本一致，方法如下：  
  `https://github.com / 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片`  
  `![](https://github.com/wuleiyang/learngit/raw/master/Logo/foryou.gif)`  
  暂时没有图片，不展示了  
 3、如果想给图片添加指定链接可以这样：  
`[![baidu]](http://baidu.com)//括弧仔细看格式哦，这里是目标链接`  
`[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"//这里是图片地址`  
[![baidu]](http://baidu.com/)
[baidu]:http://i1.sinaimg.cn/dy/deco/2013/0329/logo/LOGO_1x.png "我是新浪微博"  
####插入代码
 插入代码用1左边、tab上边的键三个分两行将代码包起来，如：  

 ```PHP
 echo "Helo GitHub"
 ```
 ```html
 <html>
 <head>
 <meta charset="utf-8" />
 <title>Demo</title>
 </head>
 <body>
  <p>我是HTML代码</p>
 </body
 </html>
 ```
