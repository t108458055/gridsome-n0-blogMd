---
title: "這是第一次的發文"
slug:
description: ""
date: 2022-06-26 22:09:29
author: 蕭恩霖
tags: - content
cover:
fullscreen: false
---
# 想不到要發什麼 直接撈 2022 /3 /13 的MD 筆記
## * 滑鼠移動至下拉式選單 自動顯示出來 使用 jQuery方式
```js
    /**<!-- Html 5 Bootstrap 4.3.1 -->*/
        <li class="nav-item dropdown adminddlin0">
            <a class="nav-link dropdown-toggle">
                Login/Signin
            </a>
            <div class="dropdown-menu">         
                <a class="dropdown-item">Item-A</a>
                <a class="dropdown-item">Item-B</a>
            </div>
        </li>

    /** JQ 下拉式選單  滑鼠 移動至 下拉式直接顯示*/
       <script>
            $(document).ready(function () {
                $('.adminddlin0').hover(function () {
                    $(this).find('.dropdown-menu').toggleClass("show");
                });
            });

        </script>
 ```
## **用法與規則:**
### **這是標題**
可以手動輸入,也可以點擊鍵盤上方的按鈕MD
# H1 一級標題

## H2 二級標題

### H3 三級標題

## !無序標題
* 從精通到陌生
* 從看懂到看開
* 從安裝到卸載

## !!有序排列
使用數字與小數點家空格如"1.","2"來創建有序列表
1. 從入門到單身
2. 從刪庫到跑路
3. 從入航道改行

## 代辦事項

- [ ] 吃飯
- [ ] 睡覺
- [x] 打咚咚
- [ ] 哭啊

## 超連結的寫法
[google](https://www.google.com/)

## 圖片
![](https://tfm104t05.myvnc.com/0%20(1).jpg)

## 圖片
![alt](https://tfm104t05.myvnc.com/0%20(1).jpg "歐歐歐")

## 飲用方式
![alt][img01]


[img01]:https://tfm104t05.myvnc.com/0%20(1).jpg
## 引用區塊
>Language Learning Strategies
## 引用-階層式
> 人遠比自己想象的要堅強
>> 特別是當你回頭看看的時候
>>> 你會發現自己走了一段自己都沒想到的路

**粗體**
__粗體__
*看到了咩,我偕了沒*
_真hen斜_
***粗體+斜體***

~~此處的故事只能用淚水掩蓋~~

# 群裡單身狗名單

|   姓名    |   年齡    |   體重     身高   |
|----------|:---------:|------------------:|
|張三紀|18|80 178|
|張小覽|88|99 148|

'Hello World'

```go
package main

import "fmt"

func main(){

        fmt.Println("沒入門就放棄");

}
```

分隔線
***
已經學會markdown了!!

<p align="right">哭啊~!</p>
<center>哭啊~!</center>
<p align="left">哭啊~!</p>

<center>居中對齊</center>

<h1 style="text-align:center">居中對齊 </h1>

<h1 style="text-align:right">居右對齊 </h1>

## 這個是公式
$$ o_{t} =g(Vs_{t}) $$

<ul class="xxx">
<li>xxx<li>
</ul>

#文字居中
<center>Markdown</center>
​
​
#文字左對齊
<p align = "left">Markdown</p>
​
​
#文字右又對齊
<p align="right" >Markdown</p>

### Markdown 字體改變顏色
​
這是綠色字體：<font color =green>Markdown</font>
紅色字體：<font color = red>Markdown</font>
藍色字體：<font color =blue>Markdown</font>
​
​
### Markdown 字體大小改變
​<hr>
size為1：<font size ="1">Markdown</font>
<hr>
size為5：<font size = "5">Markdown</font>
<hr>
size為10：<font size ="10">Markdown</font>
​<hr>
​
<font color=red size=12>字號12</font>  
<font color=red size=8>字號8</font>  
<font color=red size=4>字號4</font>   
<font color=red size=2>字號2</font>   
<font color=red size=3>字號3</font>   
<font color=black>預設字號</font>     
<table><tr><td bgcolor=orange>背景色是：orange</td></tr></table>


語法撰寫範例一：將「今天天氣真好。」顯示粗體並更改為紅色
**<font color=#FF0000>今天天氣真好。</font>**


語法撰寫範例二：將「Title」設定成等級一標題並更改為藍色
# <font color=#0000FF>Title</font>