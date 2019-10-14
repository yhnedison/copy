---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Dynamic Programming', 'Backtracking', 'Greedy', 'Leetcode', 'Hard']
---
### [44. Wildcard Matching](https://leetcode.com/problems/wildcard-matching)

#### Tags: 'String', 'Dynamic Programming', 'Backtracking', 'Greedy'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an input string (<code>s</code>) and a pattern (<code>p</code>), implement wildcard pattern matching with support for <code>'?'</code> and <code>'*'</code>.</p>
<pre>'?' Matches any single character.
'*' Matches any sequence of characters (including the empty sequence).
</pre>
<p>The matching should cover the <strong>entire</strong> input string (not partial).</p>
<p><strong>Note:</strong></p>
<ul>
<li><code>s</code> could be empty and contains only lowercase letters <code>a-z</code>.</li>
<li><code>p</code> could be empty and contains only lowercase letters <code>a-z</code>, and characters like <code><font face="monospace">?</font></code> or <code>*</code>.</li>
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
p = "*"
<strong>Output:</strong> true
<strong>Explanation:</strong> '*' matches any sequence.
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong>
s = "cb"
p = "?a"
<strong>Output:</strong> false
<strong>Explanation:</strong> '?' matches 'c', but the second letter is 'a', which does not match 'b'.
</pre>
<p><strong>Example 4:</strong></p>
<pre><strong>Input:</strong>
s = "adceb"
p = "*a*b"
<strong>Output:</strong> true
<strong>Explanation:</strong> The first '*' matches the empty sequence, while the second '*' matches the substring "dce".
</pre>
<p><strong>Example 5:</strong></p>
<pre><strong>Input:</strong>
s = "acdcb"
p = "a*c?b"
<strong>Output:</strong> false
</pre>
</div></div>

### Solution
