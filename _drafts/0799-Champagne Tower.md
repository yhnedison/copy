---
layout: post
title: 799. Champagne Tower
category: [Leetcode]
description: 
keywords: ['Leetcode', 'Medium']
---
### [799. Champagne Tower](https://leetcode.com/problems/champagne-tower)

#### Tags: 

<div class="content__u3I1 question-content__JfgR"><div><p>We stack glasses in a pyramid, where the first row has 1 glass, the second row has 2 glasses, and so on until the 100th row.  Each glass holds one cup (250ml) of champagne.</p>
<p>Then, some champagne is poured in the first glass at the top.  When the top most glass is full, any excess liquid poured will fall equally to the glass immediately to the left and right of it.  When those glasses become full, any excess champagne will fall equally to the left and right of those glasses, and so on.  (A glass at the bottom row has it's excess champagne fall on the floor.)</p>
<p>For example, after one cup of champagne is poured, the top most glass is full.  After two cups of champagne are poured, the two glasses on the second row are half full.  After three cups of champagne are poured, those two cups become full - there are 3 full glasses total now.  After four cups of champagne are poured, the third row has the middle glass half full, and the two outside glasses are a quarter full, as pictured below.</p>
<p><img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/03/09/tower.png" style="height:200px; width:290px"/></p>
<p>Now after pouring some non-negative integer cups of champagne, return how full the j-th glass in the i-th row is (both i and j are 0 indexed.)</p>
<p> </p>
<pre><strong>Example 1:</strong>
<strong>Input:</strong> poured = 1, query_glass = 1, query_row = 1
<strong>Output:</strong> 0.0
<strong>Explanation:</strong> We poured 1 cup of champange to the top glass of the tower (which is indexed as (0, 0)). There will be no excess liquid so all the glasses under the top glass will remain empty.

<strong>Example 2:</strong>
<strong>Input:</strong> poured = 2, query_glass = 1, query_row = 1
<strong>Output:</strong> 0.5
<strong>Explanation:</strong> We poured 2 cups of champange to the top glass of the tower (which is indexed as (0, 0)). There is one cup of excess liquid. The glass indexed as (1, 0) and the glass indexed as (1, 1) will share the excess liquid equally, and each will get half cup of champange.
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ul>
<li><code>poured</code> will be in the range of <code>[0, 10 ^ 9]</code>.</li>
<li><code>query_glass</code> and <code>query_row</code> will be in the range of <code>[0, 99]</code>.</li>
</ul>
<p> </p>
</div></div>

### Solution
