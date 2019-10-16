---
layout: post
title: 444. Sequence Reconstruction
category: [Leetcode]
description: 
keywords: ['Graph', 'Topological Sort', 'Leetcode', 'Medium']
---
### [444. Sequence Reconstruction](https://leetcode.com/problems/sequence-reconstruction)

#### Tags: 'Graph', 'Topological Sort'

<div class="content__u3I1 question-content__JfgR"><div><p>Check whether the original sequence <code>org</code> can be uniquely reconstructed from the sequences in <code>seqs</code>. The <code>org</code> sequence is a permutation of the integers from 1 to n, with 1 ≤ n ≤ 10<sup>4</sup>. Reconstruction means building a shortest common supersequence of the sequences in <code>seqs</code> (i.e., a shortest sequence so that all sequences in <code>seqs</code> are subsequences of it). Determine whether there is only one sequence that can be reconstructed from <code>seqs</code> and it is the <code>org</code> sequence.</p>
<p><b>Example 1:</b>
</p><pre><b>Input:</b>
org: [1,2,3], seqs: [[1,2],[1,3]]

<b>Output:</b>
false

<b>Explanation:</b>
[1,2,3] is not the only one sequence that can be reconstructed, because [1,3,2] is also a valid sequence that can be reconstructed.
</pre>
<p></p>
<p><b>Example 2:</b>
</p><pre><b>Input:</b>
org: [1,2,3], seqs: [[1,2]]

<b>Output:</b>
false

<b>Explanation:</b>
The reconstructed sequence can only be [1,2].
</pre>
<p></p>
<p><b>Example 3:</b>
</p><pre><b>Input:</b>
org: [1,2,3], seqs: [[1,2],[1,3],[2,3]]

<b>Output:</b>
true

<b>Explanation:</b>
The sequences [1,2], [1,3], and [2,3] can uniquely reconstruct the original sequence [1,2,3].
</pre>
<p></p>
<p><b>Example 4:</b>
</p><pre><b>Input:</b>
org: [4,1,5,2,6,3], seqs: [[5,2,6,3],[4,1,5,2]]

<b>Output:</b>
true
</pre>
<p></p>
<p>
<b><font color="red">UPDATE (2017/1/8):</font></b><br/>
The <i>seqs</i> parameter had been changed to a list of list of strings (instead of a 2d array of strings). Please reload the code definition to get the latest changes.
</p></div></div>

### Solution
