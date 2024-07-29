# my-dsa-coding-concept-collection-1

fill arrays-> 00048_blank

Topics:

1. Sorting-------------------
2. Array
3. Strings
4. Sliding window and two pointer
5. Greedy
6. Heap/Priority Queue
7. Stack and Queue and Dequeue and Monotonic Stack
8. Binary Search-----------------
9. Recursion---------------------------
10. DP                                
11. Graph
12. Binary Tree
13. Binary Search Tree------------------
14. LinkedList
15. Trie
16. Bit Manipulation----------------
17. Math 

Platforms used:
0. https://takeuforward.org
1. leetcode
2. geeksforgeeks
3. udemy pratik narang course
4. neetcode
5. interview bit
6. code forces
7. code 360 naukri coding ninjas
8. spoj
9. codeforces

Priority Queue

min PQ: PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();

max PQ: PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>(Collections.reverseOrder());

Revisit:

Array: 12 : priority queue

TO DO:

https://www.spoj.com/problems/classical/

https://www.spoj.com/problems/classical/sort=0,start=3950

https://www.geeksforgeeks.org/smallest-difference-pair-values-two-unsorted-arrays/

https://www.geeksforgeeks.org/kth-smallest-largest-element-in-unsorted-array/?ref=ml_lbp

https://leetcode.com/problems/course-schedule/description/ cycle in directed graph

https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/

kth permutation sequence

Knapsack Problems 3 types:

1. Greedy - Fractional knapsack - price per unit - https://www.geeksforgeeks.org/problems/knapsack-with-duplicate-items4201/1?utm_source=youtube&utm_medium=collab_striver_ytdescription&utm_campaign=knapsack-with-duplicate-items
2. DP - 0 1 knapsack 
3. DP - Unbounded Knapsack
   
From 27 June 2024, coding in java, array 38

Integer.MIN_VALUE;          
Integer.MAX_VALUE;
Long.MIN_VALUE;
Long.MAX_VALUE;
Double.MIN_VALUE;
Double.MAX_VALUE;

list.stream().mapToInt(i -> i).toArray();

list.stream().mapToLong(i -> i).toArray();

list.stream().mapToDouble(i -> i).toArray();

List<String> list = new LinkedList<>(); 

list.add("a");

list.add("b");

List<Pair> l = list.stream().map(s -> new Pair(s)).collect(Collector.toList());

List<Pair> l = list.stream().map(s -> new Pair(s)).toList(); //Java11 or 17

Set<Pair> l = list.stream().map(s -> new Pair(s)).collect(Collector.toSet());

class Pair {
    String s;
    Pair(String s) {
        this.s = s;
    }
}
ArrayList<String> cars = new ArrayList<String>(); // Create an ArrayList object

cars.add("Volvo");

cars.add("BMW");

cars.get(0);

cars.set(0, "Opel");

cars.remove(0);

cars.clear();

cars.size();

Collections.sort(cars);

all add set get method are on LinkedList or ArrayList or any List objects
    

