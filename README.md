This project is created to convert open source materials to kindle supported format (`.mobi`)

The conversion is limited to open source licensed books. This project does not include any generated `.mobi` files and only includes the `.recipe` file for Calibre.

# About calibre recipes

[Calibre](http://calibre-ebook.com/) is a free electronic book management tool. It allows the generation of e-book through scraping RSS or HTML contents. It can be done through a Calibre recipe (in Python). For more details of Calibre recipe kindly refer to [Calibre Manual](http://manual.calibre-ebook.com/news.html)

List of Recipes in `calibre-recipes` Folder

## English

+ AOSABook.recipe - [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)
+ Android_Studio_Development_Essentials.recipe - [Android Studio Development Essentials](http://www.techotopia.com/index.php/Android_Studio_Development_Essentials)
+ Computer_Science_from_the_Bottom_Up.recipe - [Computer Science from the Bottom Up](http://www.bottomupcs.com/index.html)
+ CS183_Peter_Thiel.recipe - [Notes Essays—Peter Thiel’s CS183: Startup](http://blakemasters.com/peter-thiels-cs183-startup)
+ Designing_Evolvable_Web_APIs_with_ASP_NET.recipe - [Designing Evolvable Web APIs with ASP.NET](http://chimera.labs.oreilly.com/books/1234000001708)
+ Dive_Into_Python_3.recipe - [Dive Into Python 3](http://www.diveintopython3.net/)
+ Explore_Flask.recipe - [Explore Flask](http://exploreflask.com/)
+ Forecasting_Principles_and_Practice.recipe - [Forecasting Principles and Practice](http://otexts.com/fpp/)
+ Git_Pocket_Guide.recipe - [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561)
+ High_Performance_Browser_Networking.recipe - [High Performance Browser Networking](http://chimera.labs.oreilly.com/books/1230000000545/index.html)
+ House_Transcripts.recipe - [House Transcripts](http://clinic-duty.livejournal.com/12225.html)
+ Interactive_Data_Visualization_for_the_Web.recipe - [Interactive Data Visualization for the Web](http://chimera.labs.oreilly.com/books/1230000000345)
+ Introduction_to_Linux.recipe - [Introduction to Linux](http://tldp.org/LDP/intro-linux/html/)
+ Learn_Python_the_Hard_Way.recipe - [Learn Python The Hard Way, 3rd Edition](http://learnpythonthehardway.org/book/)
+ Learn_Vimscript_the_Hard_Way.recipe - [Learn Vimscript the Hard Way](http://learnvimscriptthehardway.stevelosh.com/)
+ Mastering_Perl.recipe - [Mastering Perl](http://chimera.labs.oreilly.com/books/1234000001527)
+ Programming_JavaScript_Applications.recipe - [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262)
+ Python_Cookbook.recipe - [Python Cookbook](http://chimera.labs.oreilly.com/books/1230000000393)
+ SICP.recipe - [Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/full-text/book/book.html)
+ Test_Driven_Web_Development_with_Python.recipe - [Test-Driven Web Development with Python](http://chimera.labs.oreilly.com/books/1234000000754)
+ The_Definitive_Guide_to_Yii_2.0.recipe - [The Definitive Guide to Yii 2.0](http://www.yiiframework.com/doc-2.0/guide-index.html)
+ Tutorials_about_Development_for_Android.recipe - [Tutorials about Development for Android](http://www.vogella.com/tutorials/android.html)

## Simplified Chinese

+ A_Mathematical_Theory_of_Communication.recipe - [通信的数学理论](http://www.ituring.com.cn/minibook/611)
+ Android_Training_Course_In_Chinese.recipe - [Android官方培训课程中文版](http://hukai.me/android-training-course-in-chinese/)
+ AngularJS_Tutorial_Cn.recipe - [AngularJS入门教程](http://www.ituring.com.cn/minibook/303)
+ Git_Community_Book.recipe - [Git Community Book 中文版](http://gitbook.liuhui998.com/)
+ Pro_Git_ZH.recipe - [Pro Git 简体中文版](http://iissnan.com/progit/)

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

2. Execute the following command in `calibre-recipes` folder

   ```bash
   ebook-convert xxx.recipe xxx.mobi
   ```

   For example

   ```bash
   ebook-convert AOSABook.recipe AOSABook.mobi
   ```

   It will generate `AOSABook.mobi` in the same folder.
