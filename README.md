# get_douban_albums

> - Two gogerious ladies inspired me to make this tiny project.
> - I made two part of them: one is for personal Douban users' requests, initiated as the basic version. The other one is to seek general celebries, such as Aragaki Yui that I have just mentioned her. (1/2) :)
>- THIS IS MY FIRST PYTHON PROJECT WITH ORIGINAL THOUGHTS.
> -  There will be an important function to fulfill my <Data Analyst> style, also bugs to fix and revise codes to be pythonic.
- 『get_doubanuser.py』: an original version, it may have many redundant codes, can only work if you input an acurate personal ID.

- 『get_doubancelebrity.py』: trying to make it better.

- 『get_doubancelebrity -V1.2版.exe』: you are welcome to download and test it on your Windows computer, do not foget to issue if you find bugs. XieXie!

# 自动爬取并下载豆瓣相册的照片
> 1. 实现搜索功能
> 2. 判断输入错误，连接错误；判断有无收录和相册
> 3. 无图片、单页和多页均可分辨
> 4. 已实现完美提取info和intro
> 5. 遗留小彩蛋：如果A无图片时，则下一查找B的图片会直接存在A这个人名下
> 6. (TODO)展现复杂交互：明星关系图-通过合作次数
- 一个简单的爬虫脚本
- 通过姓名检索，可爬取豆瓣用户(get_doubanuser.py)或者明星(get_doubancelebrity.py)的照片，并下载至本地同目录Douban文件夹下
- 内置使用说明
（写于2017年的旧作，目前可能存在bug）

![](1.png) 

![](2.png)
