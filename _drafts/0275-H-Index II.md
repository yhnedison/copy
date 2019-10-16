---
layout: post
title: 275. H-Index II
category: [Leetcode]
description: 
keywords: ['Binary Search', 'Leetcode', 'Medium']
---
### [275. H-Index II](https://leetcode.com/problems/h-index-ii)

#### Tags: 'Binary Search'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array of citations <strong>sorted in ascending order </strong>(each citation is a non-negative integer) of a researcher, write a function to compute the researcher's h-index.</p>
<p>According to the <a href="https://en.wikipedia.org/wiki/H-index" target="_blank">definition of h-index on Wikipedia</a>: "A scientist has index <i>h</i> if <i>h</i> of his/her <i>N</i> papers have <b>at least</b> <i>h</i> citations each, and the other <i>N − h</i> papers have <b>no more than</b> <i>h </i>citations each."</p>
<p><b>Example:</b></p>
<pre><b>Input:</b> <code>citations = [0,1,3,5,6]</code>
<b>Output:</b> 3 
<strong>Explanation: </strong><code>[0,1,3,5,6] </code>means the researcher has <code>5</code> papers in total and each of them had 
             received 0<code>, 1, 3, 5, 6</code> citations respectively. 
             Since the researcher has <code>3</code> papers with <b>at least</b> <code>3</code> citations each and the remaining 
             two with <b>no more than</b> <code>3</code> citations each, her h-index is <code>3</code>.</pre>
<p><strong>Note:</strong></p>
<p>If there are several possible values for <em>h</em>, the maximum one is taken as the h-index.</p>
<p><strong>Follow up:</strong></p>
<ul>
<li>This is a follow up problem to <a href="/problems/h-index/description/">H-Index</a>, where <code>citations</code> is now guaranteed to be sorted in ascending order.</li>
<li>Could you solve it in logarithmic time complexity?</li>
</ul>
</div></div>

### Solution
