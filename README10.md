---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---

[![hackmd-github-sync-badge](https://hackmd.io/mcSd4DsuRkS0u5vUqmVDdA/badge)](https://hackmd.io/mcSd4DsuRkS0u5vUqmVDdA)

###### tags: `python` `EV3` `小孩聯盟` `pages10
---
# 迴圈進階控制
## :memo: 重點整理
使用指令

break 

continue

else




---
break基本概念
![](https://i.imgur.com/8BTiPsH.png)

程式範例
![](https://i.imgur.com/WnoV47Z.png)


---
continue基本概念
![](https://i.imgur.com/Eka9p9C.png)

程式範例
![](https://i.imgur.com/i6Ei9yP.png)

---
while+else基本概念
![](https://i.imgur.com/BiO98Nx.png)

程式範例
![](https://i.imgur.com/AHeU8uM.png)

---
for + else基本概念
![](https://i.imgur.com/qdKyJiT.png)

程式範例
![](https://i.imgur.com/00Ri0Mp.png)

---
## break操作
```python=
#實際操作
n =0
while n<5:
    if n ==3:
        break
    print(n)
    n+1
print("最後的n",n)    

```
