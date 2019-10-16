---
layout: post
title: 741. Cherry Pickup
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Hard']
---
### [741. Cherry Pickup](https://leetcode.com/problems/cherry-pickup)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>In a N x N <code>grid</code> representing a field of cherries, each cell is one of three possible integers.</p>
<p> </p>
<ul>
<li>0 means the cell is empty, so you can pass through;</li>
<li>1 means the cell contains a cherry, that you can pick up and pass through;</li>
<li>-1 means the cell contains a thorn that blocks your way.</li>
</ul>
<p> </p>
<p>Your task is to collect maximum number of cherries possible by following the rules below:</p>
<p> </p>
<ul>
<li>Starting at the position (0, 0) and reaching (N-1, N-1) by moving right or down through valid path cells (cells with value 0 or 1);</li>
<li>After reaching (N-1, N-1), returning to (0, 0) by moving left or up through valid path cells;</li>
<li>When passing through a path cell containing a cherry, you pick it up and the cell becomes an empty cell (0);</li>
<li>If there is no valid path between (0, 0) and (N-1, N-1), then no cherries can be collected.</li>
</ul>
<p> </p>
<p> </p>
<p><b>Example 1:</b></p>
<pre><b>Input:</b> grid =
[[0, 1, -1],
 [1, 0, -1],
 [1, 1,  1]]
<b>Output:</b> 5
<b>Explanation:</b> 
The player started at (0, 0) and went down, down, right right to reach (2, 2).
4 cherries were picked up during this single trip, and the matrix becomes [[0,1,-1],[0,0,-1],[0,0,0]].
Then, the player went left, up, up, left to return home, picking up one more cherry.
The total number of cherries picked up is 5, and this is the maximum possible.
</pre>
<p> </p>
<p><b>Note:</b></p>
<ul>
<li><code>grid</code> is an <code>N</code> by <code>N</code> 2D array, with <code>1 &lt;= N &lt;= 50</code>.</li>
<li>Each <code>grid[i][j]</code> is an integer in the set <code>{-1, 0, 1}</code>.</li>
<li>It is guaranteed that grid[0][0] and grid[N-1][N-1] are not -1.</li>
<li>
<p> </p>
</li>
</ul>
</div></div>

### Solution
