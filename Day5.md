# 242.有效的字母异位符

**为什么想到用哈希法？要查找当前元素的存在**

**为什么用数组？因为哈希表长度最多只有26，0~z**

![242](https://github.com/KJXXbear/Algorithm_Learning/blob/main/image/242.%E6%9C%89%E6%95%88%E7%9A%84%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D.png?raw=true)

# 349.两个数组的交集

**为什么想到用哈希法？因为要查找给定的一个数组，另外一个数组与其是否有交集**

**为什么用set而不用数组？因为如果元素少，而哈希值相差大，数组存的话，浪费内存**

![349](https://github.com/KJXXbear/Algorithm_Learning/blob/main/image/349.%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86.png?raw=true)

# 202.快乐数

**为什么想到用哈希法？因为循环可能一直进行下去，而循环的终止条件是结果为1或者出现了重复结果，这个时候可以把每一次的结果都保存到哈希表中**

**这道题对我来说，难点在于计算数的各个位置的单数平方和，除10取模**

![202](https://github.com/KJXXbear/Algorithm_Learning/blob/main/image/202.%E5%BF%AB%E4%B9%90%E6%95%B0.png?raw=true)

# 1.两数之和

**暴力解法应该想到：两层循环找满足条件的i和j**

**为什么也可以用哈希？因为在给定一个数组的情况下，在另一个数组用哈希法查找满足条件的元素**

**为什么用map？因为题目要求不仅要返回元素，还要返回元素下标，而map（key,value）**

**这道题对于我的难点在不熟悉函数的用法，pair?iter->second?**

![1](https://github.com/KJXXbear/Algorithm_Learning/blob/main/image/1.%E4%B8%A4%E6%95%B0%E4%B9%8B%E5%92%8C.png?raw=true)
