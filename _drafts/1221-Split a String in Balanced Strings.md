---
layout: post
title: 1221. Split a String in Balanced Strings
category: [Leetcode]
description: 
keywords: ['String', 'Greedy', 'Leetcode', 'Easy']
---
### [1221. Split a String in Balanced Strings](https://leetcode.com/problems/split-a-string-in-balanced-strings)

#### Tags: 'String', 'Greedy'

<div class="content__u3I1 question-content__JfgR"><div><p><i data-stringify-type="italic">Balanced</i> strings are those who have equal quantity of 'L' and 'R' characters.</p>
<p>Given a balanced string <code data-stringify-type="code">s</code> split it in the maximum amount of balanced strings.</p>
<p>Return the maximum amount of splitted balanced strings.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> s = "RLRRLLRLRL"
<strong>Output:</strong> 4
<strong>Explanation: </strong>s can be split into "RL", "RRLL", "RL", "RL", each substring contains same number of 'L' and 'R'.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> s = "RLLLLRRRLR"
<strong>Output:</strong> 3
<strong>Explanation: </strong>s can be split into "RL", "LLLRRR", "LR", each substring contains same number of 'L' and 'R'.
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> s = "LLLLRRRR"
<strong>Output:</strong> 1
<strong>Explanation: </strong>s can be split into "LLLLRRRR".
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= s.length &lt;= 1000</code></li>
<li><code>s[i] = 'L' or 'R'</code></li>
</ul>
</div></div>

### Solution
