---
layout: post
category: Leetcode
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Medium']
---
### [1191. K-Concatenation Maximum Sum](https://leetcode.com/problems/k-concatenation-maximum-sum)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an integer array <code>arr</code> and an integer <code>k</code>, modify the array by repeating it <code>k</code> times.</p>
<p>For example, if <code>arr = [1, 2]</code> and <code>k = 3 </code>then the modified array will be <code>[1, 2, 1, 2, 1, 2]</code>.</p>
<p>Return the maximum sub-array sum in the modified array. Note that the length of the sub-array can be <code>0</code> and its sum in that case is <code>0</code>.</p>
<p>As the answer can be very large, return the answer <strong>modulo</strong> <code>10^9 + 7</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> arr = [1,2], k = 3
<strong>Output:</strong> 9
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> arr = [1,-2,1], k = 5
<strong>Output:</strong> 2
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> arr = [-1,-2], k = 7
<strong>Output:</strong> 0
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= arr.length &lt;= 10^5</code></li>
<li><code>1 &lt;= k &lt;= 10^5</code></li>
<li><code>-10^4 &lt;= arr[i] &lt;= 10^4</code></li>
</ul></div></div>

### Solution
