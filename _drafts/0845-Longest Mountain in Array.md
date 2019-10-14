---
layout: post
category: Leetcode
description: 
keywords: ['Two Pointers', 'Leetcode', 'Medium']
---
### [845. Longest Mountain in Array](https://leetcode.com/problems/longest-mountain-in-array)

#### Tags: 'Two Pointers'

<div class="content__u3I1 question-content__JfgR"><div><p>Let's call any (contiguous) subarray B (of A) a <em>mountain</em> if the following properties hold:</p>
<ul>
<li><code>B.length &gt;= 3</code></li>
<li>There exists some <code>0 &lt; i &lt; B.length - 1</code> such that <code>B[0] &lt; B[1] &lt; ... B[i-1] &lt; B[i] &gt; B[i+1] &gt; ... &gt; B[B.length - 1]</code></li>
</ul>
<p>(Note that B could be any subarray of A, including the entire array A.)</p>
<p>Given an array <code>A</code> of integers, return the length of the longest <em>mountain</em>. </p>
<p>Return <code>0</code> if there is no mountain.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>[2,1,4,7,3,2,5]
<strong>Output: </strong>5
<strong>Explanation: </strong>The largest mountain is [1,4,7,3,2] which has length 5.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>[2,2,2]
<strong>Output: </strong>0
<strong>Explanation: </strong>There is no mountain.
</pre>
<p><strong>Note:</strong></p>
<ol>
<li><code>0 &lt;= A.length &lt;= 10000</code></li>
<li><code>0 &lt;= A[i] &lt;= 10000</code></li>
</ol>
<p><strong>Follow up:</strong></p>
<ul>
<li>Can you solve it using only one pass?</li>
<li>Can you solve it in <code>O(1)</code> space?</li>
</ul>
</div></div>

### Solution
