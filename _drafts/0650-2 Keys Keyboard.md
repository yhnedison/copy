---
layout: post
title: 650. 2 Keys Keyboard
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Leetcode', 'Medium']
---
### [650. 2 Keys Keyboard](https://leetcode.com/problems/2-keys-keyboard)

#### Tags: 'Dynamic Programming'

<div class="content__u3I1 question-content__JfgR"><div><p>Initially on a notepad only one character 'A' is present. You can perform two operations on this notepad for each step:</p>
<ol>
<li><code>Copy All</code>: You can copy all the characters present on the notepad (partial copy is not allowed).</li>
<li><code>Paste</code>: You can paste the characters which are copied <b>last time</b>.</li>
</ol>
<p> </p>
<p>Given a number <code>n</code>. You have to get <b>exactly</b> <code>n</code> 'A' on the notepad by performing the minimum number of steps permitted. Output the minimum number of steps to get <code>n</code> 'A'.</p>
<p><b>Example 1:</b></p>
<pre><b>Input:</b> 3
<b>Output:</b> 3
<b>Explanation:</b>
Intitally, we have one character 'A'.
In step 1, we use <b>Copy All</b> operation.
In step 2, we use <b>Paste</b> operation to get 'AA'.
In step 3, we use <b>Paste</b> operation to get 'AAA'.
</pre>
<p> </p>
<p><b>Note:</b></p>
<ol>
<li>The <code>n</code> will be in the range [1, 1000].</li>
</ol>
<p> </p>
</div></div>

### Solution
