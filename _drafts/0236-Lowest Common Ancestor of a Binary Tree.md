---
layout: post
title: 236. Lowest Common Ancestor of a Binary Tree
category: [Leetcode]
description: 
keywords: ['Tree', 'Leetcode', 'Medium']
---
### [236. Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree)

#### Tags: 'Tree'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a binary tree, find the lowest common ancestor (LCA) of two given nodes in the tree.</p>
<p>According to the <a href="https://en.wikipedia.org/wiki/Lowest_common_ancestor" target="_blank">definition of LCA on Wikipedia</a>: “The lowest common ancestor is defined between two nodes p and q as the lowest node in T that has both p and q as descendants (where we allow <b>a node to be a descendant of itself</b>).”</p>
<p>Given the following binary tree:  root = [3,5,1,6,2,0,8,null,null,7,4]</p>
<img alt="" src="https://assets.leetcode.com/uploads/2018/12/14/binarytree.png" style="width: 200px; height: 190px;"/>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> root = [3,5,1,6,2,0,8,null,null,7,4], p = 5, q = 1
<strong>Output:</strong> 3
<strong>Explanation: </strong>The LCA of nodes <code>5</code> and <code>1</code> is <code>3.</code>
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> root = [3,5,1,6,2,0,8,null,null,7,4], p = 5, q = 4
<strong>Output:</strong> 5
<strong>Explanation: </strong>The LCA of nodes <code>5</code> and <code>4</code> is <code>5</code>, since a node can be a descendant of itself according to the LCA definition.
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ul>
<li>All of the nodes' values will be unique.</li>
<li>p and q are different and both values will exist in the binary tree.</li>
</ul>
</div></div>

### Solution
