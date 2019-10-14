---
layout: post
category: Leetcode
description: 
keywords: ['Math', 'Leetcode', 'Hard']
---
### [906. Super Palindromes](https://leetcode.com/problems/super-palindromes)

#### Tags: 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>Let's say a positive integer is a <em>superpalindrome</em> if it is a palindrome, and it is also the square of a palindrome.</p>
<p>Now, given two positive integers <code>L</code> and <code>R</code> (represented as strings), return the number of superpalindromes in the inclusive range <code>[L, R]</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>L = <span id="example-input-1-1">"4"</span>, R = <span id="example-input-1-2">"1000"</span>
<strong>Output: </strong>4
<span><strong>Explanation</strong>: </span>4, 9, 121, and 484 are superpalindromes.
Note that 676 is not a superpalindrome: 26 * 26 = 676, but 26 is not a palindrome.</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= len(L) &lt;= 18</code></li>
<li><code>1 &lt;= len(R) &lt;= 18</code></li>
<li><code>L</code> and <code>R</code> are strings representing integers in the range <code>[1, 10^18)</code>.</li>
<li><code>int(L) &lt;= int(R)</code></li>
</ol>
<div>
<p> </p>
</div>
</div></div>

### Solution
