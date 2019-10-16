---
layout: post
title: 838. Push Dominoes
category: [Leetcode]
description: 
keywords: ['Two Pointers', 'Dynamic Programming', 'Leetcode', 'Medium']
---
### [838. Push Dominoes](https://leetcode.com/problems/push-dominoes)

#### Tags: 'Two Pointers', 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>There are<font face="monospace"> <code>N</code></font> dominoes in a line, and we place each domino vertically upright.</p>
<p>In the beginning, we simultaneously push some of the dominoes either to the left or to the right.</p>
<p><img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/05/18/domino.png" style="height: 160px;"/></p>
<p>After each second, each domino that is falling to the left pushes the adjacent domino on the left.</p>
<p>Similarly, the dominoes falling to the right push their adjacent dominoes standing on the right.</p>
<p>When a vertical domino has dominoes falling on it from both sides, it stays still due to the balance of the forces.</p>
<p>For the purposes of this question, we will consider that a falling domino expends no additional force to a falling or already fallen domino.</p>
<p>Given a string "S" representing the initial state. <code>S[i] = 'L'</code>, if the i-th domino has been pushed to the left; <code>S[i] = 'R'</code>, if the i-th domino has been pushed to the right; <code>S[i] = '.'</code>, if the <code>i</code>-th domino has not been pushed.</p>
<p>Return a string representing the final state. </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>".L.R...LR..L.."
<strong>Output: </strong>"LL.RR.LLRRLL.."
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>"RR.L"
<strong>Output: </strong>"RR.L"
<strong>Explanation: </strong>The first domino expends no additional force on the second domino.
</pre>
<p><strong>Note:</strong></p>
<ol>
<li><code>0 &lt;= N &lt;= 10^5</code></li>
<li>String <code>dominoes</code> contains only <code>'L</code>', <code>'R'</code> and <code>'.'</code></li>
</ol>
</div></div>

### Solution
