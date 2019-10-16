---
layout: post
title: 890. Find and Replace Pattern
category: [Leetcode]
description: 
keywords: ['String', 'Leetcode', 'Medium']
---
### [890. Find and Replace Pattern](https://leetcode.com/problems/find-and-replace-pattern)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>You have a list of <code>words</code> and a <code>pattern</code>, and you want to know which words in <code>words</code> matches the pattern.</p>
<p>A word matches the pattern if there exists a permutation of letters <code>p</code> so that after replacing every letter <code>x</code> in the pattern with <code>p(x)</code>, we get the desired word.</p>
<p>(<em>Recall that a permutation of letters is a bijection from letters to letters: every letter maps to another letter, and no two letters map to the same letter.</em>)</p>
<p>Return a list of the words in <code>words</code> that match the given pattern. </p>
<p>You may return the answer in any order.</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>words = <span id="example-input-1-1">["abc","deq","mee","aqq","dkd","ccc"]</span>, pattern = <span id="example-input-1-2">"abb"</span>
<strong>Output: </strong><span id="example-output-1">["mee","aqq"]</span>
<strong><span>Explanation: </span></strong>"mee" matches the pattern because there is a permutation {a -&gt; m, b -&gt; e, ...}. 
"ccc" does not match the pattern because {a -&gt; c, b -&gt; c, ...} is not a permutation,
since a and b map to the same letter.</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ul>
<li><code>1 &lt;= words.length &lt;= 50</code></li>
<li><code>1 &lt;= pattern.length = words[i].length &lt;= 20</code></li>
</ul>
</div>
</div></div>

### Solution
