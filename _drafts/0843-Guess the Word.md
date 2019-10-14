---
layout: post
category: Leetcode
description: 
keywords: ['Minimax', 'Leetcode', 'Hard']
---
### [843. Guess the Word](https://leetcode.com/problems/guess-the-word)

#### Tags: 'Minimax'

<div class="content__u3I1 question-content__JfgR"><div><p>This problem is an <strong><em>interactive problem</em></strong> new to the LeetCode platform.</p>
<p>We are given a word list of unique words, each word is 6 letters long, and one word in this list is chosen as <strong>secret</strong>.</p>
<p>You may call <code>master.guess(word)</code> to guess a word.  The guessed word should have type <code>string</code> and must be from the original list with 6 lowercase letters.</p>
<p>This function returns an <code>integer</code> type, representing the number of exact matches (value and position) of your guess to the <strong>secret word</strong>.  Also, if your guess is not in the given wordlist, it will return <code>-1</code> instead.</p>
<p>For each test case, you have 10 guesses to guess the word. At the end of any number of calls, if you have made 10 or less calls to <code>master.guess</code> and at least one of these guesses was the <strong>secret</strong>, you pass the testcase.</p>
<p>Besides the example test case below, there will be 5 additional test cases, each with 100 words in the word list.  The letters of each word in those testcases were chosen independently at random from <code>'a'</code> to <code>'z'</code>, such that every word in the given word lists is unique.</p>
<pre><strong>Example 1:</strong>
<strong>Input:</strong> secret = "acckzz", wordlist = ["acckzz","ccbazz","eiowzz","abcczz"]

<strong>Explanation:</strong>

<code>master.guess("aaaaaa")</code> returns -1, because <code>"aaaaaa"</code> is not in wordlist.
<code>master.guess("acckzz") </code>returns 6, because <code>"acckzz"</code> is secret and has all 6 matches.
<code>master.guess("ccbazz")</code> returns 3, because<code> "ccbazz"</code> has 3 matches.
<code>master.guess("eiowzz")</code> returns 2, because <code>"eiowzz"</code> has 2 matches.
<code>master.guess("abcczz")</code> returns 4, because <code>"abcczz"</code> has 4 matches.

We made 5 calls to master.guess and one of them was the secret, so we pass the test case.
</pre>
<p><strong>Note:</strong>  Any solutions that attempt to circumvent the judge will result in disqualification.</p>
</div></div>

### Solution
