---
layout: post
title: 1223. Dice Roll Simulation
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Medium']
---
### [1223. Dice Roll Simulation](https://leetcode.com/problems/dice-roll-simulation)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>A die simulator generates a random number from 1 to 6 for each roll. You introduced a constraint to the generator such that it cannot roll the number <code>i</code> more than <code>rollMax[i]</code> (1-indexed) <strong>consecutive</strong> times. </p>
<p>Given an array of integers <code>rollMax</code> and an integer <code>n</code>, return the number of distinct sequences that can be obtained with exact <code>n</code> rolls.</p>
<p>Two sequences are considered different if at least one element differs from each other. Since the answer may be too large, return it modulo <code>10^9 + 7</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> n = 2, rollMax = [1,1,2,2,2,3]
<strong>Output:</strong> 34
<strong>Explanation:</strong> There will be 2 rolls of die, if there are no constraints on the die, there are 6 * 6 = 36 possible combinations. In this case, looking at rollMax array, the numbers 1 and 2 appear at most once consecutively, therefore sequences (1,1) and (2,2) cannot occur, so the final answer is 36-2 = 34.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> n = 2, rollMax = [1,1,1,1,1,1]
<strong>Output:</strong> 30
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> n = 3, rollMax = [1,1,1,2,2,3]
<strong>Output:</strong> 181
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= n &lt;= 5000</code></li>
<li><code>rollMax.length == 6</code></li>
<li><code>1 &lt;= rollMax[i] &lt;= 15</code></li>
</ul>
</div></div>

### Solution
