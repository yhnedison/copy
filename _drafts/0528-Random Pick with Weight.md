---
layout: post
title: 528. Random Pick with Weight
category: [Leetcode]
description: 
keywords: ['Binary Search', 'Random', 'Leetcode', 'Medium']
---
### [528. Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight)

#### Tags: 'Binary Search', 'Random'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array <code>w</code> of positive integers, where <code>w[i]</code> describes the weight of index <code>i</code>, write a function <code>pickIndex</code> which randomly picks an index in proportion to its weight.</p>
<p>Note:</p>
<ol>
<li><code>1 &lt;= w.length &lt;= 10000</code></li>
<li><code>1 &lt;= w[i] &lt;= 10^5</code></li>
<li><code>pickIndex</code> will be called at most <code>10000</code> times.</li>
</ol>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: 
</strong><span id="example-input-1-1">["Solution","pickIndex"]
</span><span id="example-input-1-2">[[[1]],[]]</span>
<strong>Output: </strong><span id="example-output-1">[null,0]</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: 
</strong><span id="example-input-2-1">["Solution","pickIndex","pickIndex","pickIndex","pickIndex","pickIndex"]
</span><span id="example-input-2-2">[[[1,3]],[],[],[],[],[]]</span>
<strong>Output: </strong><span id="example-output-2">[null,0,1,1,1,0]</span></pre>
</div>
<p><strong>Explanation of Input Syntax:</strong></p>
<p>The input is two lists: the subroutines called and their arguments. <code>Solution</code>'s constructor has one argument, the array <code>w</code>. <code>pickIndex</code> has no arguments. Arguments are always wrapped with a list, even if there aren't any.</p>
</div></div>

### Solution
