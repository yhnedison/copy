---
layout: post
category: Leetcode
description: 
keywords: ['Breadth-first Search', 'Graph', 'Leetcode', 'Medium']
---
### [1162. As Far from Land as Possible](https://leetcode.com/problems/as-far-from-land-as-possible)

#### Tags: 'Breadth-first Search', 'Graph'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an N x N <code>grid</code> containing only values <code>0</code> and <code>1</code>, where <code>0</code> represents water and <code>1</code> represents land, find a water cell such that its distance to the nearest land cell is maximized and return the distance.</p>
<p>The distance used in this problem is the <em>Manhattan distance</em>: the distance between two cells <code>(x0, y0)</code> and <code>(x1, y1)</code> is <code>|x0 - x1| + |y0 - y1|</code>.</p>
<p>If no land or water exists in the grid, return <code>-1</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><strong><img alt="" src="https://assets.leetcode.com/uploads/2019/05/03/1336_ex1.JPG" style="width: 185px; height: 87px;"/></strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[[1,0,1],[0,0,0],[1,0,1]]</span>
<strong>Output: </strong><span id="example-output-1">2</span>
<strong>Explanation: </strong>
The cell (1, 1) is as far as possible from all the land with distance 2.
</pre>
<p><strong>Example 2:</strong></p>
<p><strong><img alt="" src="https://assets.leetcode.com/uploads/2019/05/03/1336_ex2.JPG" style="width: 184px; height: 87px;"/></strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">[[1,0,0],[0,0,0],[0,0,0]]</span>
<strong>Output: </strong><span id="example-output-2">4</span>
<strong>Explanation: </strong>
The cell (2, 2) is as far as possible from all the land with distance 4.
</pre>
<p> </p>
<p><span><strong>Note:</strong></span></p>
<ol>
<li><span><code>1 &lt;= grid.length == grid[0].length &lt;= 100</code></span></li>
<li><span><code>grid[i][j]</code> is <code>0</code> or <code>1</code></span></li>
</ol>
</div></div>

### Solution
