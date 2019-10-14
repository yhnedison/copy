---
layout: post
category: Leetcode
description: 
keywords: ['Array', 'Greedy', 'Queue', 'Leetcode', 'Medium']
---
### [621. Task Scheduler](https://leetcode.com/problems/task-scheduler)

#### Tags: 'Array', 'Greedy', 'Queue'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a char array representing tasks CPU need to do. It contains capital letters A to Z where different letters represent different tasks. Tasks could be done without original order. Each task could be done in one interval. For each interval, CPU could finish one task or just be idle.</p>
<p>However, there is a non-negative cooling interval <b>n</b> that means between two <b>same tasks</b>, there must be at least n intervals that CPU are doing different tasks or just be idle.</p>
<p>You need to return the <b>least</b> number of intervals the CPU will take to finish all the given tasks.</p>
<p> </p>
<p><b>Example:</b></p>
<pre><b>Input:</b> tasks = ["A","A","A","B","B","B"], n = 2
<b>Output:</b> 8
<b>Explanation:</b> A -&gt; B -&gt; idle -&gt; A -&gt; B -&gt; idle -&gt; A -&gt; B.
</pre>
<p> </p>
<p><b>Note:</b></p>
<ol>
<li>The number of tasks is in the range [1, 10000].</li>
<li>The integer n is in the range [0, 100].</li>
</ol>
</div></div>

### Solution
