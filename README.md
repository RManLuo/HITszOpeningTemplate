# 哈工大深圳开题报告模板

在 [hitesis](https://github.com/dustincys/hithesis/)模板上进行的修改，适配2020/11/3号深圳校区的新模板。

> 参考学校样例：
>
> http://due.hitsz.edu.cn/info/1341/2835.htm
> http://due.hitsz.edu.cn/system/_content/download.jsp?urltype=news.DownloadAttachUrl&owner=1481660265&wbfileid=4626652

## 使用

```
latexmk -xelatex report.tex
```

or

```
xelatex -shell-escape report.tex
bibtex report
xelatex -shell-escape report.tex
xelatex -shell-escape report.tex
```

