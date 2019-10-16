---
layout: post
title: 920. Number of Music Playlists
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Hard']
---
### [920. Number of Music Playlists](https://leetcode.com/problems/number-of-music-playlists)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>Your music player contains <code>N</code> different songs and she wants to listen to <code>L</code><strong> </strong>(not necessarily different) songs during your trip.  You create a playlist so that:</p>
<ul>
<li>Every song is played at least once</li>
<li>A song can only be played again only if <code>K</code> other songs have been played</li>
</ul>
<p>Return the number of possible playlists.  <strong>As the answer can be very large, return it modulo <code>10^9 + 7</code></strong>.</p>
<p> </p>
<div>
<div>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>N = <span id="example-input-1-1">3</span>, L = <span id="example-input-1-2">3</span>, K = <span id="example-input-1-3">1</span>
<strong>Output: </strong><span id="example-output-1">6
<strong>Explanation</strong>: </span><span>There are 6 possible playlists. [1, 2, 3], [1, 3, 2], [2, 1, 3], [2, 3, 1], [3, 1, 2], [3, 2, 1].</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>N = <span id="example-input-2-1">2</span>, L = <span id="example-input-2-2">3</span>, K = <span id="example-input-2-3">0</span>
<strong>Output: </strong><span id="example-output-2">6
</span><span id="example-output-1"><strong>Explanation</strong>: </span><span>There are 6 possible playlists. [1, 1, 2], [1, 2, 1], [2, 1, 1], [2, 2, 1], [2, 1, 2], [1, 2, 2]</span>
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong>N = <span id="example-input-3-1">2</span>, L = <span id="example-input-3-2">3</span>, K = <span id="example-input-3-3">1</span>
<strong>Output: </strong><span id="example-output-3">2
<strong>Explanation</strong>: </span><span>There are 2 possible playlists. [1, 2, 1], [2, 1, 2]</span>
</pre>
</div>
</div>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>0 &lt;= K &lt; N &lt;= L &lt;= 100</code></li>
</ol>
</div>
</div>
</div></div></div>

### Solution
