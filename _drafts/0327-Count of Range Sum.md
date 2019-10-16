---
layout: post
title: 327. Count of Range Sum
category: [Leetcode]
description: 
keywords: ['Binary Search', 'Divide and Conquer', 'Sort', 'Binary Indexed Tree', 'Segment Tree', 'Leetcode', 'Hard']
---
### [327. Count of Range Sum](https://leetcode.com/problems/count-of-range-sum)

#### Tags: 'Binary Search', 'Divide and Conquer', 'Sort', 'Binary Indexed Tree', 'Segment Tree'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an integer array <code>nums</code>, return the number of range sums that lie in <code>[lower, upper]</code> inclusive.<br/>
Range sum <code>S(i, j)</code> is defined as the sum of the elements in <code>nums</code> between indices <code>i</code> and <code>j</code> (<code>i</code> ≤ <code>j</code>), inclusive.</p>
<p><b>Note:</b><br/>
A naive algorithm of <i>O</i>(<i>n</i><sup>2</sup>) is trivial. You MUST do better than that.</p>
<p><b>Example:</b></p>
<pre><strong>Input: </strong><i>nums</i> = <code>[-2,5,-1]</code>, <i>lower</i> = <code>-2</code>, <i>upper</i> = <code>2</code>,
<strong>Output: </strong>3 
<strong>Explanation: </strong>The three ranges are : <code>[0,0]</code>, <code>[2,2]</code>, <code>[0,2]</code> and their respective sums are: <code>-2, -1, 2</code>.
</pre></div></div>

### Solution
