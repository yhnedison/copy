---
layout: post
category: Leetcode
description: 
keywords: ['Breadth-first Search', 'Leetcode', 'Medium']
---
### [1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix)

#### Tags: 'Breadth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>In an N by N square grid, each cell is either empty (0) or blocked (1).</p>
<p>A <em>clear path from top-left to bottom-right</em> has length <code>k</code> if and only if it is composed of cells <code>C_1, C_2, ..., C_k</code> such that:</p>
<ul>
<li>Adjacent cells <code>C_i</code> and <code>C_{i+1}</code> are connected 8-directionally (ie., they are different and share an edge or corner)</li>
<li><code>C_1</code> is at location <code>(0, 0)</code> (ie. has value <code>grid[0][0]</code>)</li>
<li><code>C_k</code> is at location <code>(N-1, N-1)</code> (ie. has value <code>grid[N-1][N-1]</code>)</li>
<li>If <code>C_i</code> is located at <code>(r, c)</code>, then <code>grid[r][c]</code> is empty (ie. <code>grid[r][c] == 0</code>).</li>
</ul>
<p>Return the length of the shortest such clear path from top-left to bottom-right.  If such a path does not exist, return -1.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[[0,1],[1,0]]
<img alt="" src="https://assets.leetcode.com/uploads/2019/08/04/example1_1.png" style="width: 151px; height: 152px;"/>
</span>
<strong>Output: </strong>2
<img alt="" src="https://assets.leetcode.com/uploads/2019/08/04/example1_2.png" style="width: 151px; height: 152px;"/>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">[[0,0,0],[1,1,0],[1,1,0]]
<img alt="" src="https://assets.leetcode.com/uploads/2019/08/04/example2_1.png" style="width: 151px; height: 152px;"/>
</span>
<strong>Output:</strong> 4
<img alt="" src="https://assets.leetcode.com/uploads/2019/08/04/example2_2.png" style="width: 151px; height: 152px;"/>
</pre>
<p> </p>
</div>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= grid.length == grid[0].length &lt;= 100</code></li>
<li><code>grid[r][c]</code> is <code>0</code> or <code>1</code></li>
</ol>
</div></div>

### Solution
