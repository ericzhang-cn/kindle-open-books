This project is created to convert open source materials to kindle supported format (`.mobi`)

The conversion is limited to open source licensed books. This project does not include any generated `.mobi` files and only includes the `.recipe` file for Calibre.

# About calibre recipes

[Calibre](http://calibre-ebook.com/) is a free electronic book management tool. It allows the generation of e-book through scraping RSS or HTML contents. It can be done through a Calibre recipe (in Python). For more details of Calibre recipe kindly refer to [Calibre Manual](http://manual.calibre-ebook.com/news.html)

List of Recipes in `calibre-recipes` Folder

+ AOSABook.recipe - [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)
+ High\_Performance\_Browser\_Networking.recipe - [High Performance Browser Networking](http://chimera.labs.oreilly.com/books/1230000000545/index.html)
+ A\_Mathematical\_Theory\_of\_Communication.recipe - [通信的数学理论](http://www.ituring.com.cn/minibook/611)
+ SICP.recipe - [Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/full-text/book/book.html)
+ AngularJS\_Tutorial\_Cn.recipe - [AngularJS入门教程](http://www.ituring.com.cn/minibook/303)
+ Forecasting\_Principles\_and\_Practice.recipe - [Forecasting Principles and Practice](http://otexts.com/fpp/)
+ Computer\_Science\_from\_the\_Bottom\_Up.recipe - [Computer Science from the Bottom Up](http://www.bottomupcs.com/index.html)
+ Git\_Pocket\_Guide.recipe - [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561)
+ Programming\_JavaScript\_Applications.recipe - [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262)
+ Designing\_Evolvable\_Web\_APIs\_with\_ASP\_NET - [Designing Evolvable Web APIs with ASP.NET](http://chimera.labs.oreilly.com/books/1234000001708)
+ Test\_Driven\_Web\_Development\_with\_Python - [Test-Driven Web Development with Python](http://chimera.labs.oreilly.com/books/1234000000754)
+ Mastering\_Perl.recipe - [Mastering Perl](http://chimera.labs.oreilly.com/books/1234000001527)

# Usage

## GUI

1. Install Calibre [Download](http://calibre-ebook.com/download)
2. Go to `Fetch news`, `Load recipe from file` to add your recipe.
3. Go to `Fetch news`, `Schedule news download`, `Custom`, select the recipe added in step 1 and click `Download Now`
4. For more details, kindly refer to [Calibre Manual](http://manual.calibre-ebook.com/news.html)

## Terminal

1. Install Calibre

   * Archlinux

   ```bash
   pacman -S calibre
   ```

   * Debian/Ubuntu

   ```bash
   apt-get install calibre
   ```

   * RedHat/Fedora/CentOS

   ```bash
   yum -y install calibre
   ```

   * Mac OSX - Requires [Command Line Tool] (http://manual.calibre-ebook.com/cli/cli-index.html)。

3. Execute the following command in `calibre-recipes` folder
   
   ```bash
   ebook-convert xxx.recipe xxx.mobi
   ```

   For example
   
   ```bash
   ebook-convert AOSABook.recipe AOSABook.mobi
   ```

   It will generate `AOSABook.mobi` in the same folder.
