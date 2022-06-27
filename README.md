# 🦎的技術筆記專區
網站連結：[🦎的技術筆記專區](https://htlin222.github.io/vimwiki/)

# 本網站是如何做的？
* 請先到 [mkdoc](https://github.com/htlin222) 參考裡面的教學說明，如果看不太懂，可以參考下面的中文說明
* 要安裝python，然後以`pip install mkdocs-material`安裝必要的套件
* 開好一個資料夾，在CLI中輸入`mkdocs new .`
* 系統將自動產生一個叫`docs`的資料夾、跟`mkdocs.yml`這個檔案
* 打開`mkdocs.yml`編輯以下內容
```yml
theme:
  name: material
```
* 在CLI中輸入`mkdocs serve`就可以在localhost中預覽你的網站
*
