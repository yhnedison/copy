---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Dynamic Programming', 'Leetcode', 'Medium']
---
### [873. Length of Longest Fibonacci Subsequence](https://leetcode.com/problems/length-of-longest-fibonacci-subsequence)

#### Tags: 'Array', 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>A sequence <code>X_1, X_2, ..., X_n</code> is <em>fibonacci-like</em> if:</p>
<ul>
<li><code>n &gt;= 3</code></li>
<li><code>X_i + X_{i+1} = X_{i+2}</code> for all <code>i + 2 &lt;= n</code></li>
</ul>
<p>Given a <b>strictly increasing</b> array <code>A</code> of positive integers forming a sequence, find the <strong>length</strong> of the longest fibonacci-like subsequence of <code>A</code>.  If one does not exist, return 0.</p>
<p>(<em>Recall that a subsequence is derived from another sequence <code>A</code> by deleting any number of elements (including none) from <code>A</code>, without changing the order of the remaining elements.  For example, <code>[3, 5, 8]</code> is a subsequence of <code>[3, 4, 5, 6, 7, 8]</code>.</em>)</p>
<p> </p>
<ul>
</ul>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>[1,2,3,4,5,6,7,8]
<strong>Output: </strong>5
<strong>Explanation:
</strong>The longest subsequence that is fibonacci-like: [1,2,3,5,8].
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>[1,3,7,11,12,14,18]
<strong>Output: </strong>3
<strong>Explanation</strong>:
The longest subsequence that is fibonacci-like:
[1,11,12], [3,11,14] or [7,11,18].
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ul>
<li><code>3 &lt;= A.length &lt;= 1000</code></li>
<li><code>1 &lt;= A[0] &lt; A[1] &lt; ... &lt; A[A.length - 1] &lt;= 10^9</code></li>
<li><em>(The time limit has been reduced by 50% for submissions in Java, C, and C++.)</em></li>
</ul>
</div></div>

### Solution
