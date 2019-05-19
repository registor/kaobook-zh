# kaobook-zh

[![Travis build](https://travis-ci.org/ustctug/ustcthesis.svg?branch=master)](https://travis-ci.org/ustctug/ustcthesis)
[![Github downloads](https://img.shields.io/github/downloads/ustctug/ustcthesis/total.svg)](https://github.com/ustctug/ustcthesis/releases)
[![GitHub release](https://img.shields.io/github/release/ustctug/ustcthesis/all.svg)](https://github.com/ustctug/ustcthesis/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/ustctug/ustcthesis/latest.svg)](https://github.com/ustctug/ustcthesis/commits/master)

这里CTeX/LaTeX群管理员（312439151，hello）制作了一个`kaobook`“美美的书籍LaTeX模板”汉化版本的样式(http://www.latexstudio.net/archives/51683.html)，这样整个模板的适配性好了很多。采用的字体是思源字体，希望大家独立下载。这一模板非常适合我们的图书和报告的模板，其边注的设计这次进行了更新和完善，如果有英文的书籍是非常不错的选择，有喜欢的用户可以下载试用起来。

Happy LaTeXing！~

注意：

1. 本文档要求 TeXLive、MacTeX、MikTeX 不低于 2018 年的发行版，并且尽可能升级到最新。

3. **不支持** [CTeX 套装](http://www.ctex.org/CTeXDownload)。


## 编译文档

- 编译示例文档 `main.pdf`：
1. 支持minted代码排版宏包
   ```
   latexmk -xelatex -shell-escape main.tex
   ```
2. 不支持minted代码排版宏包
   ```
   latexmk -xelatex main.tex
   ```
3. 在与`main.tex` 同级目录下存在`.latexmkrc` 脚本文件的情况下，执行：
   ```
   latexmk
   ```
- 如需清理论文编译过程中的临时文件，可以：
   ```
   latexmk -c
   ```

## 反馈问题

如果发现代码有问题，请按照以下步骤操作：

1. 将 TeX 发行版和宏包升级到最新，并且将模板升级到 Github 上最新版本，
查看问题是否已经修复；
2. 在 [GitHub Issues](https://github.com/registor/csv2latextab/issues)
中搜索该问题的关键词；
3. 在 [GitHub Issues](https://github.com/registor/csv2latextab/issues)
中提出新 issue，并回答以下问题：
    - 使用了什么版本的 TeX Live / MacTeX / MikTeX ？
    - 具体的问题是什么？
    - 正确的结果应该是什么样的？
    - 是否应该附上相关源码或者截图？
4. 联系作者：西北农林科技大学信息工程学院耿楠

## 字体下载

- [Google思源字体](https://github.com/googlefonts/noto-cjk)

