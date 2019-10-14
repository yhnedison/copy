---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Stack', 'Leetcode', 'Medium']
---
### [907. Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums)

#### Tags: 'Array', 'Stack'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array of integers <code>A</code>, find the sum of <code>min(B)</code>, where <code>B</code> ranges over every (contiguous) subarray of <code>A</code>.</p>
<p>Since the answer may be large, <strong>return the answer modulo <code>10^9 + 7</code>.</strong></p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[3,1,2,4]</span>
<strong>Output: </strong><span id="example-output-1">17</span>
<strong>Explanation:</strong> Subarrays are [3], [1], [2], [4], [3,1], [1,2], [2,4], [3,1,2], [1,2,4], [3,1,2,4]. 
Minimums are 3, 1, 2, 4, 1, 1, 2, 1, 1, 1.  Sum is 17.</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= A.length &lt;= 30000</code></li>
<li><code>1 &lt;= A[i] &lt;= 30000</code></li>
</ol>
<div>
<p> </p>
</div>
</div></div>

### Solution
