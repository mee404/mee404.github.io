---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---


## Table of Contents:

- [Intro to Linear classification]("about.md">)
- [Linear score function](#score)
- [Interpreting a linear classifier](#interpret)
- [Loss function](#loss)
  - [Multiclass SVM](#svm)
  - [Softmax classifier](#softmax)
  - [SVM vs Softmax](#svmvssoftmax)
- [Interactive Web Demo of Linear Classification](#webdemo)
- [Summary](#summary)

```python
def quicksort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quicksort(left) + middle + quicksort(right)

print(quicksort([3,6,8,10,1,2,1]))
# Prints "[1, 1, 2, 3, 6, 8, 10]"
```