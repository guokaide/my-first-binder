# my-first-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guokaide/my-first-binder/HEAD)

# 基础知识

程序 = 数据结构 + 算法

## 数据结构
* 整型 int
* 字符串 string
* 数组 A[n]
* 字典 [key : value] [90 : 3] 
* ...

## 算法
* function

A[n]: [1, 2, 3, 4, 5, 6] 找到和为 7 的 2 个数。

算法：求解这个问题的代码实现 + 理论实现

理论实现：

y = f(a, target)

代码实现：

```python
def f(a, target) -> []:
  for i in range(len(a)):
    for j in range(i+1, len(a)):
        if a[i] + a[j] == target:
            return [a[i], a[j]] 
  return []
```

# cite
* https://mybinder.readthedocs.io/en/latest/introduction.html
