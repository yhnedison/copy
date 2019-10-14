---
layout: post
category: Leetcode
description: 
keywords: ['Stack', 'Leetcode', 'Medium']
---
### [880. Decoded String at Index](https://leetcode.com/problems/decoded-string-at-index)

#### Tags: 'Stack'

<div class="content__u3I1 question-content__JfgR"><div><p>An encoded string <code>S</code> is given.  To find and write the <em>decoded</em> string to a tape, the encoded string is read <strong>one character at a time</strong> and the following steps are taken:</p>
<ul>
<li>If the character read is a letter, that letter is written onto the tape.</li>
<li>If the character read is a digit (say <code>d</code>), the entire current tape is repeatedly written <code>d-1</code> more times in total.</li>
</ul>
<p>Now for some encoded string <code>S</code>, and an index <code>K</code>, find and return the <code>K</code>-th letter (1 indexed) in the decoded string.</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong>S = <span id="example-input-1-1">"leet2code3"</span>, K = <span id="example-input-1-2">10</span>
<strong>Output: </strong><span id="example-output-1">"o"</span>
<strong>Explanation: </strong>
The decoded string is "leetleetcodeleetleetcodeleetleetcode".
The 10th letter in the string is "o".
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong>S = <span id="example-input-2-1">"ha22"</span>, K = <span id="example-input-2-2">5</span>
<strong>Output: </strong><span id="example-output-2">"h"</span>
<strong>Explanation: </strong>
The decoded string is "hahahaha".  The 5th letter is "h".
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong>S = <span id="example-input-3-1">"a2345678999999999999999"</span>, K = <span id="example-input-3-2">1</span>
<strong>Output: </strong><span id="example-output-3">"a"</span>
<strong>Explanation: </strong>
The decoded string is "a" repeated 8301530446056247680 times.  The 1st letter is "a".
</pre>
<p> </p>
<p><strong>Note:</strong></p>
<ol>
<li><code>2 &lt;= S.length &lt;= 100</code></li>
<li><code>S</code> will only contain lowercase letters and digits <code>2</code> through <code>9</code>.</li>
<li><code>S</code> starts with a letter.</li>
<li><code>1 &lt;= K &lt;= 10^9</code></li>
<li>The decoded string is guaranteed to have less than <code>2^63</code> letters.</li>
</ol>
</div>
</div>
</div>
</div></div>

### Solution
