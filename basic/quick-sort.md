本页面将简要介绍快速排序。

## 定义

快速排序（英语：Quicksort），又称分区交换排序（英语：partition-exchange sort），简称「快排」，是一种被广泛运用的排序算法。

## 基本原理与实现

### 过程

快速排序的工作原理是通过 [分治](./divide-and-conquer.md) 的方式来将一个数组排序。

快速排序分为三个过程：

1. 选择一个**基准数**，按照基准数，把数列划分为两个区间，使得左区间所有元素小于基准数， 右区间所有元素大于基准数。
2. 递归到两个区间内，分别进行上述操作。
3. 等到`L >= R` 之后，即所有区间处理完毕，数列已经有序。

和归并排序不同，第一步并不是直接分成前后两个序列，而是在分的过程中要保证相对大小关系。具体来说，第一步要是要把数列分成两个部分，然后保证前一个子数列中的数都小于后一个子数列中的数。为了保证平均时间复杂度，一般是随机选择一个数即 **基准数** 来当做两个子数列的分界。

之后，维护一前一后两个指针 $i$ 和 $j$，$i$ 从左向右开始扫描，直到碰到一个大于基准数的数字停止； $j$ 从右向左扫描，直到碰到一个小于基准数的数字停止， 交换$i$ 和 $j$ 位置的数字。 扫描直到$i$ 与$j$ 相遇时，即两个区间已经满足相对大小关系。

其实，快速排序的模版不是固定的，有很多实现方法， 建议熟练掌握一种。

??? +note "基准数的选取"
    - 可以选择最左侧的数字当作**基准值**，但是如果有退还$O(n^2)$ 的风险
    - 选择中间的数字，当作**基准值**，
    - 选择中位数， 即最左侧的数字，中间的数字，最右侧的数字。 选择中间大小的数字。
    - 随机选择数列中的一个数字

### 代码模版

```cpp 
void quickSort(int f[], int l, int r){
	if (l >= r) return;
	int  pt =f[(l+r) >> 1];  // 选择基准数
	int i = l - 1 ,  j = r + 1;
	while (i < j){
		do i++; while (f[i] < pt);
		do j--; while (f[j] > pt);
		if (i < j) swap(f[i], f[j]);
	}
	
	quickSort(f, l, j);   // 处理左区间
	quickSort(f, j+1, r); // 处理右区间
}
```


## 性质

### 稳定性

快速排序是一种不稳定的排序算法。

### 时间复杂度

快速排序的最优时间复杂度和平均时间复杂度为 $O(n\log n)$，最坏时间复杂度为 $O(n^2)$。

对于最优情况，每一次选择的分界值都是序列的中位数，此时算法时间复杂度满足的递推式为 $T(n) = 2T(\dfrac{n}{2}) + \Theta(n)$，由主定理，$T(n) = \Theta(n\log n)$。

对于最坏情况，每一次选择的分界值都是序列的最值，此时算法时间复杂度满足的递推式为 $T(n) = T(n - 1) + \Theta(n)$，累加可得 $T(n) = \Theta(n^2)$。

对于平均情况，每一次选择的分界值可以看作是等概率随机的。




## 题单
[P1177 【模板】排序](https://www.luogu.com.cn/problem/P1177)
[P1138 第 k 小整数](https://www.luogu.com.cn/problem/P1138)


