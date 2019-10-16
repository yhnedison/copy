---
layout: post
title: 474. Ones and Zeroes
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Medium']
---
### [474. Ones and Zeroes](https://leetcode.com/problems/ones-and-zeroes)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>In the computer world, use restricted resource you have to generate maximum benefit is what we always want to pursue.</p>
<p>For now, suppose you are a dominator of <b>m</b> <code>0s</code> and <b>n</b> <code>1s</code> respectively. On the other hand, there is an array with strings consisting of only <code>0s</code> and <code>1s</code>.</p>
<p>Now your task is to find the maximum number of strings that you can form with given <b>m</b> <code>0s</code> and <b>n</b> <code>1s</code>. Each <code>0</code> and <code>1</code> can be used at most <b>once</b>.</p>
<p><b>Note:</b></p>
<ol>
<li>The given numbers of <code>0s</code> and <code>1s</code> will both not exceed <code>100</code></li>
<li>The size of given string array won't exceed <code>600</code>.</li>
</ol>
<p> </p>
<p><b>Example 1:</b></p>
<pre><b>Input:</b> Array = {"10", "0001", "111001", "1", "0"}, m = 5, n = 3
<b>Output:</b> 4

<b>Explanation:</b> This are totally 4 strings can be formed by the using of 5 0s and 3 1s, which are “10,”0001”,”1”,”0”
</pre>
<p> </p>
<p><b>Example 2:</b></p>
<pre><b>Input:</b> Array = {"10", "0", "1"}, m = 1, n = 1
<b>Output:</b> 2

<b>Explanation:</b> You could form "10", but then you'd have nothing left. Better form "0" and "1".
</pre>
<p> </p>
</div></div>

### Solution
