---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Stack', 'Leetcode', 'Medium']
---
### [1003. Check If Word Is Valid After Substitutions](https://leetcode.com/problems/check-if-word-is-valid-after-substitutions)

#### Tags: 'String', 'Stack'

<div class="content__u3I1 question-content__JfgR"><div><p>We are given that the string <code>"abc"</code> is valid.</p>
<p>From any valid string <code>V</code>, we may split <code>V</code> into two pieces <code>X</code> and <code>Y</code> such that <code>X + Y</code> (<code>X</code> concatenated with <code>Y</code>) is equal to <code>V</code>.  (<code>X</code> or <code>Y</code> may be empty.)  Then, <code>X + "abc" + Y</code> is also valid.</p>
<p>If for example <code>S = "abc"</code>, then examples of valid strings are: <code>"abc", "aabcbc", "abcabc", "abcabcababcc"</code>.  Examples of <strong>invalid</strong> strings are: <code>"abccba"</code>, <code>"ab"</code>, <code>"cababc"</code>, <code>"bac"</code>.</p>
<p>Return <code>true</code> if and only if the given string <code>S</code> is valid.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">"aabcbc"</span>
<strong>Output: </strong><span id="example-output-1">true</span>
<strong>Explanation: </strong>
We start with the valid string "abc".
Then we can insert another "abc" between "a" and "bc", resulting in "a" + "abc" + "bc" which is "aabcbc".
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span id="example-input-2-1">"abcabcababcc"</span>
<strong>Output: </strong><span id="example-output-2">true</span>
<strong>Explanation: </strong>
"abcabcabc" is valid after consecutive insertings of "abc".
Then we can insert "abc" before the last letter, resulting in "abcabcab" + "abc" + "c" which is "abcabcababcc".
</pre>
<div>
<p><strong>Example 3:</strong></p>
<pre><strong>Input: </strong><span id="example-input-3-1">"abccba"</span>
<strong>Output: </strong><span id="example-output-3">false</span>
</pre>
<div>
<p><strong>Example 4:</strong></p>
<pre><strong>Input: </strong><span id="example-input-4-1">"cababc"</span>
<strong>Output: </strong><span id="example-output-4">false</span></pre>
<p> </p>
</div>
</div>
</div>
<p><strong>Note:</strong></p>
<ol>
<li><code>1 &lt;= S.length &lt;= 20000</code></li>
<li><code>S[i]</code> is <code>'a'</code>, <code>'b'</code>, or <code>'c'</code></li>
</ol>
<div>
<div>
<div>
<div> </div>
</div>
</div>
</div></div></div>

### Solution
