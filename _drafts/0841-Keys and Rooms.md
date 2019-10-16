---
layout: post
title: 841. Keys and Rooms
category: [Leetcode]
description: 
keywords: ['Depth-first Search', 'Graph', 'Leetcode', 'Medium']
---
### [841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms)

#### Tags: 'Depth-first Search', 'Graph'

<div class="content__u3I1 question-content__JfgR"><div><p>There are <code>N</code> rooms and you start in room <code>0</code>.  Each room has a distinct number in <code>0, 1, 2, ..., N-1</code>, and each room may have some keys to access the next room. </p>
<p>Formally, each room <code>i</code> has a list of keys <code>rooms[i]</code>, and each key <code>rooms[i][j]</code> is an integer in <code>[0, 1, ..., N-1]</code> where <code>N = rooms.length</code>.  A key <code>rooms[i][j] = v</code> opens the room with number <code>v</code>.</p>
<p>Initially, all the rooms start locked (except for room <code>0</code>). </p>
<p>You can walk back and forth between rooms freely.</p>
<p>Return <code>true</code> if and only if you can enter every room.</p>
<ol>
</ol>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>[[1],[2],[3],[]]
<strong>Output: </strong>true
<strong>Explanation:  </strong>
We start in room 0, and pick up key 1.
We then go to room 1, and pick up key 2.
We then go to room 2, and pick up key 3.
We then go to room 3.  Since we were able to go to every room, we return true.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>[[1,3],[3,0,1],[2],[0]]
<strong>Output: </strong>false
<strong>Explanation: </strong>We can't enter the room with number 2.
</pre>
<p><b>Note:</b></p>
<ol>
<li><code>1 &lt;= rooms.length &lt;= 1000</code></li>
<li><code>0 &lt;= rooms[i].length &lt;= 1000</code></li>
<li>The number of keys in all rooms combined is at most <code>3000</code>.</li>
</ol>
</div></div>

### Solution
