本页面将简要介绍枚举算法。

## 简介

枚举（英语：Enumerate）是基于已有条件来猜测答案的一种问题求解策略。

枚举的思想是不断地猜测，从可能的集合中一一尝试，然后再判断题目的条件是否成立。

## 要点

### 给出解空间

建立简洁的数学模型。

枚举的时候要想清楚：可能的情况是什么？要枚举哪些要素？

### 减少枚举的空间

枚举的范围是什么？是所有的内容都需要枚举吗？

在用枚举法解决问题的时候，一定要想清楚这两件事，否则会带来不必要的时间开销。

### 选择合适的枚举顺序

根据题目判断。比如例题中要求的是最大的符合条件的素数，那自然是从大到小枚举比较合适。

## 例题

???+note "[洛谷 P3836 GESP 百鸡问题](https://www.luogu.com.cn/problem/B3836)"

    每只公鸡 5 元，每只母鸡 3 元，每 3 只小鸡 1 元；现在有 100 元，买了 100 只鸡，共有多少种方案？
    
    小明很喜欢这个故事，他决定对这个问题进行扩展，并使用编程解决：如果每只公鸡 $x$ 元，每只母鸡 $y$ 元，每 $z$ 只小鸡 $1$ 元；现在有 $n$ 元，买了 $m$ 只鸡，共有多少种方案？



??? note "解题思路"
    通过观察可以发现， 公鸡的数量范围是 $[0, m]$ 只；母鸡的数量范围是$[0, m]$只；小鸡的数量范围是$[0, m]$​​。我们可以枚举每个可能性。

    ```cpp
    --8<-- "docs/basic/code/enumerate/luogu_B3836.cpp"
    ```
    上一个写法是暴力写法，时间复杂度为$O(n^3)$大概率会超时，但其实我们可以发现，我们假设枚举公鸡的数量为$i$；母鸡的数量范围是$[0, m-i]$，假设为$j$；小鸡的数量则是$m-i-j$。
    ```cpp
    --8<-- "docs/basic/code/enumerate/luogu_B3836_1.cpp"
    ```
    当然还有一些局部小优化，例如：小鸡的数量一定是$z$的倍数，否则不符合要求，那么就可以枚举小鸡的数量，来减少循环次数。 
    ```cpp
    --8<-- "docs/basic/code/enumerate/luogu_B3836_2.cpp"
    ```


## 习题

- [洛谷 P1614 爱与愁的心痛](https://www.luogu.com.cn/problem/P1614)

- [洛谷 P1089 津津的储蓄计划](https://www.luogu.com.cn/problem/P1089)

- [洛谷 P8828 直角三角形](https://www.luogu.com.cn/problem/P8828)

- [洛谷 B3750 幸运素数](https://www.luogu.com.cn/problem/B3750)
  
- [洛谷 P8680 特别数的和](https://www.luogu.com.cn/problem/P8680)

- [洛谷 P2141 珠心算测验](https://www.luogu.com.cn/problem/P2141)
