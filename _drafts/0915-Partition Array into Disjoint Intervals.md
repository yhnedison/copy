---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Leetcode', 'Medium']
---
### [915. Partition Array into Disjoint Intervals](https://leetcode.com/problems/partition-array-into-disjoint-intervals)

#### Tags: 'Array'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array <code>A</code>, partition it into two (contiguous) subarrays <code>left</code> and <code>right</code> so that:</p>
<ul>
<li>Every element in <code>left</code> is less than or equal to every element in <code>right</code>.</li>
<li><code>left</code> and <code>right</code> are non-empty.</li>
<li><code>left</code> has the smallest possible size.</li>
</ul>
<p>Return the <strong>length</strong> of <code>left</code> after such a partitioning.  It is guaranteed that such a partitioning exists.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[5,0,3,8,6]</span>
<strong>Output: </strong><span id="example-output-1">3</span>
<strong>Explanation: </strong>left = [5,0,3], right = [8,6]
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">[1,1,1,0,6,12]</span>
<strong>Output: </strong><span id="example-output-2">4</span>
<strong>Explanation: </strong>left = [1,1,1,0], right = [6,12]
</pre>
<p> </p>
</div>
<p><strong>Note:</strong></p>
<ol>
<li><code>2 &lt;= A.length &lt;= 30000</code></li>
<li><code>0 &lt;= A[i] &lt;= 10^6</code></li>
<li>It is guaranteed there is at least one way to partition <code>A</code> as described.</li>
</ol>
<div>
<div> </div>
</div>
</div></div>

### Solution
