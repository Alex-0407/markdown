
![mahua](http://mahua.jser.me/mahua-logo.jpg)

##MaHua是什么?
一个在线编辑markdown文档的编辑器

##MaHua有哪些功能？

* 方便的`导入导出`功能
    *  直接把一个markdown的文本文件拖放到当前这个页面就可以了
    *  导出为一个html格式的文件，样式一点也不会丢失
* 编辑和预览`同步滚动`，所见即所得（右上角设置）
* `VIM快捷键`支持，方便vim党们快速的操作 （右上角设置）
* 强大的`自定义CSS`功能，方便定制自己的展示
* 有数量也有质量的`主题`,编辑器和预览区域
* 完美兼容`Github`的markdown语法
* 预览区域`代码高亮`
* 所有选项自动记忆

##代码
如果你只想高亮语句中的某个函数名或关键字，可以使用 `function_name()` 实现

通常编辑器根据代码片段适配合适的高亮方法，但你也可以用 ``` 包裹一段代码，并指定一种语言

```javascript
  var ihubo = {
    nickName  : "草依山",
    site : "http://jser.me"
  }
```
支持的语言：actionscript, apache, bash, clojure, cmake, coffeescript, cpp, cs, css, d, delphi, django, erlang, go, haskell, html, http, ini, java, javascript, json, lisp, lua, markdown, matlab, nginx, objectivec, perl, php, python, r, ruby, scala, smalltalk, sql, tex, vbscript, xml
也可以使用 4 空格缩进，再贴上代码，实现相同的的效果

    def g(x):
        yield from range(x, 0, -1)
    yield from range(x)
    
 标题

文章内容较多时，可以用标题分段：

标题1
======

标题2
-----

## 大标题 ##
### 小标题 ###

粗斜体

*斜体文本*    _斜体文本_
**粗体文本**    __粗体文本__
***粗斜体文本***    ___粗斜体文本___

链接

常用链接方法

文字链接 [链接名称](http://链接网址)
网址链接 <http://链接网址>

高级链接技巧

这个链接用 1 作为网址变量 [Google][1].
这个链接用 yahoo 作为网址变量 [Yahoo!][yahoo].
然后在文档的结尾为变量赋值（网址）

  [1]: http://www.google.com/
  [yahoo]: http://www.yahoo.com/
  
列表

普通无序列表

- 列表文本前使用 [减号+空格]
+ 列表文本前使用 [加号+空格]
* 列表文本前使用 [星号+空格]

普通有序列表

1. 列表前使用 [数字+空格]
2. 我们会自动帮你添加数字
7. 不用担心数字不对，显示的时候我们会自动把这行的 7 纠正为 3

列表嵌套

1. 列出所有元素：
    - 无序列表元素 A
        1. 元素 A 的有序子列表
    - 前面加四个空格
2. 列表里的多段换行：
    前面必须加四个空格，
    这样换行，整体的格式不会乱
3. 列表里引用：

    > 前面空一行
    > 仍然需要在 >  前面加四个空格

4. 列表里代码段：

    ```
    前面四个空格，之后按代码语法 ``` 书写
    ```

        或者直接空八个，引入代码块

引用

普通引用

> 引用文本前使用 [大于号+空格]
> 折行可以不加，新起一行都要加上哦

引用里嵌套引用

> 最外层引用
> > 多一个 > 嵌套一层引用
> > > 可以嵌套很多层

引用里嵌套列表

> - 这是引用里嵌套的一个列表
> - 还可以有子列表
>     * 子列表需要从 - 之后延后四个空格开始

引用里嵌套代码块

>     同样的，在前面加四个空格形成代码块
>  
> ```
> 或者使用 ``` 形成代码块
> ```

图片

跟链接的方法区别在于前面加了个感叹号 !，这样是不是觉得好记多了呢？

![图片名称](http://图片网址)

当然，你也可以像网址那样对图片网址使用变量

这个链接用 1 作为网址变量 [Google][1].
然后在文档的结尾位变量赋值（网址）

 [1]: http://www.google.com/logo.png
 
 也可以使用 HTML 的图片语法来自定义图片的宽高大小
 
 <img src="htt://example.com/sample.png" width="400" height="100">
 
 换行

如果另起一行，只需在当前行结尾加 2 个空格

在当前行的结尾加 2 个空格  
这行就会新起一行

如果是要起一个新段落，只需要空出一行即可。

分隔符

如果你有写分割线的习惯，可以新起一行输入三个减号-。当前后都有段落时，请空出一行：

前面的段落

---

后面的段落

##联系方式

* 邮件(12345678@qq.com, 把#换成@)
* QQ: 12345678
* 今日头条: [@ionic实战](http://www.toutiao.com/c/user/56196722948/#mid=1559994731399169)
* 简书: [@alex](http://www.jianshu.com/u/6c16640d68d2)
* 知乎： [@alex](https://www.zhihu.com/people/alex-79-60-4/activities)
* 博客园： [@alex](http://www.cnblogs.com/LVBingo)

### 新浪云活动

新浪云平台Sina App Engine(SAE)，是由新浪公司开发和运营的开放云计算平台的核心组成部分，国内第一家公有云计算平台，可以为网站开发者，App开发者提供稳定、快捷、透明、可控的服务化的平台，并且减少开发者的开发和维护成本。

「新浪云福利」1000云豆免费领！低成本、免运维、灵活、安全稳定，轻松应对业务爆发式增长，一起来用吧！ 注册地址：http://t.cn/R5oFIaD


### 最新技术福利

免费视频教程百度云盘链接：

React Native入门  链接: https://pan.baidu.com/s/1qYtryC8

ionic入门  链接: https://pan.baidu.com/s/1i5mKcnF

微信小程序入门  链接: https://pan.baidu.com/s/1o8FGjDw

为了保证连接的可使用性，请关注微信公众号 <font color=red>`全栈弄潮儿`</font>，

React Native入门视频 回复“RN提取码”领取 提取码

ionic入门视频 回复“ionic提取码”领取 提取码

微信小程序入门视频 回复“小程序提取码”领取 提取码


#### 欢迎关注我的微信公众号或头条号`全栈弄潮儿` ，获取更多学习资源及技术文章等

* 微信公众号二维码，扫一扫或者搜索"全栈弄潮儿"即可关注

<img src="https://github.com/Alex-0407/sinacloud-node/blob/master/fullstack-8cm.jpg" width="320px" style="display:inline;">

* 今日头条号二维码，扫一扫即可关注

<img src="https://github.com/Alex-0407/node-demo/blob/master/toutiao.jpg" width="320px" style="display:inline;">
