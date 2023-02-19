---
title: "C#字串處理的方法"
slug:
description: "C#字串處理"
date: 2023-02-19 00:07:29
author: EnLin
tags: 
    - CSharp
    - Linq
    - String
cover:
fullscreen: false
---
#  使用頻率較高的字串紀錄
## * 我最常使用的String
```C#
    var haha; //any other type
    string result = haha.ToString(); //轉字串
    string hanlderDataString  = "haha Wordl";
    int length = hanlderDataString.Length //回傳字串長度
    hanlderDataString.Replace("Wordl", "play computer");//字串取代
    bool result = hanlderDataString.Contains("haha"); //ans:true
```
 - `Length()`:回傳字串的長度(含空格)。
    ```C#
         int length = String.Length; // int
    ```
 - `Replace("A","B")`:把字串中的A用B取代。
    ```C#
        string result = String.Replace("A","B");  //B replace A
    ```
 - `Constains("字串A")`:先建立一個布林值等於Constains("字串A")，在尋找字串A是否在字串中，如果再的話回傳true，如果不再就回傳false
    ```C#
        bool result = String.Contains("filterString"); //true false
    ```
 - `IndexOf("字串A")`:先建立一個整數等於IndexOf("字串A")，在尋找字串A是否在字串中，如果再的話就回傳字串A的索引位置，如果不再就回傳-1。
    ```C#
        int result = String.IndexOf("filterString");
    ```
 - `LastIndexOf("要找的內容")`:找到這個字元或字串最後一次出現的索引位置，如果找不到會回傳-1
    ```C#
        int result = String.LastIndexOf("filterString");
    ```
 - `Split()`:將字串切割後放入陣列中，請將切割的符號用單引號包起來放入括號中。
    ```C#
        string result = String.Split("x");
    ```
 - `Substring(A,B)`:找出這個字串的第A個字(起始索引數)到第B個字(結束索引數)。
    ```C#
        string result = String.Substring("A","B");
    ```
 - `ToUpper()`:將字串中的英文全部轉成大寫。
    ```C#
        string result = String.ToUpper();
    ```
 - `ToLower()`:將字串中的英文全部轉成小寫。
    ```C#
        string result = String.ToLower();
    ```
 - `Trim()`:經字串前面、後面[空白]給刪除。
    ```C#
        string result = String.Trim();
    ```
 - `String.Trim(Char[])`:移除開頭和結尾的指定字元。
    ```C#
        string result = String.Trim('');
    ```
 - `String.TrimStart(Char[])`:移除開頭的指定字元。
    ```C#
        string result = String.TrimStart('');
    ```
 - `String.TrimEnd(Char[])`:移除結尾的指定字元。
    ```C#
        string result = String.TrimEnd('');
    ```
 - Remove("從第幾個開始移除"):`Remove(Int)`
    ```C#
        string result = String.Remove(10);
    ```
 - Remove("從第幾個開始移除",總共移除幾個):`Remove(Int,Int)`
    ```C#
        string result = String.Remove(5,7);
    ```
 - String.Insert("從第幾個index插入", "要插入的字串"):`String.Insert(Int32, String)`
    ```C#
        string result = String.Insert(5, "InsertString");
    ```
---
## Reference:

[C#與ASP.Net入門-我要成為工程師!!系列 第 18 篇](https://ithelp.ithome.com.tw/articles/10216394)

[C#常用的字函數與用法(學習紀錄)](https://ithelp.ithome.com.tw/articles/10232305)

