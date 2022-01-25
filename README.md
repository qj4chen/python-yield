# 关于Python中的关键字`yield`的常见用法
> 代码详见本repo的ipynb文件

## 介绍Python自带`itertools`包中的部分
1. [`itertools.count`](https://docs.python.org/3/library/itertools.html#itertools.count)
2. [`itertools.filterfalse`](https://docs.python.org/3/library/itertools.html#itertools.filterfalse)
3. 使用`.send()`重新设置起点时,究竟在做什么

## 使用流的方式，无穷地生成素数/fizzbuzz数等
1. 三种方式实现无穷素数流: 带缓存 | 不带缓存 | 支持`.send()`方法
2. 对`流`的筛选 | 对`流`函数的装饰

## 在两个流中传输数据。应用：二分法解一元二次方程
1. 其实没有想象中那么复杂, 需要处理的细节, 以及可以改进的方向比较多
2. 如果能解一元多次方程, 那么就能解出多次常微分方程的通解形式...这是后话了

## useful links:
1. [introduction-to-python-generators](https://realpython.com/introduction-to-python-generators)
2. [http://www.dabeaz.com/finalgenerator/](http://www.dabeaz.com/finalgenerator/)
