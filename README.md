# Insertion_Sort
Selection sort stages, time complexity and other stuff about Selection sort but Patika dev. calls insertion sort. so be it:D
-----Stages of selection sort------
given list = [22,27,16,2,18,6]
->[2,27,16,22,18,6] #select first item of the list and search for smallest number in the list then switch their indexes.
->[2,6,16,22,18,27] #ignore and select second item of the list and do the same thing ....
->[2,6,16,22,18,27]
->[2,6,16,18,22,27]
->[2,6,16,18,22,27] #list is sorted.
-----Stages of selection sort------

---Big O notation---
O(n^2) because our process is like n+(n-1)+(n-2)+...+1 => n*(n+1)/2 is the final equation we can ignore n and take n^2 is our Big O notation.
---Big O notation---

------Time complexity------
Worst case and avarage case is O(n^2) but best case is the already sorted list so O(n)
Worst case: [
------Time complexity------

------Finding 18 in sorted list------
given sorted list = [2,6,16,18,22,27]
18 is like middle so we can say it's average case.
------Finding 18 in sorted------

------First 4 stages of selection sort-----
given list = [7,3,5,8,2,9,4,15,6]
-> [2,3,5,8,7,9,4,15,6]
-> [2,3,5,8,7,9,4,15,6]
-> [2,3,4,8,7,9,5,15,6]
-> [2,3,4,5,7,9,8,15,6]
------First 4 stages of selection sort-----

[Patika.dev](https://www.patika.dev/tr) 
