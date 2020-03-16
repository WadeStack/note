参考资料:
- [list.sort()](https://docs.python.org/3.7/tutorial/datastructures.html?highlight=sort)
- [sorted()](https://docs.python.org/3.7/library/functions.html#sorted)
- [sorting how to do](https://docs.python.org/3.7/howto/sorting.html#sortinghowto)



## sorted(iterable, *, key=None, reverse=False)
> python3中移除了cmp

###### 参数说明：

- iterable:迭代器，可迭代的元素
- key:主要是用来进行比较的元素，只有一个参数，具体的函数的参数就是取自于可迭代对象中，指定可迭代对象中的一个元素来进行排序。默认为空,可传函数和匿名函数
- reverse：排序规则，reverse = True 降序， reverse = False 升序（默认）
###### 返回值
从可迭代的项目中返回新的排序列表。




## list.sort(key=None, reverse=False)
###### 参数说明：
- key:主要是用来进行比较的元素，只有一个参数，具体的函数的参数就是取自于可迭代对象中，指定可迭代对象中的一个元素来进行排序。默认为空,可传函数和匿名函数
- reverse：排序规则，reverse = True 降序， reverse = False 升序（默认）

###### 返回值
无返回值，改变原list

## 实例:
###### list.sort(key=匿名函数)
###### list.sort(key=匿名函数,reverse=True)
```python
random = [(2, 2), (3, 4), (4, 1), (1, 3)]
random.sort(key=lambda x:x[1])
print(random)//[(4, 1), (2, 2), (1, 3), (3, 4)]
random.sort(key=lambda x:x[1],reverse=True)
print(random)//[(3, 4), (1, 3), (2, 2), (4, 1)]
```

###### sorted(list,key=lambda)

```python
random = [(2, 2), (3, 4), (4, 1), (1, 3)]
print(sorted(random,key=lambda x:x[1]))//[(4, 1), (2, 2), (1, 3), (3, 4)]
print(random)//[(2, 2), (3, 4), (4, 1), (1, 3)]
```
sorted(list)排序完生成一个新的list，原始list并未改变

