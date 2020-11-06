---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---
###### tags: `python` `EV3` `小孩聯盟` `pages6`
---
# 數字基本應用與運算

## :memo: 重點整理
使用指令

input()

1. 基本算術運算
加，減，乘，除，取餘數
2. 除法細節
整數除法，小數除法
3. X的 Y次放
X**Y
4. 字串
單引號，雙引號，多行文字
5. 重覆與串接
重複相同文字，串接多個字串
6. 索引與字元
使用[索引]操作字串中的字元
---
### 基本算術運算
```python=
#實際操作
X=3+6    #請自己嘗試 + - * /
print(X)
print(type(X))
```

### 除法細節
```python=
#實際操作
X=3/6    # / ˊ整數除法
print(X)
print(type(X))
Y=3//6    # // 小數除法
print(Y)
print(type(Y))
```
### 次方
```python=
#實際操作
X=2**3    # 2**3  2的3次方
print(X)
print(type(X))
```
### 取餘數
```python=
#實際操作
X=2%3    # 2*%3  取餘數
print(X)
print(type(X))
```
### X=X+1
```python=
#實際操作
X=1  # 2**3  2的3次方
X=X+1 #X+=1
print(X)
print(type(X))
```
X=X+1 這雖然是同一行指令，但還是有先後的順序
 等於的後面先執行，
 請自行嘗試  +=, -=, *= 都可以自己試試看