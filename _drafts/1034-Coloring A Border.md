---
layout: post
category: Leetcode
description: 
keywords: ['Depth-first Search', 'Leetcode', 'Medium']
---
### [1034. Coloring A Border](https://leetcode.com/problems/coloring-a-border)

#### Tags: 'Depth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a 2-dimensional <code>grid</code> of integers, each value in the grid represents the color of the grid square at that location.</p>
<p>Two squares belong to the same <em>connected component</em> if and only if they have the same color and are next to each other in any of the 4 directions.</p>
<p>The <em>border</em> of a connected component is all the squares in the connected component that are either 4-directionally adjacent to a square not in the component, or on the boundary of the grid (the first or last row or column).</p>
<p>Given a square at location <code>(r0, c0)</code> in the grid and a <code>color</code>, color the border of the connected component of that square with the given <code>color</code>, and return the final <code>grid</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>grid = <span id="example-input-1-1">[[1,1],[1,2]]</span>, r0 = <span id="example-input-1-2">0</span>, c0 = <span id="example-input-1-3">0</span>, color = <span id="example-input-1-4">3</span>
<strong>Output: </strong><span id="example-output-1">[[3, 3], [3, 2]]</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>grid = <span id="example-input-2-1">[[1,2,2],[2,3,2]]</span>, r0 = <span id="example-input-2-2">0</span>, c0 = <span id="example-input-2-3">1</span>, color = <span id="example-input-2-4">3</span>
<strong>Output: </strong><span id="example-output-2">[[1, 3, 3], [2, 3, 3]]</span>
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong>grid = <span id="example-input-3-1">[[1,1,1],[1,1,1],[1,1,1]]</span>, r0 = <span id="example-input-3-2">1</span>, c0 = <span id="example-input-3-3">1</span>, color = <span id="example-input-3-4">2</span>
<strong>Output: </strong><span id="example-output-3">[[2, 2, 2], [2, 1, 2], [2, 2, 2]]</span></pre>
</div>
</div>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= grid.length &lt;= 50</code></li>
<li><code>1 &lt;= grid[0].length &lt;= 50</code></li>
<li><code>1 &lt;= grid[i][j] &lt;= 1000</code></li>
<li><code>0 &lt;= r0 &lt; grid.length</code></li>
<li><code>0 &lt;= c0 &lt; grid[0].length</code></li>
<li><code>1 &lt;= color &lt;= 1000</code></li>
</ol></div></div>

### Solution
