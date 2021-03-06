# 内排序

内部排序是指待排序列完全存放在内存中所进行的排序过程，适合不太大的元素序列。

**八种常见内部排序算法总结回顾**

| 排序方法 | 最好时间复杂度 | 平均时间复杂度 | 最坏时间复杂度 | 空间复杂度 | 是否稳定 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 冒泡排序 | O\(n\) | O\(n\*n\) | O\(n\*n\) | O\(1\) | 稳定 |
| 插入排序 | O\(n\) | O\(n\*n\) | O\(n\*n\) | O\(1\) | 稳定 |
| 选择排序 | O\(n\*n\) | O\(n\*n\) | O\(n\*n\) | O\(1\) | 不稳定 |
| 希尔排序 | O\(n\) | 不定 | O\(n\*n\) | O\(1\) | 不稳定 |
| 堆排序 | O\(n\*logn\) | O\(n\*logn\) | O\(n\*logn\) | O\(1\) | 不稳定 |
| 归并排序 | O\(n\*logn\) | O\(n\*logn\) | O\(n\*logn\) | O\(n\) | 稳定 |
| 快速排序 | O\(n\*logn\) | O\(n\*logn\) | O\(n\*n\) | O\(logn\) | 不稳定 |
| 计数排序 | O\(n+k\) | O\(n+k\) | O\(n+k\) | O\(k\) | 稳定 |
| 基数排序 | O\(d\(n+k\)\) | O\(d\(n+k\)\) | O\(d\(n+k\)\) | O\(k\) | 稳定 |
| 桶排序 | O\(n\) | O\(n\) | O\(n\) | 不定 | 取决于桶内 |

* [选择排序](selection_sort.md)
* [直接插入排序](insertion_sort.md)
* [希尔排序](shell_insertion_sort.md)
* [冒泡排序](bubble_sort.md)
* [快速排序](quick_sort.md)
* [堆排序](heap_sort.md)
* [归并排序](merge_sort.md)

