# LATEX 2COLUMN MASTER
Latexでタイトル部分も含めて2段組みの課題レポート用テンプレートです。

## 使い方
```
git clone git@github.com:Jzurde/latex_2row_master.git report
```
でクローンしたフォルダ`report`内の`report.tex`を編集しコンパイルします。

### 名前なしバージョン
名前や学籍番号を記載せずにレポートを作成し、提出するように求められた場合があります。その場合は`no_name`ブランチにある、名前無しバージョンを用います。

クローン後に
```
git fetch origin no_name
git checkout no_name
```