---
layout: post
category: Leetcode
description: 
keywords: ['Tree', 'Depth-first Search', 'Leetcode', 'Medium']
---
### [337. House Robber III](https://leetcode.com/problems/house-robber-iii)

#### Tags: 'Tree', 'Depth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>The thief has found himself a new place for his thievery again. There is only one entrance to this area, called the "root." Besides the root, each house has one and only one parent house. After a tour, the smart thief realized that "all houses in this place forms a binary tree". It will automatically contact the police if two directly-linked houses were broken into on the same night.</p>
<p>Determine the maximum amount of money the thief can rob tonight without alerting the police.</p>
<p><b>Example 1:</b></p>
<pre><strong>Input: </strong>[3,2,3,null,3,null,1]

     <font color="red">3</font>
    / \
   2   3
    \   \ 
     <font color="red">3   1
</font>
<strong>Output:</strong> 7 
<strong>Explanation:</strong> Maximum amount of money the thief can rob = <font color="red" style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'>3</font><span style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'> + </span><font color="red" style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'>3</font><span style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'> + </span><font color="red" style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'>1</font><span style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'> = </span><b style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'>7</b><span style='font-family: sans-serif, Arial, Verdana, "Trebuchet MS";'>.</span></pre>
<p><b>Example 2:</b></p>
<pre><strong>Input: </strong>[3,4,5,1,3,null,1]

     3
    / \
   <font color="red">4</font>   <font color="red">5</font>
  / \   \ 
 1   3   1

<strong>Output:</strong> 9
<strong>Explanation:</strong> Maximum amount of money the thief can rob = <font color="red">4</font> + <font color="red">5</font> = <b>9</b>.
</pre></div></div>

### Solution
