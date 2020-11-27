---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---
###### tags: `python` `EV3` `小孩聯盟` `pages9`
---
# 流程控制-迴圈While & for

## :memo: 重點整理
使用指令

while
For
range()

---
1. while基本語法
![](https://i.imgur.com/2jyQTUX.png)


```python=
#範例
n=1
while n<5 :                   #:是必要的
    print(n)                 #注意要縮排 
    n+=1
#請問會執行幾次呢? 
```
## while操作
```python=
#實際操作
n =1
while True:
    print(n)
    n+=1
#ctrl+ C 強制退出
#使用while 時一定要記得設計退出的機制
```
小任務:
請使用while設計一個 1+到 100 的程式 並將答案顯示在螢幕上
```python=
#實際操作
n =1
sum=0
while n<=10:
    sum=sum+n
    n+=1
```
---
---
2. for基本語法
![](https://i.imgur.com/PP7mubp.png)

```python=
#實際操作
for x in [3,3,2,1]
    print(c)            #注意縮排
    
#範例2
for A in "Flower"
    print(A)
```

2.1 for 搭配 range()
renge() 可以產生連續數字的列表
![](https://i.imgur.com/5kudGOo.png)

```python=
#實際操作
for x in range(3):
#就等於
for x in [0,1,2]:
#也可以用範圍 (3:6) 包含前不包含後
for a in range(3:6)
#就等於
for a in [3,4,5]:

```
小任務:
請使用for設計一個 1+到 100 的程式 並將答案顯示在螢幕上

---
```python=
sum=0
for x in range(1,11):
    sum=sum+x
print(sum)

```
---

回家小功課:
用 while 輸出 1-100 內的所有奇數
用 for   輸出 1-100 內的所有偶數
小提示: 記得使用%