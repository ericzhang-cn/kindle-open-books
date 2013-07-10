这个项目的目的是将网上的一些开放资源转为kindle可用的电子书。

限于很多开放书籍的license，这个项目不包含生成的电子书，只包含相关的生成脚本。

# 关于calibre recipes

[Calibre](http://calibre-ebook.com/)是一个免费的电子书管理工具，可以通过抓取RSS或网页页面内容生成电子书，其中抓取过程可以通过recipe文件（实际是一个Python脚本）自定义。具体recipe文件的编写方式见[文档](http://manual.calibre-ebook.com/news.html)。

calibre-recipes目录下是一些recipe文件。目录如下：

+ AOSABook.recipe - [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)

# 使用方法

## 图形界面模式

1. 安装Calibre。
2. 通过GUI界面调用自定义recipe功能，抓取内容生成电子书，使用方法见[文档](http://manual.calibre-ebook.com/news.html)。

## 命令行模式

1. 安装Calibre。
2. 如果是Mac OS，则需要手工安装Command Line工具，安装方式见[这里](http://manual.calibre-ebook.com/cli/cli-index.html)。
3. 到calibre-recipes目录下执行命令
   
   ```bash
   ebook-convert xxx.recipe xxx.mobi
   ```

   例如在calibre-recipes目录下执行
   
   ```bash
   ebook-convert AOSABook.recipe AOSABook.mobi
   ```

   则可生成AOSABook.mobi。
