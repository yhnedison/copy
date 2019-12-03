---
layout: post
title: 35. Search Insert Position
category: [Leetcode]
description: 
keywords: ['Array', 'Binary Search', 'Leetcode', 'Easy']
---
### [35. Search Insert Position](https://leetcode.com/problems/search-insert-position)

#### Tags: 'Array', 'Binary Search'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a sorted array and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.</p>
<p>You may assume no duplicates in the array.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> [1,3,5,6], 5
<strong>Output:</strong> 2
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> [1,3,5,6], 2
<strong>Output:</strong> 1
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> [1,3,5,6], 7
<strong>Output:</strong> 4
</pre>
<p><strong>Example 4:</strong></p>
<pre><strong>Input:</strong> [1,3,5,6], 0
<strong>Output:</strong> 0
</pre>
</div></div>

### Solution
```java
public int searchInsert(int[] nums, int target) {
    int result = 0;
    for (int i = 0; i < nums.length; i++) {
        if (target <= nums[i]) {
            return i;
        }
    }
    
    return nums.length;
}
```