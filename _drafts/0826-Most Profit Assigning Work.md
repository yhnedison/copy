---
layout: post
title: 826. Most Profit Assigning Work
category: [Leetcode]
description: 
keywords: ['Two Pointers', 'Leetcode', 'Medium']
---
### [826. Most Profit Assigning Work](https://leetcode.com/problems/most-profit-assigning-work)

#### Tags: 'Two Pointers'

<div class="content__u3I1 question-content__JfgR"><div><p>We have jobs: <code>difficulty[i]</code> is the difficulty of the <code>i</code>th job, and <code>profit[i]</code> is the profit of the <code>i</code>th job. </p>
<p>Now we have some workers. <code>worker[i]</code> is the ability of the <code>i</code>th worker, which means that this worker can only complete a job with difficulty at most <code>worker[i]</code>. </p>
<p>Every worker can be assigned at most one job, but one job can be completed multiple times.</p>
<p>For example, if 3 people attempt the same job that pays $1, then the total profit will be $3.  If a worker cannot complete any job, his profit is $0.</p>
<p>What is the most profit we can make?</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>difficulty = [2,4,6,8,10], profit = [10,20,30,40,50], worker = [4,5,6,7]
<strong>Output: </strong>100 
<strong>Explanation: W</strong>orkers are assigned jobs of difficulty [4,4,6,6] and they get profit of [20,20,30,30] seperately.</pre>
<p><strong>Notes:</strong></p>
<ul>
<li><code>1 &lt;= difficulty.length = profit.length &lt;= 10000</code></li>
<li><code>1 &lt;= worker.length &lt;= 10000</code></li>
<li><code>difficulty[i], profit[i], worker[i]</code>  are in range <code>[1, 10^5]</code></li>
</ul>
</div></div>

### Solution
