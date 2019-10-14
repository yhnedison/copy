---
layout: post
category: Leetcode
description: 
keywords: ['Math', 'Dynamic Programming', 'Leetcode', 'Hard']
---
### [902. Numbers At Most N Given Digit Set](https://leetcode.com/problems/numbers-at-most-n-given-digit-set)

#### Tags: 'Math', 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>We have a <strong>sorted</strong> set of digits <code>D</code>, a non-empty subset of <code>{'1','2','3','4','5','6','7','8','9'}</code>.  (Note that <code>'0'</code> is not included.)</p>
<p>Now, we write numbers using these digits, using each digit as many times as we want.  For example, if <code>D = {'1','3','5'}</code>, we may write numbers such as <code>'13', '551', '1351315'</code>.</p>
<p>Return the number of positive integers that can be written (using the digits of <code>D</code>) that are less than or equal to <code>N</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>D = <span id="example-input-1-1">["1","3","5","7"]</span>, N = <span id="example-input-1-2">100</span>
<strong>Output: </strong><span id="example-output-1">20</span>
<strong>Explanation: </strong>
The 20 numbers that can be written are:
1, 3, 5, 7, 11, 13, 15, 17, 31, 33, 35, 37, 51, 53, 55, 57, 71, 73, 75, 77.
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>D = <span id="example-input-2-1">["1","4","9"]</span>, N = <span id="example-input-2-2">1000000000</span>
<strong>Output: </strong><span id="example-output-2">29523</span>
<strong>Explanation: </strong>
We can write 3 one digit numbers, 9 two digit numbers, 27 three digit numbers,
81 four digit numbers, 243 five digit numbers, 729 six digit numbers,
2187 seven digit numbers, 6561 eight digit numbers, and 19683 nine digit numbers.
In total, this is 29523 integers that can be written using the digits of D.</pre>
</div>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>D</code> is a subset of digits <code>'1'-'9'</code> in sorted order.</li>
<li><code>1 &lt;= N &lt;= 10^9</code></li>
</ol>
</div></div>

### Solution
