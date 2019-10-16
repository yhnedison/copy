---
layout: post
title: 823. Binary Trees With Factors
category: [Leetcode]
description: 
keywords: ['Leetcode', 'Medium']
---
### [823. Binary Trees With Factors](https://leetcode.com/problems/binary-trees-with-factors)

#### Tags: 

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array of unique integers, each integer is strictly greater than 1.</p>
<p>We make a binary tree using these integers and each number may be used for any number of times.</p>
<p>Each non-leaf node's value should be equal to the product of the values of it's children.</p>
<p>How many binary trees can we make?  Return the answer <strong>modulo 10 ** 9 + 7</strong>.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> <code>A = [2, 4]</code>
<strong>Output:</strong> 3
<strong>Explanation:</strong> We can make these trees: <code>[2], [4], [4, 2, 2]</code></pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> <code>A = [2, 4, 5, 10]</code>
<strong>Output:</strong> <code>7</code>
<strong>Explanation:</strong> We can make these trees: <code>[2], [4], [5], [10], [4, 2, 2], [10, 2, 5], [10, 5, 2]</code>.</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= A.length &lt;= 1000</code>.</li>
<li><code>2 &lt;= A[i] &lt;= 10 ^ 9</code>.</li>
</ol>
</div></div>

### Solution
