---
layout: post
category: Leetcode
description: 
keywords: ['Breadth-first Search', 'Leetcode', 'Medium']
---
### [127. Word Ladder](https://leetcode.com/problems/word-ladder)

#### Tags: 'Breadth-first Search'

<div class="content__u3I1 question-content__JfgR"><div><p>Given two words (<em>beginWord</em> and <em>endWord</em>), and a dictionary's word list, find the length of shortest transformation sequence from <em>beginWord</em> to <em>endWord</em>, such that:</p>
<ol>
<li>Only one letter can be changed at a time.</li>
<li>Each transformed word must exist in the word list. Note that <em>beginWord</em> is <em>not</em> a transformed word.</li>
</ol>
<p><strong>Note:</strong></p>
<ul>
<li>Return 0 if there is no such transformation sequence.</li>
<li>All words have the same length.</li>
<li>All words contain only lowercase alphabetic characters.</li>
<li>You may assume no duplicates in the word list.</li>
<li>You may assume <em>beginWord</em> and <em>endWord</em> are non-empty and are not the same.</li>
</ul>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong>
beginWord = "hit",
endWord = "cog",
wordList = ["hot","dot","dog","lot","log","cog"]

<strong>Output: </strong>5

<strong>Explanation:</strong> As one shortest transformation is "hit" -&gt; "hot" -&gt; "dot" -&gt; "dog" -&gt; "cog",
return its length 5.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong>
beginWord = "hit"
endWord = "cog"
wordList = ["hot","dot","dog","lot","log"]

<strong>Output:</strong> 0

<strong>Explanation:</strong> The endWord "cog" is not in wordList, therefore no possible<strong> </strong>transformation.
</pre>
<ul>
</ul>
</div></div>

### Solution
