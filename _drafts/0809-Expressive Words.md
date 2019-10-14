---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Leetcode', 'Medium']
---
### [809. Expressive Words](https://leetcode.com/problems/expressive-words)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>Sometimes people repeat letters to represent extra feeling, such as "hello" -&gt; "heeellooo", "hi" -&gt; "hiiii".  In these strings like "heeellooo", we have <em>groups</em> of adjacent letters that are all the same:  "h", "eee", "ll", "ooo".</p>
<p>For some given string <code>S</code>, a query word is <em>stretchy</em> if it can be made to be equal to <code>S</code> by any number of applications of the following <em>extension</em> operation: choose a group consisting of characters <code>c</code>, and add some number of characters <code>c</code> to the group so that the size of the group is 3 or more.</p>
<p>For example, starting with "hello", we could do an extension on the group "o" to get "hellooo", but we cannot get "helloo" since the group "oo" has size less than 3.  Also, we could do another extension like "ll" -&gt; "lllll" to get "helllllooo".  If <code>S = "helllllooo"</code>, then the query word "hello" would be stretchy because of these two extension operations: <code>query = "hello" -&gt; "hellooo" -&gt; "helllllooo" = S</code>.</p>
<p>Given a list of query words, return the number of words that are stretchy. </p>
<p> </p>
<pre><strong>Example:</strong>
<strong>Input:</strong> 
S = "heeellooo"
words = ["hello", "hi", "helo"]
<strong>Output:</strong> 1
<strong>Explanation:</strong> 
We can extend "e" and "o" in the word "hello" to get "heeellooo".
We can't extend "helo" to get "heeellooo" because the group "ll" is not size 3 or more.
</pre>
<p> </p>
<p><strong>Notes: </strong></p>
<ul>
<li><code>0 &lt;= len(S) &lt;= 100</code>.</li>
<li><code>0 &lt;= len(words) &lt;= 100</code>.</li>
<li><code>0 &lt;= len(words[i]) &lt;= 100</code>.</li>
<li><code>S</code> and all words in <code>words</code> consist only of lowercase letters</li>
</ul>
<p> </p>
</div></div>

### Solution
