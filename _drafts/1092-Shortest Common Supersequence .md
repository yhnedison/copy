---
layout: post
title: 1092. Shortest Common Supersequence 
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Hard']
---
### [1092. Shortest Common Supersequence ](https://leetcode.com/problems/shortest-common-supersequence)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>Given two strings <code>str1</code> and <code>str2</code>, return the shortest string that has both <code>str1</code> and <code>str2</code> as subsequences.  If multiple answers exist, you may return any of them.</p>
<p><em>(A string S is a subsequence of string T if deleting some number of characters from T (possibly 0, and the characters are chosen <u>anywhere</u> from T) results in the string S.)</em></p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>str1 = <span id="example-input-1-1">"abac"</span>, str2 = <span id="example-input-1-2">"cab"</span>
<strong>Output: </strong><span id="example-output-1">"cabac"</span>
<strong>Explanation: </strong>
str1 = "abac" is a subsequence of "cabac" because we can delete the first "c".
str2 = "cab" is a subsequence of "cabac" because we can delete the last "ac".
The answer provided is the shortest such string that satisfies these properties.
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= str1.length, str2.length &lt;= 1000</code></li>
<li><code>str1</code> and <code>str2</code> consist of lowercase English letters.</li>
</ol>
</div></div>

### Solution
