---
layout: post
title: 1072. Flip Columns For Maximum Number of Equal Rows
category: [Leetcode]
description: 
keywords: ['Hash Table', 'Leetcode', 'Medium']
---
### [1072. Flip Columns For Maximum Number of Equal Rows](https://leetcode.com/problems/flip-columns-for-maximum-number-of-equal-rows)

#### Tags: 'Hash Table'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a <code>matrix</code> consisting of 0s and 1s, we may choose any number of columns in the matrix and flip <strong>every</strong> cell in that column.  Flipping a cell changes the value of that cell from 0 to 1 or from 1 to 0.</p>
<p>Return the maximum number of rows that have all values equal after some number of flips.</p>
<p> </p>
<ol>
</ol>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[[0,1],[1,1]]</span>
<strong>Output: </strong><span id="example-output-1">1</span>
<strong>Explanation: </strong>After flipping no values, 1 row has all values equal.
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">[[0,1],[1,0]]</span>
<strong>Output: </strong><span id="example-output-2">2</span>
<strong>Explanation: </strong>After flipping values in the first column, both rows have equal values.
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong><span id="example-input-3-1">[[0,0,0],[0,0,1],[1,1,0]]</span>
<strong>Output: </strong><span id="example-output-3">2</span>
<strong>Explanation: </strong>After flipping values in the first two columns, the last two rows have equal values.
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= matrix.length &lt;= 300</code></li>
<li><code>1 &lt;= matrix[i].length &lt;= 300</code></li>
<li>All <code>matrix[i].length</code>'s are equal</li>
<li><code>matrix[i][j]</code> is <code>0</code> or <code>1</code></li>
</ol>
</div>
</div>
</div>
</div></div>

### Solution
