---
layout: post
title: 833. Find And Replace in String
category: [Leetcode]
description: 
keywords: ['String', 'Leetcode', 'Medium']
---
### [833. Find And Replace in String](https://leetcode.com/problems/find-and-replace-in-string)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>To some string <code>S</code>, we will perform some replacement operations that replace groups of letters with new ones (not necessarily the same size).</p>
<p>Each replacement operation has <code>3</code> parameters: a starting index <code>i</code>, a source word <code>x</code> and a target word <code>y</code>.  The rule is that if <code><font face="monospace">x</font></code> starts at position <code>i</code> in the <strong>original</strong> <strong>string</strong> <strong><code>S</code></strong>, then we will replace that occurrence of <code>x</code> with <code>y</code>.  If not, we do nothing.</p>
<p>For example, if we have <code>S = "abcd"</code> and we have some replacement operation <code>i = 2, x = "cd", y = "ffff"</code>, then because <code>"cd"</code> starts at position <code><font face="monospace">2</font></code> in the original string <code>S</code>, we will replace it with <code>"ffff"</code>.</p>
<p>Using another example on <code>S = "abcd"</code>, if we have both the replacement operation <code>i = 0, x = "ab", y = "eee"</code>, as well as another replacement operation <code>i = 2, x = "ec", y = "ffff"</code>, this second operation does nothing because in the original string <code>S[2] = 'c'</code>, which doesn't match <code>x[0] = 'e'</code>.</p>
<p>All these operations occur simultaneously.  It's guaranteed that there won't be any overlap in replacement: for example, <code>S = "abc", indexes = [0, 1], sources = ["ab","bc"]</code> is not a valid test case.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>S = "abcd", indexes = [0,2], sources = ["a","cd"], targets = ["eee","ffff"]
<strong>Output: </strong>"eeebffff"
<strong>Explanation:</strong> "a" starts at index 0 in S, so it's replaced by "eee".
"cd" starts at index 2 in S, so it's replaced by "ffff".
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>S = "abcd", indexes = [0,2], sources = ["ab","ec"], targets = ["eee","ffff"]
<strong>Output: </strong>"eeecd"
<strong>Explanation:</strong> "ab" starts at index 0 in S, so it's replaced by "eee". 
"ec" doesn't starts at index 2 in the <strong>original</strong> S, so we do nothing.
</pre>
<p>Notes:</p>
<ol>
<li><code>0 &lt;= indexes.length = sources.length = targets.length &lt;= 100</code></li>
<li><code>0 &lt; indexes[i] &lt; S.length &lt;= 1000</code></li>
<li>All characters in given inputs are lowercase letters.</li>
</ol>
<p> </p>
</div></div>

### Solution
