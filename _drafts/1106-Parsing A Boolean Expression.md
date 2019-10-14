---
layout: post
category: Leetcode
description: 
keywords: ['String', 'Leetcode', 'Hard']
---
### [1106. Parsing A Boolean Expression](https://leetcode.com/problems/parsing-a-boolean-expression)

#### Tags: 'String'

<div class="content__u3I1 question-content__JfgR"><div><p>Return the result of evaluating a given boolean <code>expression</code>, represented as a string.</p>
<p>An expression can either be:</p>
<ul>
<li><code>"t"</code>, evaluating to <code>True</code>;</li>
<li><code>"f"</code>, evaluating to <code>False</code>;</li>
<li><code>"!(expr)"</code>, evaluating to the logical NOT of the inner expression <code>expr</code>;</li>
<li><code>"&amp;(expr1,expr2,...)"</code>, evaluating to the logical AND of 2 or more inner expressions <code>expr1, expr2, ...</code>;</li>
<li><code>"|(expr1,expr2,...)"</code>, evaluating to the logical OR of 2 or more inner expressions <code>expr1, expr2, ...</code></li>
</ul>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> expression = "!(f)"
<strong>Output:</strong> true
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> expression = "|(f,t)"
<strong>Output:</strong> true
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> expression = "&amp;(t,f)"
<strong>Output:</strong> false
</pre>
<p><strong>Example 4:</strong></p>
<pre><strong>Input:</strong> expression = "|(&amp;(t,f,t),!(t))"
<strong>Output:</strong> false
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= expression.length &lt;= 20000</code></li>
<li><code>expression[i]</code> consists of characters in <code>{'(', ')', '&amp;', '|', '!', 't', 'f', ','}</code>.</li>
<li><code>expression</code> is a valid expression representing a boolean, as given in the description.</li>
</ul>
</div></div>

### Solution
