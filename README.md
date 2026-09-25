# jump_Game
**Problem

Given an array nums, each element represents the maximum number of steps you can jump from that position.

We need to check whether we can reach the last index.

**Example**
Input: nums = [2,3,1,1,4]
Output: true

We can reach the last index.

**Approach

I used a Greedy Approach.

maxR stores the farthest index we can reach.
For every index, we check whether that index is reachable.
If i > maxR, we cannot reach that position, so return false.
Otherwise, update maxR with the farthest position we can reach.
