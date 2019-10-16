---
layout: post
title: 295. Find Median from Data Stream
category: [Leetcode]
description: 
keywords: ['Heap', 'Design', 'Leetcode', 'Hard']
---
### [295. Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream)

#### Tags: 'Heap', 'Design'

<div class="content__u3I1 question-content__JfgR"><div><p>Median is the middle value in an ordered integer list. If the size of the list is even, there is no middle value. So the median is the mean of the two middle value.</p>
For example,

<p><code>[2,3,4]</code>, the median is <code>3</code></p>
<p><code>[2,3]</code>, the median is <code>(2 + 3) / 2 = 2.5</code></p>
<p>Design a data structure that supports the following two operations:</p>
<ul>
<li>void addNum(int num) - Add a integer number from the data stream to the data structure.</li>
<li>double findMedian() - Return the median of all elements so far.</li>
</ul>
<p> </p>
<p><strong>Example:</strong></p>
<pre>addNum(1)
addNum(2)
findMedian() -&gt; 1.5
addNum(3) 
findMedian() -&gt; 2
</pre>
<p> </p>
<p><strong>Follow up:</strong></p>
<ol>
<li>If all integer numbers from the stream are between 0 and 100, how would you optimize it?</li>
<li>If 99% of all integer numbers from the stream are between 0 and 100, how would you optimize it?</li>
</ol>
</div></div>

### Solution
