---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Leetcode', 'Hard']
---
### [1096. Brace Expansion II](https://leetcode.com/problems/brace-expansion-ii)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>Under a grammar given below, strings can represent a set of lowercase words.  Let's use <code>R(expr)</code> to denote the <strong>set</strong> of words the expression represents.</p>
<p>Grammar can best be understood through simple examples:</p>
<ul>
<li>Single letters represent a singleton set containing that word.
	<ul>
<li><code>R("a") = {"a"}</code></li>
<li><code>R("w") = {"w"}</code></li>
</ul>
</li>
<li>When we take a comma delimited list of 2 or more expressions, we take the union of possibilities.
	<ul>
<li><code>R("{a,b,c}") = {"a","b","c"}</code></li>
<li><code>R("{{a,b},{b,c}}") = {"a","b","c"}</code> (notice the final set only contains each word at most once)</li>
</ul>
</li>
<li>When we concatenate two expressions, we take the set of possible concatenations between two words where the first word comes from the first expression and the second word comes from the second expression.
	<ul>
<li><code>R("{a,b}{c,d}") = {"ac","ad","bc","bd"}</code></li>
<li><code>R("a{b,c}{d,e}f{g,h}") = {"abdfg", "abdfh", "abefg", "abefh", "acdfg", "acdfh", "acefg", "acefh"}</code></li>
</ul>
</li>
</ul>
<p>Formally, the 3 rules for our grammar:</p>
<ul>
<li>For every lowercase letter <code>x</code>, we have <code>R(x) = {x}</code></li>
<li>For expressions <code>e_1, e_2, ... , e_k</code> with <code>k &gt;= 2</code>, we have <code>R({e_1,e_2,...}) = R(e_1) ∪ R(e_2) ∪ ...</code></li>
<li>For expressions <code>e_1</code> and <code>e_2</code>, we have <code>R(e_1 + e_2) = {a + b for (a, b) in R(e_1) × R(e_2)}</code>, where + denotes concatenation, and × denotes the cartesian product.</li>
</ul>
<p>Given an <code>expression</code> representing a set of words under the given grammar, return the sorted list of words that the expression represents.</p>
<p> </p>
<div>
<p><strong>Example 1:</strong></p>
<pre><strong>Input: </strong><span id="example-input-1-1">"{a,b}{c,{d,e}}"</span>
<strong>Output: </strong><span id="example-output-1">["ac","ad","ae","bc","bd","be"]</span>
</pre>
<div>
<p><strong>Example 2:</strong></p>
<pre><strong>Input: </strong><span>"{{a,z},a{b,c},{ab,z}}"</span>
<strong>Output: </strong><span>["a","ab","ac","z"]</span>
<strong>Explanation: </strong>Each distinct word is written only once in the final answer.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ol>
<li><code>1 &lt;= expression.length &lt;= 60</code></li>
<li><code>expression[i]</code> consists of <code>'{'</code>, <code>'}'</code>, <code>','</code>or lowercase English letters.</li>
<li>The given <code>expression</code> represents a set of words based on the grammar given in the description.</li>
</ol>
</div>
</div>
</div></div>

### Solution
