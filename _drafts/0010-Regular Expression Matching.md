---
layout: post
title: 10. Regular Expression Matching
category: [Leetcode]
description: 
keywords: ['String', 'Dynamic Programming', 'Backtracking', 'Leetcode', 'Hard']
---
### [10. Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching)

#### Tags: 'String', 'Dynamic Programming', 'Backtracking'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an input string (<code>s</code>) and a pattern (<code>p</code>), implement regular expression matching with support for <code>'.'</code> and <code>'*'</code>.</p>
<pre>'.' Matches any single character.
'*' Matches zero or more of the preceding element.
</pre>
<p>The matching should cover the <strong>entire</strong> input string (not partial).</p>
<p><strong>Note:</strong></p>
<ul>
<li><code>s</code> could be empty and contains only lowercase letters <code>a-z</code>.</li>
<li><code>p</code> could be empty and contains only lowercase letters <code>a-z</code>, and characters like <code>.</code> or <code>*</code>.</li>
</ul>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong>
s = "aa"
p = "a"
<strong>Output:</strong> false
<strong>Explanation:</strong> "a" does not match the entire string "aa".
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong>
s = "aa"
p = "a*"
<strong>Output:</strong> true
<strong>Explanation:</strong> '*' means zero or more of the preceding element, 'a'. Therefore, by repeating 'a' once, it becomes "aa".
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong>
s = "ab"
p = ".*"
<strong>Output:</strong> true
<strong>Explanation:</strong> ".*" means "zero or more (*) of any character (.)".
</pre>
<p><strong>Example 4:</strong></p>
<pre><strong>Input:</strong>
s = "aab"
p = "c*a*b"
<strong>Output:</strong> true
<strong>Explanation:</strong> c can be repeated 0 times, a can be repeated 1 time. Therefore, it matches "aab".
</pre>
<p><strong>Example 5:</strong></p>
<pre><strong>Input:</strong>
s = "mississippi"
p = "mis*is*p*."
<strong>Output:</strong> false
</pre>
</div></div>

### Solution
