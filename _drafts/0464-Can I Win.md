---
layout: post
title: 464. Can I Win
category: [Leetcode]
description: 
keywords: ['Dynamic Programming', 'Minimax', 'Leetcode', 'Medium']
---
### [464. Can I Win](https://leetcode.com/problems/can-i-win)

#### Tags: 'Dynamic Programming', 'Minimax'

<div class="content__u3I1 question-content__JfgR"><div><p>In the "100 game," two players take turns adding, to a running total, any integer from 1..10. The player who first causes the running total to reach or exceed 100 wins. </p>
<p>What if we change the game so that players cannot re-use integers? </p>
<p>For example, two players might take turns drawing from a common pool of numbers of 1..15 without replacement until they reach a total &gt;= 100.</p>
<p>Given an integer <code>maxChoosableInteger</code> and another integer <code>desiredTotal</code>, determine if the first player to move can force a win, assuming both players play optimally. </p>
<p>You can always assume that <code>maxChoosableInteger</code> will not be larger than 20 and <code>desiredTotal</code> will not be larger than 300.
</p>
<p><b>Example</b>
</p><pre><b>Input:</b>
maxChoosableInteger = 10
desiredTotal = 11

<b>Output:</b>
false

<b>Explanation:</b>
No matter which integer the first player choose, the first player will lose.
The first player can choose an integer from 1 up to 10.
If the first player choose 1, the second player can only choose integers from 2 up to 10.
The second player will win by choosing 10 and get a total = 11, which is &gt;= desiredTotal.
Same with other integers chosen by the first player, the second player will always win.
</pre>
<p></p></div></div>

### Solution
