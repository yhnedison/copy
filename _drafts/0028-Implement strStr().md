---
layout: post
title: 28. Implement strStr()
category: [Leetcode]
description: 
keywords: ['Two Pointers', 'String', 'Leetcode', 'Easy']
---
### [28. Implement strStr()](https://leetcode.com/problems/implement-strstr)

#### Tags: 'Two Pointers', 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>Implement <a href="http://www.cplusplus.com/reference/cstring/strstr/" target="_blank">strStr()</a>.</p>
<p>Return the index of the first occurrence of needle in haystack, or <strong>-1</strong> if needle is not part of haystack.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> haystack = "hello", needle = "ll"
<strong>Output:</strong> 2
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> haystack = "aaaaa", needle = "bba"
<strong>Output:</strong> -1
</pre>
<p><strong>Clarification:</strong></p>
<p>What should we return when <code>needle</code> is an empty string? This is a great question to ask during an interview.</p>
<p>For the purpose of this problem, we will return 0 when <code>needle</code> is an empty string. This is consistent to C's <a href="http://www.cplusplus.com/reference/cstring/strstr/" target="_blank">strstr()</a> and Java's <a href="https://docs.oracle.com/javase/7/docs/api/java/lang/String.html#indexOf(java.lang.String)" target="_blank">indexOf()</a>.</p>
</div></div>

### Solution
