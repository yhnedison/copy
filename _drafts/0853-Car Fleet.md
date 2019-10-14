---
layout: post
category: Leetcode
description: 
keywords: ['Sort', 'Leetcode', 'Medium']
---
### [853. Car Fleet](https://leetcode.com/problems/car-fleet)

#### Tags: 'Sort'

<div class="content__u3I1 question-content__JfgR"><div><p><code>N</code> cars are going to the same destination along a one lane road.  The destination is <code>target</code> miles away.</p>
<p>Each car <code>i</code> has a constant speed <code>speed[i]</code> (in miles per hour), and initial position <code>position[i]</code> miles towards the target along the road.</p>
<p>A car can never pass another car ahead of it, but it can catch up to it, and drive bumper to bumper at the same speed.</p>
<p>The distance between these two cars is ignored - they are assumed to have the same position.</p>
<p>A <em>car fleet</em> is some non-empty set of cars driving at the same position and same speed.  Note that a single car is also a car fleet.</p>
<p>If a car catches up to a car fleet right at the destination point, it will still be considered as one car fleet.</p>
<p><br/>
How many car fleets will arrive at the destination?</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>target = <span id="example-input-1-1">12</span>, position = <span id="example-input-1-2">[10,8,0,5,3]</span>, speed = <span id="example-input-1-3">[2,4,1,1,3]</span>
<strong>Output: </strong><span id="example-output-1">3</span>
<strong>Explanation</strong>:
The cars starting at 10 and 8 become a fleet, meeting each other at 12.
The car starting at 0 doesn't catch up to any other car, so it is a fleet by itself.
The cars starting at 5 and 3 become a fleet, meeting each other at 6.
Note that no other cars meet these fleets before the destination, so the answer is 3.
</pre>
<p><br/>
<strong>Note:</strong></p>
<ol>
<li><code>0 &lt;= N &lt;= 10 ^ 4</code></li>
<li><code>0 &lt; target &lt;= 10 ^ 6</code></li>
<li><code>0 &lt; speed[i] &lt;= 10 ^ 6</code></li>
<li><code>0 &lt;= position[i] &lt; target</code></li>
<li>All initial positions are different.</li>
</ol></div></div>

### Solution
