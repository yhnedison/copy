---
layout: post
category: Leetcode
description: 
keywords: ['Linked List', 'Leetcode', 'Medium']
---
### [817. Linked List Components](https://leetcode.com/problems/linked-list-components)

#### Tags: 'Linked List'

<div class="content__u3I1 question-content__JfgR"><div><p>We are given <code>head</code>, the head node of a linked list containing <strong>unique integer values</strong>.</p>
<p>We are also given the list <code>G</code>, a subset of the values in the linked list.</p>
<p>Return the number of connected components in <code>G</code>, where two values are connected if they appear consecutively in the linked list.</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> 
head: 0-&gt;1-&gt;2-&gt;3
G = [0, 1, 3]
<strong>Output:</strong> 2
<strong>Explanation:</strong> 
0 and 1 are connected, so [0, 1] and [3] are the two connected components.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> 
head: 0-&gt;1-&gt;2-&gt;3-&gt;4
G = [0, 3, 1, 4]
<strong>Output:</strong> 2
<strong>Explanation:</strong> 
0 and 1 are connected, 3 and 4 are connected, so [0, 1] and [3, 4] are the two connected components.
</pre>
<p><strong>Note: </strong></p>
<ul>
<li>If <code>N</code> is the length of the linked list given by <code>head</code>, <code>1 &lt;= N &lt;= 10000</code>.</li>
<li>The value of each node in the linked list will be in the range<code> [0, N - 1]</code>.</li>
<li><code>1 &lt;= G.length &lt;= 10000</code>.</li>
<li><code>G</code> is a subset of all values in the linked list.</li>
</ul>
</div></div>

### Solution
