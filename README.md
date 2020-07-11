# Go-LeetCode
- <a href="#linkedlist">链表</a>
- <a href="#string">字符查找</a>
- <a href="#sorting">排序</a>
- <a href="#recursive">递归</a>

## <a name="linkedlist">链表</a>
##### 1.链表的尾插法

##### 2.链表的头插法

##### 3.两两交换链表结点

##### 4.判断链表是否有环
>方法一、使用快慢指针(Floyd's Algorithm)<br />
>方法二、使用哈希<br />
##### 5.链表的中间结点

##### 6.反转链表
> 基本步骤<br />
>1.设置三个指针--prev 为 nil, current 为当前结点, next 为下一个结点<br />
>2.存储当前结点的下一个结点: `next = current.next` <br /> 
>3.改变当前结点的下一个结点: `current.next = prev` <br />
>4.把prev和current都向前移动一步: <br />`prev = current` <br /> `current = next` <br />

## <a name="string">字符查找</a>
##### 暴力算法(BF)

##### KMP

##### Karp Rabin

## <a name="sorting">排序</a>
##### 插入排序

##### 选择排序

##### 快速排序

##### 归并排序

##### 希尔排序

##### 冒泡排序

##### 堆排序

##### 计数排序

##### 桶排序

##### 休眠排序

##### 奇偶排序