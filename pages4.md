---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---
###### tags: `python` `EV3` `小孩聯盟` `pages4`
---
# 終於可以開始了。
一點點....

# linux commands quick review

**印出目前位置 *(目前的工作目錄)***
> [**p**rint **w**orking **d**irectory](https://en.wikipedia.org/wiki/Pwd)
```shell
$ pwd
```

**列出目前目錄下的檔案**
> [**l**i**s**t](https://en.wikipedia.org/wiki/Ls)
```shell
$ ls
```

**創建資料夾**
> [**m**a**k**e **dir**ectory](https://en.wikipedia.org/wiki/Mkdir)
```shell
$ mkdir myproject
```

**移動位置 *(變更你的工作目錄)***
> [**c**hange **d**irectory](https://en.wikipedia.org/wiki/Cd_(command))
```shell
$ cd myproject
```

**創建一個空檔案**
> [touch](https://en.wikipedia.org/wiki/Touch_(command))
```shell
$ touch main.py
```

**複製檔案**
```shell
cp main.py main.bak.py
```
> 抽考，`cp` 又是何單字的縮寫？

**刪除檔案**
```shell
$ rm main.bak.py
```
> 抽考，`rm` 又是何單字的縮寫？

### Bonus! 先跳過

**編輯檔案**
:::warning
refer to [簡明 Vim 文字編輯器操作入門教學](https://blog.techbridge.cc/2020/04/06/how-to-use-vim-as-an-editor-tutorial/)
:::

- 我們其實可以直接在 command line 環境下撰寫 python 程式碼
- 需要使用一個非常強大的編輯器：**vim** 

```shell
$ vim main.py
```
- 第一個看到的是**命令模式**，在此模式下按下
    - **i** - 進入**插入模式**
    - **:** - 進入**底線命令模式**
- 在**插入模式**中你可以編輯內容
- 在**底線命令模式**你可以**花式離開** vim 環境
- (demo) 編輯 python file、執行 python file、印出 hello world


## Exercise(s)
*hints: `<command> --help`* or google it
1. `ls`
    - 如何列出**隱藏檔**? 在 linux 環境裡隱藏檔**如何表示**？
    - 如何列出檔案的**詳細資料**?
        - windows 上看起來是這樣 ![](https://i.imgur.com/1oZSdUv.png)
        - `ls` 是這樣 (git bash view) ![](https://i.imgur.com/U89kbYL.png)
        - 如何變成這樣 ![](https://i.imgur.com/c8465k9.png)
    - 觀察，預設的**詳細資料**排序方式是 (use a long listing format)？
    - 如何改變排序方式、改成以**修改日期**排序 (sort by modification time, newest first)？
    - 如何讓最後的排序結果**反向排序** (reverse order while sorting)？
2. 如何**刪除目錄**？
    - 如何用 `rm` 刪除目錄？
    - 有沒有其他指令可以刪除目錄？是否有情境限制？








### Python 指令

print()  <--- 在 終端機 印出 想印出的內容

```python=
a = 0
b = 10
c = "GO"
print("HELLO WORLD") # 印出 TELLO WORLD
print(a)
print("a")
print(a+b)

```
請依照上面程式碼 自行練習
最後試試看 print(a+b+c)

---
