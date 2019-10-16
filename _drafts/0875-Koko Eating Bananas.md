---
layout: post
title: 875. Koko Eating Bananas
category: [Leetcode]
description: 
keywords: ['Binary Search', 'Leetcode', 'Medium']
---
### [875. Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas)

#### Tags: 'Binary Search'

<div class="content__u3I1 question-content__JfgR"><div><p>Koko loves to eat bananas.  There are <code>N</code> piles of bananas, the <code>i</code>-th pile has <code>piles[i]</code> bananas.  The guards have gone and will come back in <code>H</code> hours.</p>
<p>Koko can decide her bananas-per-hour eating speed of <code>K</code>.  Each hour, she chooses some pile of bananas, and eats K bananas from that pile.  If the pile has less than <code>K</code> bananas, she eats all of them instead, and won't eat any more bananas during this hour.</p>
<p>Koko likes to eat slowly, but still wants to finish eating all the bananas before the guards come back.</p>
<p>Return the minimum integer <code>K</code> such that she can eat all the bananas within <code>H</code> hours.</p>
<p> </p>
<ul>
</ul>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>piles = <span id="example-input-1-1">[3,6,7,11]</span>, H = <span id="example-input-1-2">8</span>
<strong>Output: </strong><span id="example-output-1">4</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>piles = <span id="example-input-2-1">[30,11,23,4,20]</span>, H = <span id="example-input-2-2">5</span>
<strong>Output: </strong><span id="example-output-2">30</span>
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong>piles = <span id="example-input-3-1">[30,11,23,4,20]</span>, H = <span id="example-input-3-2">6</span>
<strong>Output: </strong><span id="example-output-3">23</span>
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ul>
<li><code>1 &lt;= piles.length &lt;= 10^4</code></li>
<li><code>piles.length &lt;= H &lt;= 10^9</code></li>
<li><code>1 &lt;= piles[i] &lt;= 10^9</code></li>
</ul>
</div>
</div>
</div>
</div></div>

### Solution
