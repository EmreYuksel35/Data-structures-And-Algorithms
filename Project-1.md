<h1>Selection Insertion Sort</h1>
<strong>Answer 1</strong>

````
                                   [7,3,5,8,2,9,4,15,6]
````
Write the first 4 steps of the sequence according to Selection Sort.
````
Answer:  
    Step 1 : [2,3,5,8,7,9,4,15,6]
    Step 2 : [2,3,4,8,7,9,5,15,6]
    Step 3 : [2,3,4,5,7,9,8,15,6]
    Step 4 : [2,3,4,5,6,9,8,15,7]
    ...
    Step 5 : [2,3,4,5,6,7,8,15,9]
    Step 6 : [2,3,4,5,6,7,8,9,15]
````
<strong>Answer 2</strong>
````
                                   [22,27,16,2,18,6]
````
<p>a) Write the stages of the sequence given above according to the Insertion Sort type.</p>

````
    Step 1 : [22,27,16,2,18,6] // If 27 < 22, change places. so fixed
    Step 2 : [22,16,27,2,18,6] // replace 27 and 16
    Step 3 : [16,22,27,2,18,6] // replace 22 and 16
    Step 4 : [16,22,2,27,18,6] // replace 2 and 27
    Step 5 : [16,2,22,27,18,6] // replace 22 and 2
    Step 6 : [2,16,22,27,18,6] // replace 2 and 16
    Step 7 : [2,16,22,27,6,18] // replace 27 and 18
    Step 8 : [2,16,22,6,27,18] // replace 22 and 18
    Step 9 : [2,16,6,22,27,18] // replace 27 and 6
    Step 10 : [2,6,16,22,27,18] // replace 22 and 6
    Step 11 : [2,6,16,22,18,27] // replace 18 and 6
    Step 12 : [2,6,16,18,22,27] // replace 16 and 6
    
````

<p>b) Write the Big-O notation.</p>

````
  O(n^2)
````

<p>c) Time Complexity: After the array is sorted, which of the following cases does the number 18 fall under? Write.</p>
<ol>
  <li>Average Case: The number sought is in the middle</li>
  <li>Worst Case: The number you are looking for is at the end</li>
  <li>Best Case: The number sought is at the beginning of the array</li>
</ol>

````
   Answer C : Average Case
````

<h1>Merge Sort</h1>
<strong>Answer 1</strong>

````
                                   [16,21,11,8,12,22]
````
<p>a) Write the stages of the above sequence according to the sort type.</p>

````

Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]
````
<p>b) Write the Big-O notation.</p>

````
   Answer B : O(n logn)
````

<h1>Binary Search Tree </h1>
<strong>Answer 1</strong>

```
[7,5,1,8,3,6,0,9,4,2]
```
<p>Write the steps of the Binary Search Tree sequence.
Example: root is x. y is found to the right of the root. To the left of it is z, etc.</p>

````
Root x = 6
                             6
                           /   \ 
                          5     7
                        /         \
                       1           8
                     /   \           \
                    0     3           9
                        /   \      
                       2     4    
                                
Step 1:     For 7 > 6, there is 7 to the right of the root.
Step 2:     For 5 < 6, there is 5 to the left of the root.
Step 3:     For 1 < 6, 1 is added to the left of the root.
Step 4:     For 8 > 6, 8 is added to the right of the root.
Step 5:     For 3 < 6, 3 is added to the left of the root.
Step 6:     For 0 < 6, 0 is added to the left of the root.
Step 7:     For 9 > 6, 9 is added to the right of the root.
Step 8:     For 4 < 6, 4 is added to the left of the root.                       
Step 9:     For 2 < 6, 2 is added to the left of the root.
````
