---
layout: post
category: Leetcode
description: 
keywords: ['Math', 'Leetcode', 'Medium']
---
### [1006. Clumsy Factorial](https://leetcode.com/problems/clumsy-factorial)

#### Tags: 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>Normally, the factorial of a positive integer <code>n</code> is the product of all positive integers less than or equal to <code>n</code>.  For example, <code>factorial(10) = 10 * 9 * 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1</code>.</p>
<p>We instead make a <em>clumsy factorial:</em> using the integers in decreasing order, we swap out the multiply operations for a fixed rotation of operations: multiply (*), divide (/), add (+) and subtract (-) in this order.</p>
<p>For example, <code>clumsy(10) = 10 * 9 / 8 + 7 - 6 * 5 / 4 + 3 - 2 * 1</code>.  However, these operations are still applied using the usual order of operations of arithmetic: we do all multiplication and division steps before any addition or subtraction steps, and multiplication and division steps are processed left to right.</p>
<p>Additionally, the division that we use is <em>floor division</em> such that <code>10 * 9 / 8</code> equals <code>11</code>.  This guarantees the result is an integer.</p>
<p><code><font face="sans-serif, Arial, Verdana, Trebuchet MS">Implement the </font>clumsy</code> function as defined above: given an integer <code>N</code>, it returns the clumsy factorial of <code>N</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>4
<strong>Output:</strong> 7
<strong>Explanation:</strong> 7 = 4 * 3 / 2 + 1
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">10
</span><strong>Output: </strong><span id="example-output-1">12
</span><strong>Explanation: </strong>12 = 10 * 9 / 8 + 7 - 6 * 5 / 4 + 3 - 2 * 1
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= N &lt;= 10000</code></li>
<li><code>-2^31 &lt;= answer &lt;= 2^31 - 1</code>  (The answer is guaranteed to fit within a 32-bit integer.)</li>
</ol>
</div></div>

### Solution
