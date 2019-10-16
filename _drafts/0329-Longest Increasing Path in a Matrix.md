---
layout: post
title: 329. Longest Increasing Path in a Matrix
category: [Leetcode]
description: 
keywords: ['Depth-first Search', 'Topological Sort', 'Memoization', 'Leetcode', 'Hard']
---
### [329. Longest Increasing Path in a Matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix)

#### Tags: 'Depth-first Search', 'Topological Sort', 'Memoization'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an integer matrix, find the length of the longest increasing path.</p>
<p>From each cell, you can either move to four directions: left, right, up or down. You may NOT move diagonally or move outside of the boundary (i.e. wrap-around is not allowed).</p>
<p><b>Example 1:</b></p>
<pre><strong>Input: </strong>nums = 
[
  [<font color="red">9</font>,9,4],
  [<font color="red">6</font>,6,8],
  [<font color="red">2</font>,<font color="red">1</font>,1]
] 
<strong>Output:</strong> 4 
<strong>Explanation:</strong> The longest increasing path is <code>[1, 2, 6, 9]</code>.
</pre>
<p><b>Example 2:</b></p>
<pre><strong>Input:</strong> nums = 
[
  [<font color="red">3</font>,<font color="red">4</font>,<font color="red">5</font>],
  [3,2,<font color="red">6</font>],
  [2,2,1]
] 
<strong>Output: </strong>4 
<strong>Explanation: </strong>The longest increasing path is <code>[3, 4, 5, 6]</code>. Moving diagonally is not allowed.
</pre>
</div></div>

### Solution
