# Find Center of Star Graph

LeetCode Q # 1791.

There is an undirected star graph consisting of n nodes labeled from 1 to n. A star graph is a graph where there is one center node and exactly n - 1 edges that connect the center node with every other node.

You are given a 2D integer array edges where each edges[i] = [ui, vi] indicates that there is an edge between the nodes ui and vi. Return the center of the given star graph.

Example 1:

<div align = "center">

  ![image](https://github.com/xo-azeem/Find-Center-of-Star-Graph-LeetCode/assets/171427226/0fa75dec-3657-402c-b2f3-cf5ba0b314b1)

</div>

> Input: edges = [[1,2],[2,3],[4,2]]</br>
> Output: 2</br>
> Explanation: As shown in the figure above, node 2 is connected to every other node, so 2 is the center.

Example 2:

> Input: edges = [[1,2],[5,1],[1,3],[1,4]]</br>
> Output: 1

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Find-Center-of-Star-Graph-LeetCode/assets/171427226/515ed1d7-9d97-4430-945b-27bbab404a82)

  Time complexity: O(1).</br>Space complexity: O(1).
</div>
