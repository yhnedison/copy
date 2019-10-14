---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Leetcode', 'Hard']
---
### [68. Text Justification](https://leetcode.com/problems/text-justification)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>Given an array of words and a width <em>maxWidth</em>, format the text such that each line has exactly <em>maxWidth</em> characters and is fully (left and right) justified.</p>
<p>You should pack your words in a greedy approach; that is, pack as many words as you can in each line. Pad extra spaces <code>' '</code> when necessary so that each line has exactly <em>maxWidth</em> characters.</p>
<p>Extra spaces between words should be distributed as evenly as possible. If the number of spaces on a line do not divide evenly between words, the empty slots on the left will be assigned more spaces than the slots on the right.</p>
<p>For the last line of text, it should be left justified and no <strong>extra</strong> space is inserted between words.</p>
<p><strong>Note:</strong></p>
<ul>
<li>A word is defined as a character sequence consisting of non-space characters only.</li>
<li>Each word's length is guaranteed to be greater than 0 and not exceed <em>maxWidth</em>.</li>
<li>The input array <code>words</code> contains at least one word.</li>
</ul>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong>
words = ["This", "is", "an", "example", "of", "text", "justification."]
maxWidth = 16
<strong>Output:</strong>
[
   "This    is    an",
   "example  of text",
   "justification.  "
]
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong>
words = ["What","must","be","acknowledgment","shall","be"]
maxWidth = 16
<strong>Output:</strong>
[
  "What   must   be",
  "acknowledgment  ",
  "shall be        "
]
<strong>Explanation:</strong> Note that the last line is "shall be    " instead of "shall     be",
             because the last line must be left-justified instead of fully-justified.
             Note that the second line is also left-justified becase it contains only one word.
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong>
words = ["Science","is","what","we","understand","well","enough","to","explain",
         "to","a","computer.","Art","is","everything","else","we","do"]
maxWidth = 20
<strong>Output:</strong>
[
  "Science  is  what we",
  "understand      well",
  "enough to explain to",
  "a  computer.  Art is",
  "everything  else  we",
  "do                  "
]
</pre>
</div></div>

### Solution
