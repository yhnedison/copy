---
layout: post
category: Leetcode
description: 
keywords: ['Hash Table', 'Two Pointers', 'Leetcode', 'Medium']
---
### [930. Binary Subarrays With Sum](https://leetcode.com/problems/binary-subarrays-with-sum)

#### Tags: 'Hash Table', 'Two Pointers'

<div class="content__u3I1 question-content__JfgR"><div><p>In an array <code>A</code> of <code>0</code>s and <code>1</code>s, how many <strong>non-empty</strong> subarrays have sum <code>S</code>?</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>A = <span id="example-input-1-1">[1,0,1,0,1]</span>, S = <span id="example-input-1-2">2</span>
<strong>Output: </strong><span id="example-output-1">4</span>
<strong>Explanation: </strong>
The 4 subarrays are bolded below:
[<strong>1,0,1</strong>,0,1]
[<strong>1,0,1,0</strong>,1]
[1,<strong>0,1,0,1</strong>]
[1,0,<strong>1,0,1</strong>]
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>A.length &lt;= 30000</code></li>
<li><code>0 &lt;= S &lt;= A.length</code></li>
<li><code>A[i]</code> is either <code>0</code> or <code>1</code>.</li>
</ol></div></div>

### Solution
