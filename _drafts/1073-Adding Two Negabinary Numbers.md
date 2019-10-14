---
layout: post
category: Leetcode
description: 
keywords: ['Math', 'Leetcode', 'Medium']
---
### [1073. Adding Two Negabinary Numbers](https://leetcode.com/problems/adding-two-negabinary-numbers)

#### Tags: 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>Given two numbers <code>arr1</code> and <code>arr2</code> in base <strong>-2</strong>, return the result of adding them together.</p>
<p>Each number is given in <em>array format</em>:  as an array of 0s and 1s, from most significant bit to least significant bit.  For example, <code>arr = [1,1,0,1]</code> represents the number <code>(-2)^3 + (-2)^2 + (-2)^0 = -3</code>.  A number <code>arr</code> in <em>array format</em> is also guaranteed to have no leading zeros: either <code>arr == [0]</code> or <code>arr[0] == 1</code>.</p>
<p>Return the result of adding <code>arr1</code> and <code>arr2</code> in the same format: as an array of 0s and 1s with no leading zeros.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>arr1 = <span id="example-input-1-1">[1,1,1,1,1]</span>, arr2 = <span id="example-input-1-2">[1,0,1]</span>
<strong>Output: </strong><span id="example-output-1">[1,0,0,0,0]
</span><strong>Explanation: </strong>arr1 represents 11, arr2 represents 5, the output represents 16.
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= arr1.length &lt;= 1000</code></li>
<li><code>1 &lt;= arr2.length &lt;= 1000</code></li>
<li><code>arr1</code> and <code>arr2</code> have no leading zeros</li>
<li><code>arr1[i]</code> is <code>0</code> or <code>1</code></li>
<li><code>arr2[i]</code> is <code>0</code> or <code>1</code></li>
</ol>
</div></div>

### Solution
