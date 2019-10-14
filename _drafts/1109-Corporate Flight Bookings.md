---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Math', 'Leetcode', 'Medium']
---
### [1109. Corporate Flight Bookings](https://leetcode.com/problems/corporate-flight-bookings)

#### Tags: 'Array', 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>There are <code>n</code> flights, and they are labeled from <code>1</code> to <code>n</code>.</p>
<p>We have a list of flight bookings.  The <code>i</code>-th booking <code>bookings[i] = [i, j, k]</code> means that we booked <code>k</code> seats from flights labeled <code>i</code> to <code>j</code> inclusive.</p>
<p>Return an array <code>answer</code> of length <code>n</code>, representing the number of seats booked on each flight in order of their label.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> bookings = [[1,2,10],[2,3,20],[2,5,25]], n = 5
<strong>Output:</strong> [10,55,45,25,25]
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= bookings.length &lt;= 20000</code></li>
<li><code>1 &lt;= bookings[i][0] &lt;= bookings[i][1] &lt;= n &lt;= 20000</code></li>
<li><code>1 &lt;= bookings[i][2] &lt;= 10000</code></li>
</ul></div></div>

### Solution
