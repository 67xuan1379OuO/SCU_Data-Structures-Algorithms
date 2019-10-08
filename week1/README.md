README
===========================
測試並展示書寫README時的各種markdown語法。此語法稱為`GitHub Flavored Markdown`，簡稱`GFM`。除了README外，issues和wiki均支持markdown語法。

## 目錄
* [橫線/分隔線](#橫線/分隔線)
* [標題Headers](#標題)
* [文本](#文本)
    * [普通文本](#普通文本)
    * [單行文本](#單行文本)
    * [文字強調](#文字強調)
    * [換行](#換行)
    * [斜體/粗體/刪除線](#斜體/粗體/刪除線)
* [圖片](#圖片)
    * 來源於網路之圖片
    * GitHub中的圖片
* [連結](#連結) 
    * 文字超連結
        *  連結外部URL
        *  連結GitHub裡的URL
    *  錨點
    * [圖片連結](#圖片連結)
* [列表](#列表)
    * 無分層列表
    * 有分層列表
    * 帶選框之列表
* [引用](#引用)
* [程式碼](#程式碼)
* [表格](#表格) 
* [表情符號](#表情符號)
* [diff語法](#diff語法)

------

### 横線/分隔線/
```
***、---、___可以顯示横線效果
```

------

## 標題
```no-highlight
# H1
## H2
### H3
#### H4
##### H5
###### H6

也可使用下劃線的方式標記 H1 與 H2：

Alt-H1
======

Alt-H2
------
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

也可使用下劃線的方式標記 H1 與 H2：

Alt-H1
======

Alt-H2
------

------

## 文本
### 普通文本
這是一段普通的文本。
### 單行文本
    這是一段單行文本。
在一行開頭加入1個Tab或者4個空格鍵。
### 文字強調
使部分文字高亮，也適合做一篇文章的tag。語法：
```
`東吳巨資` `資料結構` `演算法` `劉謦瑄` 
```
效果：`東吳巨資` `資料結構` `演算法` `劉謦瑄`

### 換行
可在上一行文本後補兩個空格，  
這樣下一行的文本就換行行了。

或是在兩行文本直接加一個空行。

### 斜體/粗體/刪除線

|語法|效果|
|----|-----|
|`*斜體1*`|*斜體1*|
|`_斜體2_`| _斜體2_|
|`**粗體1**`|**粗體1**|
|`__粗體2__`|__粗體2__|
|`這是一個 ~~刪除線~~`|這是一個 ~~刪除線~~|
|`***斜粗體1***`|***斜粗體1***|
|`___斜粗體2___`|___斜粗體2___|
|`***~~斜粗體刪除線1~~***`|***~~斜粗體刪除線1~~***|
|`~~***斜粗體刪除線2***~~`|~~***斜粗體刪除線2***~~|

------
