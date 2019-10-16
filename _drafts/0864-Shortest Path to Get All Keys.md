---
layout: post
title: 864. Shortest Path to Get All Keys
category: [Leetcode]
description: 
keywords: ['Heap', 'Breadth-first Search', 'Leetcode', 'Hard']
---
### [864. Shortest Path to Get All Keys](https://leetcode.com/problems/shortest-path-to-get-all-keys)

#### Tags: 'Heap', 'Breadth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>We are given a 2-dimensional <code>grid</code>. <code>"."</code> is an empty cell, <code>"#"</code> is a wall, <code>"@"</code> is the starting point, (<code>"a"</code>, <code>"b"</code>, ...) are keys, and (<code>"A"</code>, <code>"B"</code>, ...) are locks.</p>
<p>We start at the starting point, and one move consists of walking one space in one of the 4 cardinal directions.  We cannot walk outside the grid, or walk into a wall.  If we walk over a key, we pick it up.  We can't walk over a lock unless we have the corresponding key.</p>
<p>For some <font face="monospace">1 &lt;= K &lt;= 6</font>, there is exactly one lowercase and one uppercase letter of the first <code>K</code> letters of the English alphabet in the grid.  This means that there is exactly one key for each lock, and one lock for each key; and also that the letters used to represent the keys and locks were chosen in the same order as the English alphabet.</p>
<p>Return the lowest number of moves to acquire all keys.  If it's impossible, return <code>-1</code>.</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">["@.a.#","###.#","b.A.B"]</span>
<strong>Output: </strong><span id="example-output-1">8</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">["@..aA","..B#.","....b"]</span>
<strong>Output: </strong><span id="example-output-2">6</span>
</pre>
</div>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= grid.length &lt;= 30</code></li>
<li><code>1 &lt;= grid[0].length &lt;= 30</code></li>
<li><code>grid[i][j]</code> contains only<code> '.'</code>, <code>'#'</code>, <code>'@'</code>, <code>'a'-</code><code>'f</code><code>'</code> and <code>'A'-'F'</code></li>
<li>The number of keys is in <code>[1, 6]</code>.  Each key has a different letter and opens exactly one lock.</li>
</ol>
</div>
</div></div>

### Solution
