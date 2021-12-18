# Proje 1

#### [22,27,16,2,18,6] -> Insertion Sort
##### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
* [22,27,16,2,18,6]
* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]

##### Big-O gösterimini yazınız.
* O(n^2)

##### Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Average Case : 16,18 
* Worst Case : 27 
* Best Case : 2

##### Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* Average Case

##### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
* [2,3,5,8,7,9,4,15,6] 
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]
* [2,3,4,5,6,9,8,15,7]

---

# Proje 2

#### [16,21,11,8,12,22] -> Merge Sort
##### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                [16,21,11,8,12,22]
                /               \
            [16,21,11]          [8,12,22]
             /     \              /   \
          [16]   [21,11]         [8]  [12,22]
            |      /  \           |     /   \
          [16]   [21]  [11]      [8]  [12]  [22]
            |      \    /         |     \    /
          [16]     [11,21]       [8]   [12,22]
            \         /            \      /
            [11,16,21]            [8,12,22]
                      \          / 
                    [8,11,12,16,21,22]    

##### Big-O gösterimini yazınız.
* n = 2^x
* x = logn ise O(nlogn)

---
# Proje 3

#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary-Search-Tree
##### Binary Search Tree aşamalarını yazınız.

    Root = 7

           7
         /   \
        5     8
       / \     \
      1   6     9
     / \
    0   3
       / \
      2   4

