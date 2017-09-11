#  链接、图片、引用、代码块的使用规范

## 链接demo
### 内嵌式链接：

- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：  [第一节课](The_first_try.md)
- 内部链接2，链接本文件的其他部分： [代码块](Second_try.md#代码块demo)

### 引用式链接：

- 外部链接：[百度]
- 外部链接：[百度][baidu]
- 内部链接1，链接仓库的其他文件：  [第一节课]
- 内部链接2，链接本文件的其他部分： [代码块]


## 图片demo
- 图片的markdown语法:  
    ![alt](url text)
- 外部图片demo：  
![百度图片](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png  "百度图片")  
- 仓库内的图片：  
![](image/baidu.png)     

## 引用demo  
> 这是一个引用。  

--出自《》

多次引用：  
>>> 这是一个引用。

## 代码块demo  
- 行内代码：  
我们的文字中间有一行代码`var a=10;`。

- 块式代码：  
```javascript
var a=10;
console.log();
```


<!--- 下面是本文档的链接  -->

[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[第一节课]: The_first_try.md
[代码块]: Second_try.md#代码块demo