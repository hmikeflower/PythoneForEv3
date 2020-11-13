---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---
###### tags: `python` `EV3` `小孩聯盟` `pages7`
---
# 文字基本應用與運算

## :memo: 重點整理
使用指令

input()
int()
str()
\ 跳脫
\n 換行

1. 字串
單引號，雙引號，多行文字
2. 重覆與串接
重複相同文字，串接多個字串
3. 索引與字元
使用[索引]操作字串中的字元

---
### 字串運算
```python=
#實際操作
S="hello"    #""雙引號 或是單引號 都可以
print(S)
print(type(S))
```
### 如果字串中有"" 怎麼辦?
```python=
#實際操作
S="hello I AM "MIKE" "  #""雙引號 或是單引號 都可以
print(S)
print(type(S))
```

### 字串串接
```python=
#實際操作
S="hello" "WORLD"  #""雙引號 或是單引號 都可以
print(S)

S="hello\nWORLD"  #\n 換行
print(S)

S="hello"*3+"world"  #\n 換行
print(S)

```

### 字元操作
```python=
#實際操作
S="HELLO"  #字串會對內部的字元編號(索引)，從0開始
print(S[0])
print(S[1:4])  #開頭編號與結束編號，(包含開頭不包含結束)
```






---
回家功課:
對終端機輸入 兩個數字，並計算出兩個數字的相乘


