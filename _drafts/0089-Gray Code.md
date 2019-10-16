---
layout: post
title: 89. Gray Code
category: [Leetcode]
description: 
keywords: ['Backtracking', 'Leetcode', 'Medium']
---
### [89. Gray Code](https://leetcode.com/problems/gray-code)

#### Tags: 'Backtracking'

<div class="content__u3I1 question-content__JfgR"><div><p>The gray code is a binary numeral system where two successive values differ in only one bit.</p>
<p>Given a non-negative integer <em>n</em> representing the total number of bits in the code, print the sequence of gray code. A gray code sequence must begin with 0.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> 2
<strong>Output:</strong> <code>[0,1,3,2]</code>
<strong>Explanation:</strong>
00 - 0
01 - 1
11 - 3
10 - 2

For a given <em>n</em>, a gray code sequence may not be uniquely defined.
For example, [0,2,3,1] is also a valid gray code sequence.

00 - 0
10 - 2
11 - 3
01 - 1
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> 0
<strong>Output:</strong> <code>[0]
<strong>Explanation:</strong> We define the gray code sequence to begin with 0.
             A gray code sequence of <em>n</em> has size = 2<sup>n</sup>, which for <em>n</em> = 0 the size is 2<sup>0</sup> = 1.
             Therefore, for <em>n</em> = 0 the gray code sequence is [0].</code>
</pre>
</div></div>

### Solution
