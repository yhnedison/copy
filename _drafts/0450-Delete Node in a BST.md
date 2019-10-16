---
layout: post
title: 450. Delete Node in a BST
category: [Leetcode]
description: 
keywords: ['Tree', 'Leetcode', 'Medium']
---
### [450. Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst)

#### Tags: 'Tree'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a root node reference of a BST and a key, delete the node with the given key in the BST. Return the root node reference (possibly updated) of the BST.</p>
<p>Basically, the deletion can be divided into two stages:
</p><ol>
<li>Search for a node to remove.</li>
<li>If the node is found, delete the node.</li>
</ol>
<p></p>
<p><b>Note:</b> Time complexity should be O(height of tree).</p>
<p><b>Example:</b>
</p><pre>root = [5,3,6,2,4,null,7]
key = 3

    5
   / \
  3   6
 / \   \
2   4   7

Given key to delete is 3. So we find the node with value 3 and delete it.

One valid answer is [5,4,6,2,null,null,7], shown in the following BST.

    5
   / \
  4   6
 /     \
2       7

Another valid answer is [5,2,6,null,4,null,7].

    5
   / \
  2   6
   \   \
    4   7
</pre>
<p></p></div></div>

### Solution
