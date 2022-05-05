## [剑指 Offer 05. 替换空格](https://leetcode-cn.com/problems/ti-huan-kong-ge-lcof/)

```java
class Solution {
    public String replaceSpace(String s) {
        StringBuilder buffer = new StringBuilder();
        for(int i=0; i<s.length(); i++){
            if(s.charAt(i) == ' '){
                buffer.append("%20");
            }else{
                buffer.append(s.charAt(i));
            }
           
        }
        return buffer.toString();
    }
}
```

