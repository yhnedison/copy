---
layout: post
title: 899. Orderly Queue
category: [Leetcode]
description: 
keywords: ['Math', 'String', 'Leetcode', 'Hard']
---
### [899. Orderly Queue](https://leetcode.com/problems/orderly-queue)

#### Tags: 'Math', 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>A string <code>S</code> of lowercase letters is given.  Then, we may make any number of <em>moves</em>.</p>
<p>In each move, we choose one of the first <code>K</code> letters (starting from the left), remove it, and place it at the end of the string.</p>
<p>Return the lexicographically smallest string we could have after any number of moves.</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>S = <span id="example-input-1-1">"cba"</span>, K = <span id="example-input-1-2">1</span>
<strong>Output: </strong><span id="example-output-1">"acb"</span>
<strong>Explanation: </strong>
In the first move, we move the 1st character ("c") to the end, obtaining the string "bac".
In the second move, we move the 1st character ("b") to the end, obtaining the final result "acb".
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>S = <span id="example-input-2-1">"baaca"</span>, K = <span id="example-input-2-2">3</span>
<strong>Output: </strong><span id="example-output-2">"aaabc"</span>
<strong>Explanation: </strong>
In the first move, we move the 1st character ("b") to the end, obtaining the string "aacab".
In the second move, we move the 3rd character ("c") to the end, obtaining the final result "aaabc".
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= K &lt;= S.length &lt;= 1000</code></li>
<li><code>S</code> consists of lowercase letters only.</li>
</ol>
</div>
</div>
</div></div>

### Solution
