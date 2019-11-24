---
layout: post
title: 9. Palindrome Number
category: [Leetcode]
description: 
keywords: ['Math', 'Leetcode', 'Easy']
---
### [9. Palindrome Number](https://leetcode.com/problems/palindrome-number)

#### Tags: 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>Determine whether an integer is a palindrome. An integer is a palindrome when it reads the same backward as forward.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> 121
<strong>Output:</strong> true
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> -121
<strong>Output:</strong> false
<strong>Explanation:</strong> From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> 10
<strong>Output:</strong> false
<strong>Explanation:</strong> Reads 01 from right to left. Therefore it is not a palindrome.
</pre>
<p><strong>Follow up:</strong></p>
<p>Coud you solve it without converting the integer to a string?</p>
</div></div>

### Solution
方法1: Naive way O(n) time O(n) space
```java
public boolean isPalindrome(int x) {
    String s = String.valueOf(x);
    int i = 0, j = s.length() - 1;
    while (i < j) {
        if (s.charAt(i++) != s.charAt(j--)) {
            return false;
        }
    }
    return true;
}
```

