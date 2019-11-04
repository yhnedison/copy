---
layout: post
title: 26. Remove Duplicates from Sorted Array
category: [Leetcode]
description: 
keywords: ['Array', 'Two Pointers', 'Leetcode', 'Easy']
---
### [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array)

#### Tags: 'Array', 'Two Pointers'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a sorted array <em>nums</em>, remove the duplicates <a href="https://en.wikipedia.org/wiki/In-place_algorithm" target="_blank"><strong>in-place</strong></a> such that each element appear only <em>once</em> and return the new length.</p>
<p>Do not allocate extra space for another array, you must do this by <strong>modifying the input array <a href="https://en.wikipedia.org/wiki/In-place_algorithm" target="_blank">in-place</a></strong> with O(1) extra memory.</p>
<p><strong>Example 1:</strong></p>
<pre>Given <em>nums</em> = <strong>[1,1,2]</strong>,

Your function should return length = <strong><code>2</code></strong>, with the first two elements of <em><code>nums</code></em> being <strong><code>1</code></strong> and <strong><code>2</code></strong> respectively.

It doesn't matter what you leave beyond the returned length.</pre>
<p><strong>Example 2:</strong></p>
<pre>Given <em>nums</em> = <strong>[0,0,1,1,1,2,2,3,3,4]</strong>,

Your function should return length = <strong><code>5</code></strong>, with the first five elements of <em><code>nums</code></em> being modified to <strong><code>0</code></strong>, <strong><code>1</code></strong>, <strong><code>2</code></strong>, <strong><code>3</code></strong>, and <strong><code>4</code></strong> respectively.

It doesn't matter what values are set beyond the returned length.
</pre>
<p><strong>Clarification:</strong></p>
<p>Confused why the returned value is an integer but your answer is an array?</p>
<p>Note that the input array is passed in by <strong>reference</strong>, which means modification to the input array will be known to the caller as well.</p>
<p>Internally you can think of this:</p>
<pre>// <strong>nums</strong> is passed in by reference. (i.e., without making a copy)
int len = removeDuplicates(nums);

// any modification to <strong>nums</strong> in your function would be known by the caller.
// using the length returned by your function, it prints the first <strong>len</strong> elements.
for (int i = 0; i &lt; len; i++) {
    print(nums[i]);
}</pre>
</div></div>

### Solution
```java
public int removeDuplicates(int[] nums) {
    // two pointer
    // i point to the end of result array
    // j is the runner
    if (nums == null) return 0;
    if (nums.length < 2) return nums.length;
    
    int i = 0; // slow runner, j is fast runner
    for (int j = 1; j < nums.length; j++) {
        if (nums[j] != nums[i]) {
            i++; // increment slow runner
            nums[i] = nums[j];
        }
    }
    return i+1;
}
```

A general solution for K
```java
public int removeDuplicates(int[] nums) {
    if (nums == null) return 0;
    if (nums.length <= 2) return nums.length;
    // i point to the end of result array
    // j is the runner
    int i = 0, count = 1; 
    for (int j = 1; j < nums.length; j++) {
        if (nums[j] != nums[j-1]) {
            i++;
            nums[i] = nums[j];
            count = 1;
        } else {
            // need to check previous count
            // replace 2 with k for general solution
            if (count < k) { 
                i++;
                nums[i] = nums[j];
            }
            count++;
        }
        
        
        
    }
    return i + 1;
}
```