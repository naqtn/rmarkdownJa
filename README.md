# rmarkdownJa

A R-language package providing Japanese-aware R Markdown template(s).

This package just provides R Markdown template(s) file for writing with Japanese language.
The template consists of YAML header, first chunk for setting up and example contents.

---
このパッケージは、
Windows 環境下での PDF 生成で日本語文字を問題なく扱う R Markdown 設定を、
R Studio の新規ファイル作成で選択できるテンプレートとして提供します。

わざわざパッケージで提供するようなものでもないのですが、
R パッケージ作成の練習がてら作成してみました。
[テンプレートファイル](https://raw.githubusercontent.com/naqtn/rmarkdownJa/master/inst/rmarkdown/templates/ja_pdf_article/skeleton/skeleton.Rmd)
だけをお手元にコピーして使っていただいてもかまいません。


## パッケージとして R Studio に導入する手順

次の操作を R Studio の console で行ってください。

    install.packages("devtools")
    library("devtools")
    devtools::install_github("naqtn/rmarkdownJa")




