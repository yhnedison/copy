---
layout: post
title: 984. String Without AAA or BBB
category: [Leetcode]
description: 
keywords: ['Greedy', 'Leetcode', 'Medium']
---
### [984. String Without AAA or BBB](https://leetcode.com/problems/string-without-aaa-or-bbb)

#### Tags: 'Greedy'

<div class="content__u3I1 question-content__JfgR"><div><p>Given two integers <code>A</code> and <code>B</code>, return <strong>any</strong> string <code>S</code> such that:</p>
<ul>
<li><code>S</code> has length <code>A + B</code> and contains exactly <code>A</code> <code>'a'</code> letters, and exactly <code>B</code> <code>'b'</code> letters;</li>
<li>The substring <code>'aaa'</code> does not occur in <code>S</code>;</li>
<li>The substring <code>'bbb'</code> does not occur in <code>S</code>.</li>
</ul>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>A = <span id="example-input-1-1">1</span>, B = <span id="example-input-1-2">2</span>
<strong>Output: </strong><span id="example-output-1">"abb"
</span><strong>Explanation:</strong> "abb", "bab" and "bba" are all correct answers.
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>A = <span id="example-input-2-1">4</span>, B = <span id="example-input-2-2">1</span>
<strong>Output: </strong><span id="example-output-2">"aabaa"</span></pre>
<p> </p>
</div>
<p><strong>Note:</strong></p>
<ol>
<li><code>0 &lt;= A &lt;= 100</code></li>
<li><code>0 &lt;= B &lt;= 100</code></li>
<li>It is guaranteed such an <code>S</code> exists for the given <code>A</code> and <code>B</code>.</li>
</ol>
</div></div>

### Solution
