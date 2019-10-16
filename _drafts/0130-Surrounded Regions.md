---
layout: post
title: 130. Surrounded Regions
category: [Leetcode]
description: 
keywords: ['Depth-first Search', 'Breadth-first Search', 'Union Find', 'Leetcode', 'Medium']
---
### [130. Surrounded Regions](https://leetcode.com/problems/surrounded-regions)

#### Tags: 'Depth-first Search', 'Breadth-first Search', 'Union Find'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a 2D board containing <code>'X'</code> and <code>'O'</code> (<strong>the letter O</strong>), capture all regions surrounded by <code>'X'</code>.</p>
<p>A region is captured by flipping all <code>'O'</code>s into <code>'X'</code>s in that surrounded region.</p>
<p><strong>Example:</strong></p>
<pre>X X X X
X O O X
X X O X
X O X X
</pre>
<p>After running your function, the board should be:</p>
<pre>X X X X
X X X X
X X X X
X O X X
</pre>
<p><strong>Explanation:</strong></p>
<p>Surrounded regions shouldn’t be on the border, which means that any <code>'O'</code> on the border of the board are not flipped to <code>'X'</code>. Any <code>'O'</code> that is not on the border and it is not connected to an <code>'O'</code> on the border will be flipped to <code>'X'</code>. Two cells are connected if they are adjacent cells connected horizontally or vertically.</p>
</div></div>

### Solution
