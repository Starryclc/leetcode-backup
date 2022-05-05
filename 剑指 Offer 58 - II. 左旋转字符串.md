## [剑指 Offer 58 - II. 左旋转字符串](https://leetcode-cn.com/problems/zuo-xuan-zhuan-zi-fu-chuan-lcof/)

```java
class Solution {
    public String reverseLeftWords(String s, int n) {
        String sub1 = s.substring(0,n);
        String sub2 = s.substring(n,s.length());
        return sub2+sub1;

    }
}
```

