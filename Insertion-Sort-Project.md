 ## [22,27,16,2,18,6]

### Insertion-Sort steps
1.  [22,16,27,2,18,6]
2.  [16,22,27,2,18,6]
3.  [16,22,2,27,18,6]
4.  [16,2,22,27,18,6]
5.  [2,16,22,27,18,6]
6.  [2,16,22,18,27,6]
7.  [2,16,18,22,27,6]
8.  [2,16,18,22,6,27]
9.  [2,16,18,6,22,27]
10.  [2,16,6,18,22,27]
11.  [2,6,16,18,22,27]
---
big -O notation of sorting type is O(n^2) at average case

in this scenario, it is equal to **O(24)**

---
| **Time Complexity** | **Formulas** | **Results** |
|-----------------|----------|---------|
| **Worst Case**      |  O(N^2)  |  O(36)  |
| **Average Case**    |  O(N^2)  | O(36)   |
| **Best Case**       |   O(N)   |   O(6)  |

---

Dizi siralandiktan sonra 18 sayisi Average Case kategorisine girmektedir.

---
## [7,3,5,8,2,9,4,15,6]

1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,2,8,9,4,15,6]
4. [3,5,2,7,8,9,4,15,6]
