---
layout: post
title: 1041. Robot Bounded In Circle
category: [Leetcode]
description: 
keywords: ['Math', 'Leetcode', 'Medium']
---
### [1041. Robot Bounded In Circle](https://leetcode.com/problems/robot-bounded-in-circle)

#### Tags: 'Math'

<div class="content__u3I1 question-content__JfgR"><div><p>On an infinite plane, a robot initially stands at <code>(0, 0)</code> and faces north.  The robot can receive one of three instructions:</p>
<ul>
<li><code>"G"</code>: go straight 1 unit;</li>
<li><code>"L"</code>: turn 90 degrees to the left;</li>
<li><code>"R"</code>: turn 90 degress to the right.</li>
</ul>
<p>The robot performs the <code>instructions</code> given in order, and repeats them forever.</p>
<p>Return <code>true</code> if and only if there exists a circle in the plane such that the robot never leaves the circle.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>"GGLLGG"
<strong>Output: </strong>true
<strong>Explanation: </strong>
The robot moves from (0,0) to (0,2), turns 180 degrees, and then returns to (0,0).
When repeating these instructions, the robot remains in the circle of radius 2 centered at the origin.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>"GG"
<strong>Output: </strong>false
<strong>Explanation: </strong>
The robot moves north indefinitely.
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong>"GL"
<strong>Output: </strong>true
<strong>Explanation: </strong>
The robot moves from (0, 0) -&gt; (0, 1) -&gt; (-1, 1) -&gt; (-1, 0) -&gt; (0, 0) -&gt; ...
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= instructions.length &lt;= 100</code></li>
<li><code>instructions[i]</code> is in <code>{'G', 'L', 'R'}</code></li>
</ol>
</div></div>

### Solution
