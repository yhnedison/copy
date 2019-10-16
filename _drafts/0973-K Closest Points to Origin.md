---
layout: post
title: 973. K Closest Points to Origin
category: [Leetcode]
description: 
keywords: ['Divide and Conquer', 'Heap', 'Sort', 'Leetcode', 'Medium']
---
### [973. K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin)

#### Tags: 'Divide and Conquer', 'Heap', 'Sort'

<div class="content__u3I1 question-content__JfgR"><div><p>We have a list of <code>points</code> on the plane.  Find the <code>K</code> closest points to the origin <code>(0, 0)</code>.</p>
<p>(Here, the distance between two points on a plane is the Euclidean distance.)</p>
<p>You may return the answer in any order.  The answer is guaranteed to be unique (except for the order that it is in.)</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>points = <span id="example-input-1-1">[[1,3],[-2,2]]</span>, K = <span id="example-input-1-2">1</span>
<strong>Output: </strong><span id="example-output-1">[[-2,2]]</span>
<strong>Explanation: </strong>
The distance between (1, 3) and the origin is sqrt(10).
The distance between (-2, 2) and the origin is sqrt(8).
Since sqrt(8) &lt; sqrt(10), (-2, 2) is closer to the origin.
We only want the closest K = 1 points from the origin, so the answer is just [[-2,2]].
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>points = <span id="example-input-2-1">[[3,3],[5,-1],[-2,4]]</span>, K = <span id="example-input-2-2">2</span>
<strong>Output: </strong><span id="example-output-2">[[3,3],[-2,4]]</span>
(The answer [[-2,4],[3,3]] would also be accepted.)
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= K &lt;= points.length &lt;= 10000</code></li>
<li><code>-10000 &lt; points[i][0] &lt; 10000</code></li>
<li><code>-10000 &lt; points[i][1] &lt; 10000</code></li>
</ol>
</div>
</div></div></div>

### Solution
