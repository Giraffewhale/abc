# TA class for Markdown and R Markdown
Jingyu He
WISE
# A Brief Introduction of Markdown
>Markdown: Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email. 


In the course, you are required to use Markdown/R markdown to write your homework.

Markdown Online Programming:
+ [dillinger](https://dillinger.io/ )
+ [stackedit](https://stackedit.io/editor)

Markdown Local Programming:
+ Windows : MarkdownPad. Download from (http://markdownpad.com)
+ Mac: Mou. Download from (http://25.io/mou)

# Markdown Grammar
1. Headers. Use "#" to distinguish different titles. n"#" means the nth header. example:#hello world!
```sh
# hello world!
## hello world!
### hello world!
```
- # hello world!
- ## hello World!
- ### hello world!

2. Emphasis. we use different symbol and symbol combination to emphasize words , sentences or paragraphs. example:
```sh
**Bold** 
__Bold__
*ilatic*
_ilatic_   
~~delete~~
UP~down~
^UP^down
==highlight==
```
- **Bold** 
- __Bold__
- *ilatic*
- _ilatic_   
- ~~delete~~
- UP~down~
- ^UP^down
- ==highlight== 

3. Enter: double enter

4. Ordered list: 
```sh
use "number"+"\."
1.hello world
2.hello world 
3.hello world
```

5. Unordered list:
```sh
only use"+" or "-"
+ hello
+ world
+ 
```
+ hello
+ world
+ 
6. Citation: 
```sh
use ">" and ">>"
> hello world!
>> hello world!
```
- > hello world!
- >> hello world!

7. Paragraph: A paragraph is composed of one or more consecutive text lines,
It needs more than one blank line before and after the display (which looks like empty)

8. Linkages: insert webpage links.
```sh
+ this is [baidu](https://www.baidu.com/)
+ <https:www.baidu.com>
```
+ this is [baidu](https://www.baidu.com/)
+ <https:www.baidu.com>

9. Pics: you can insert pictures from the Internet or your own pc. Example:"!"+"[name]"+"(links)"
```sh
![cz](http://img4.duitang.com/uploads/item/201508/19/20150819131018_vYPyR.thumb.224_0.png)
```
![cz](http://img4.duitang.com/uploads/item/201508/19/20150819131018_vYPyR.thumb.224_0.png)
Tips: if you use online markdown programming, it's more convenient to insert online pics. Upload your local pics via Github or Weibo.
- step 1: create a new repositories
![show4](https://raw.githubusercontent.com/Giraffewhale/abc/master/show4.png)
- step 2: upload your local pics to github
![show1](https://raw.githubusercontent.com/Giraffewhale/abc/master/show1.png)

![show2](https://raw.githubusercontent.com/Giraffewhale/abc/master/show2.png)

![show3](https://raw.githubusercontent.com/Giraffewhale/abc/master/show3.png)

- step 3: copy the path of the pic and insert into your markdown
![show5](https://raw.githubusercontent.com/Giraffewhale/abc/master/show5.png)
**Done!**


 
10. Math grammar:based on Latex Grammar
-[math](https://github.com/Giraffewhale/abc/blob/master/TA_class_for_math_formula_writing.pdf)
-[cheatsheet](http://blog.csdn.net/zdk930519/article/details/54137476)

 
11. R markdown
- R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS. 
download R from [R-project](https://www.r-project.org/)
download R studio [Rstudio](https://www.rstudio.com/)
Install CTex for Windows [Ctex](http://www.ctex.org/HomePage)
Install mactex for Mac [mactex](http://www.tug.org/mactex/)
- Use Rstudio to write R markdown
1. Open your Rstudio->New Project->New Directory(or Existing Directory)
2. open a new R markdown 
![show6](https://raw.githubusercontent.com/Giraffewhale/abc/master/show6.PNG)
![show7](https://raw.githubusercontent.com/Giraffewhale/abc/master/show7.PNG)
3. choose the default markdown output format
![show8](https://raw.githubusercontent.com/Giraffewhale/abc/master/show8.PNG)
4. start write your first R markdown
![show9](https://raw.githubusercontent.com/Giraffewhale/abc/master/show9.PNG)
5. Export your masterpieces!
![show10](https://raw.githubusercontent.com/Giraffewhale/abc/master/show10.PNG)
- R markdown Grammar: similar to Latex Grammar.
- Insert pics from Internet
- Insert pics from local pc: copy the location of your picture and paste, eg."C:\Users\jy\Pictures\Camera Roll"

==**wait!**== 

```sh
![show1](C:\\Users\\jy\\Pictures\\Camera Roll\\show1.png)
![show1](C:/Users/jy/Pictures/Camera Roll/show1.png)
```
