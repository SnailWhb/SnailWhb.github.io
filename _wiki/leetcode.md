#Leetcode笔记

##2017.3.10
### 一、 python中一些实用的函数
   str.isupper()：
无参数，如果字符串中包含至少一个区分大小写的字符，并且所有这些(区分大小写的)字符都是大写，则返回 True，否则返回 False

   islower()：无参数，如果字符串中包含至少一个区分大小写的字符，并且所有这些(区分大小写的)字符都是小写，则返回 True，否则返回 False
  

   istitle()：无参数，如果字符串中所有的单词拼写首字母是否为大写，且其他字母为小写则返回 True，否则返回 False.
##2017.3.13

##寻找数组中重复（缺失）的元素
- 448. Given an array of integers, 1 ≤ a[i] ≤ n (n = size of array), some elements appear twice and others appear once.Find all the elements that appear twice in this array.

 Example:

     Input:
     [4,3,2,7,8,2,3,1]

     Output:
     [2,3]

**分析**：数组中的元素是整数，大于 1 小于 n（n是数组的长度），并且最多只能两次。






- Given an array of integers where 1 ≤ a[i] ≤ n (n = size of array), some elements appear twice and others appear once.Find all the elements of [1, n] inclusive that do not appear in this array.

Could you do it without extra space and in O(n) runtime? You may assume the returned list does not count as extra space.

Example:

     Input:
    [4,3,2,7,8,2,3,1]

     Output:
     [5,6]