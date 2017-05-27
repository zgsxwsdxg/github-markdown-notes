大标题
====


中标题
----

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题  

> 大标题和中标题是分别和一级标题和二级标题对应的。即大标题大小和一级标题相同，中标题大小和二级标题相同

#### 普通文本

这是一段普通的文本，<br>
直接回车不能换行，<br>
要使用\<br>
注意第三行的\<br>前加了反斜杠 \ 。目的就是像其他语言那样实现转义
http://blog.csdn.net/kaitiren/article/details/38513715
#### 单行文本
    使用两个Tab符实现单行文本。
    Hello,大家好，我是果冻虾仁。  
#### 多行文本
    多行文本和单行文本异曲同工，只要在每行行首加两个Tab
    
    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安
    
    
#### 部分文字的高亮
如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 \`  \` 包围起来。注意这不是单引号，而是Tab上方，数字1左边的按键
<br>Thank `You`. Please `Call` Me `Coder`

#### 文字超链接
[来自博客](http://blog.csdn.net/kaitiren/article/details/38513715 "悬停显示")

#### 标题超链接
[标题超链接](#普通文本)

#### 圆点符
要注意的是星号* 后面要有一个空格。否则显示为普通星号。上文的显示效果如图：
* 昵称：果冻虾仁
* 别名：隔壁老王
* 英文名：Jelly  
##### 此外还有二级圆点和三级圆点。就是多加一个Tab
* 编程语言
    * 脚本语言
        * Python  

#### 缩进
> 数据结构
>> 树
>>> 二叉树
>>>> 平衡二叉树
>>>>> 满二叉树  

#### 插入图片
##### 来源于网络的图片
![](http://www.baidu.com/img/bdlogo.gif)

##### GitHub仓库里的图片
有时候我们想显示一个GitHub仓库(或者说项目)里的图片而不是一张其他来源网络图片，因为其他来源的URL很可能会失效。那么如何显示一个GitHub项目里的图片呢？<br>
其实与上面的格式基本一致的，所不同的就是括号里的URL该怎么写。<br>
https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片

##### 给图片加上超链接
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"

##### 插入代码片段
我们需要在代码的上一行和下一行用\`\`\` 标记。\`\`\` 不是三个单引号，而是数字1左边，Tab键上面的键。要实现语法高亮那么只要在 \`\`\` 之后加上你的编程语言即可（忽略大小写）。c++语言可以写成c++也可以是cpp。看代码：
``` java
public static void main(String[] args){} // java
```
``` c
int main(int argc, char*argv[]){} // c
``` 
``` Bash
echo 'Hello,World.' # bash
```
``` cpp
string & operator+(const string& A,const string& B) // cpp
```

##### Emphasis
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet <br>
https://help.github.com/categories/writing-on-github/ <br>
https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/ <br>
https://help.github.com/articles/basic-writing-and-formatting-syntax/#headings <br> 

Use `git status` to list all new or modified files that haven't yet been committed.
Some basic Git commands are:
```
git status
git add
git commit
```
