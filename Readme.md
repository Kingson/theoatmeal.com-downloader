Python Script to download all comics from theoatmeal.com

It downloads each comic to seperate folder "OatmealComics/ComicName" where ComicName is the name of the comic.
It DOES NOT download comics which are already downloaded, incase you run the script again.

Usage is as follows:

Just run the python script. No input is taken from the user.
Requires BeautifulSoup to run.


For any queries, please drop a line to manojmj92@gmail.com
Thanks!

------------------------------------------------ 华丽的分割线 ------------------------------------------------------
### Description

   在伯乐在线上偶然看到了这篇文章《你所写过的最好的Python脚本是什么？》(<http://blog.jobbole.com/75244/>)，对于其中的theoatmeal.com
网站漫画下载器比较感兴趣，所以就fork了一把，结果由于众所周知的原因，运行会报timeout错误。为了能够顺利下载，我对脚本小小的改造了一番，以适应
我大天朝的奇葩网络。

### Change Log

1. 使用requests模块，因为我对urllib不太熟悉
2. 加入proxy处理
3. 修改若干PEP8错误
4. 修改文件存储目录，原脚本将下载的文件目录放在和脚本所在的上一目录，现修改为和脚本同一目录下

### Usage

1. 你需要安装一个代理工具，例如Goagent，Wallproxy等
2. 你需要安装BeautifulSoup4，安装方法：pip install beautifulsoup4

### OK，现在你可以愉快的从theoatmeal(<http://theoatmeal.com/>)上下载漫画了。