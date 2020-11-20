---
tags: python, 小孩聯盟, EV3
slideOptions:
  transition: slide
---
###### tags: `python` `EV3` `小孩聯盟` `pages8`
---
# 流程控制-IF判斷式

## :memo: 重點整理
使用指令

if
else
elif


1. 基本語法
```python=
#實際操作
if 判斷條件 :                   #:是必要的
    若判斷條件為真 True，執行命令 #注意要縮排 
```
2. 基本語法2
```python=
#實際操作
if 判斷條件 :                    #:是必要的
    若判斷條件為真 True，執行命令  #注意要縮排 
else:                           #注意:    
    若判斷條件為假 False，執行命令 #注意縮排
```
3. 基本語法3
```python=
#實際操作
if 判斷條件 :                    #:是必要的
    若判斷條件為真 True，執行命令  #注意要縮排 
elif判斷條件2:                  #注意:    
    若判斷條件為真 True，執行命令 #注意縮排
else:
    若上述狀況都不滿足，則執行這邊得命令 #注意縮排
```
EV3 圖形化程式範例

![](https://i.imgur.com/ovZ4EPo.png)





---
## 實際範例
```python=
#實際操作
x=input("請輸入數字:")  #注意這邊輸入的都會是字串
x=int(x) #型別轉換
if x>200:
    print("大於200")
elif x>100:
    print("大於100,小於200")
else:
    print("小於100")
```

---
簡易計算機:

請問要做什麼運算 1.加法 2.減法 3.乘法 4.除法
請輸入第一個數字
請輸入第二個數字

output:
答案
