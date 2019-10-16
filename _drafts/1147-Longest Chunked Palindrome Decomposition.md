---
layout: post
title: 1147. Longest Chunked Palindrome Decomposition
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Rolling Hash', 'Leetcode', 'Hard']
---
### [1147. Longest Chunked Palindrome Decomposition](https://leetcode.com/problems/longest-chunked-palindrome-decomposition)

#### Tags: 'Dynamic Programming', 'Rolling Hash'

<div class="content__u3I1 question-content__JfgR"><div><p>Return the largest possible <code>k</code> such that there exists <code>a_1, a_2, ..., a_k</code> such that:</p>
<ul>
<li>Each <code>a_i</code> is a non-empty string;</li>
<li>Their concatenation <code>a_1 + a_2 + ... + a_k</code> is equal to <code>text</code>;</li>
<li>For all <code>1 &lt;= i &lt;= k</code>,  <code>a_i = a_{k+1 - i}</code>.</li>
</ul>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> text = "ghiabcdefhelloadamhelloabcdefghi"
<strong>Output:</strong> 7
<strong>Explanation:</strong> We can split the string on "(ghi)(abcdef)(hello)(adam)(hello)(abcdef)(ghi)".
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> text = "merchant"
<strong>Output:</strong> 1
<strong>Explanation:</strong> We can split the string on "(merchant)".
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> text = "antaprezatepzapreanta"
<strong>Output:</strong> 11
<strong>Explanation:</strong> We can split the string on "(a)(nt)(a)(pre)(za)(tpe)(za)(pre)(a)(nt)(a)".
</pre>
<p><strong>Example 4:</strong></p>
<pre><strong>Input:</strong> text = "aaa"
<strong>Output:</strong> 3
<strong>Explanation:</strong> We can split the string on "(a)(a)(a)".
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>text</code> consists only of lowercase English characters.</li>
<li><code>1 &lt;= text.length &lt;= 1000</code></li>
</ul></div></div>

### Solution
