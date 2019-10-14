---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Leetcode', 'Medium']
---
### [1144. Decrease Elements To Make Array Zigzag](https://leetcode.com/problems/decrease-elements-to-make-array-zigzag)

#### Tags: 'Array'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array <code>nums</code> of integers, a <em>move</em> consists of choosing any element and <strong>decreasing it by 1</strong>.</p>
<p>An array <code>A</code> is a <em>zigzag array</em> if either:</p>
<ul>
<li>Every even-indexed element is greater than adjacent elements, ie. <code>A[0] &gt; A[1] &lt; A[2] &gt; A[3] &lt; A[4] &gt; ...</code></li>
<li>OR, every odd-indexed element is greater than adjacent elements, ie. <code>A[0] &lt; A[1] &gt; A[2] &lt; A[3] &gt; A[4] &lt; ...</code></li>
</ul>
<p>Return the minimum number of moves to transform the given array <code>nums</code> into a zigzag array.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> nums = [1,2,3]
<strong>Output:</strong> 2
<strong>Explanation:</strong> We can decrease 2 to 0 or 3 to 1.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> nums = [9,6,1,6,2]
<strong>Output:</strong> 4
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 1000</code></li>
<li><code>1 &lt;= nums[i] &lt;= 1000</code></li>
</ul>
</div></div>

### Solution
