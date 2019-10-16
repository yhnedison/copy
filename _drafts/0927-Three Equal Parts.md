---
layout: post
title: 927. Three Equal Parts
category: [Leetcode]
description: 
keywords: ['Math', 'Binary Search', 'Greedy', 'Leetcode', 'Hard']
---
### [927. Three Equal Parts](https://leetcode.com/problems/three-equal-parts)

#### Tags: 'Math', 'Binary Search', 'Greedy'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array <code>A</code> of <code>0</code>s and <code>1</code>s, divide the array into 3 non-empty parts such that all of these parts represent the same binary value.</p>
<p>If it is possible, return <strong>any</strong> <code>[i, j]</code> with <code>i+1 &lt; j</code>, such that:</p>
<ul>
<li><code>A[0], A[1], ..., A[i]</code> is the first part;</li>
<li><code>A[i+1], A[i+2], ..., A[j-1]</code> is the second part, and</li>
<li><code>A[j], A[j+1], ..., A[A.length - 1]</code> is the third part.</li>
<li>All three parts have equal binary value.</li>
</ul>
<p>If it is not possible, return <code>[-1, -1]</code>.</p>
<p>Note that the entire part is used when considering what binary value it represents.  For example, <code>[1,1,0]</code> represents <code>6</code> in decimal, not <code>3</code>.  Also, leading zeros are allowed, so <code>[0,1,1]</code> and <code>[1,1]</code> represent the same value.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">[1,0,1,0,1]</span>
<strong>Output: </strong><span id="example-output-1">[0,3]</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">[1,1,0,1,1]</span>
<strong>Output: </strong><span id="example-output-2">[-1,-1]</span></pre>
</div>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>3 &lt;= A.length &lt;= 30000</code></li>
<li><code>A[i] == 0</code> or <code>A[i] == 1</code></li>
</ol>
<div>
<div> </div>
</div></div></div>

### Solution
