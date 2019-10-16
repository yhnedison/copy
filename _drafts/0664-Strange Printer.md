---
layout: post
title: 664. Strange Printer
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Depth-first Search', 'Leetcode', 'Hard']
---
### [664. Strange Printer](https://leetcode.com/problems/strange-printer)

#### Tags: 'Dynamic Programming', 'Depth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>
There is a strange printer with the following two special requirements:

</p><ol>
<li>The printer can only print a sequence of the same character each time.</li>
<li>At each turn, the printer can print new characters starting from and ending at any places, and will cover the original existing characters.</li>
</ol>
<p></p>
<p>
Given a string consists of lower English letters only, your job is to count the minimum number of turns the printer needed in order to print it.
</p>
<p><b>Example 1:</b><br/>
</p><pre><b>Input:</b> "aaabbb"
<b>Output:</b> 2
<b>Explanation:</b> Print "aaa" first and then print "bbb".
</pre>
<p></p>
<p><b>Example 2:</b><br/>
</p><pre><b>Input:</b> "aba"
<b>Output:</b> 2
<b>Explanation:</b> Print "aaa" first and then print "b" from the second place of the string, which will cover the existing character 'a'.
</pre>
<p></p>
<p><b>Hint</b>: Length of the given string will not exceed 100.</p></div></div>

### Solution
