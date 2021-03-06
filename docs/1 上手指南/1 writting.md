Title: 写作规则
url: basic-writting

## 基本规则

- 文件名即文章的标题
- 文件内容，即文章正文  

## 插入图片

在FarBox Editor中，你只需要把图片拖入文本区域就可以了。

如果需要手工插入，格式如下：

    ![图片不显示时的文本](/图片的/地址/中间不能有空格.jpg)

*注: 这是[MarkDown](markdown)的语法。*

## 文章类型支持的后缀名

文章的文件名，其后缀支持.txt .md .markdown .mk四种格式。


## 额外属性

> FarBox使用统一的[配置语法](syntax-of-configs)来实现文档的属性扩展, 下面将对一些常用的属性做简单介绍。

### 修改文章的发表时间

在文章的第一行进行声明，格式如下

```
Date: 2012-10-25 12:22

然后开始写正文...
```

### 修改文章的标题

在文章的第一行进行声明，格式如下

```
Title: 文章标题
Date: 2012-10-25 12:22

然后开始写正文...
```

### Status

这个是表示文章的状态的，默认的是`public`。日志列表内输出的都是`public`属性的文章。

### Tags
声明`Tags`，可以给文章增加标签。
```
Tags: Tag1 Tag2
Tags: Words Toghter, Words2 
```
如上所示，如果标签中没有连词的，直接使用空格；如果有连词的话，使用英文状态下的`,`进行分割即可。

### 更多

这里仅对主要的几个属性进行了说明，如果需要了解更多，请访问[>日志的属性](post-configs#item-3-3)

