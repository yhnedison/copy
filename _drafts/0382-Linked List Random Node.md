---
layout: post
category: Leetcode
description: 
keywords: ['Reservoir Sampling', 'Leetcode', 'Medium']
---
### [382. Linked List Random Node](https://leetcode.com/problems/linked-list-random-node)

#### Tags: 'Reservoir Sampling'

<div class="content__u3I1 question-content__JfgR"><div><p>Given a singly linked list, return a random node's value from the linked list. Each node must have the <b>same probability</b> of being chosen.</p>
<p><b>Follow up:</b><br/>
What if the linked list is extremely large and its length is unknown to you? Could you solve this efficiently without using extra space?
</p>
<p><b>Example:</b>
</p><pre>// Init a singly linked list [1,2,3].
ListNode head = new ListNode(1);
head.next = new ListNode(2);
head.next.next = new ListNode(3);
Solution solution = new Solution(head);

// getRandom() should return either 1, 2, or 3 randomly. Each element should have equal probability of returning.
solution.getRandom();
</pre>
<p></p></div></div>

### Solution
