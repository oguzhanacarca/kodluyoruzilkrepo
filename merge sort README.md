Proje 2
[16,21,11,8,12,22] -> Merge Sort
Yukarýdaki dizinin sort türüne göre aþamalarýný yazýnýz.
Big-O gösterimini yazýnýz.

Solution:

Step 1: [16,21,11,8,12,22] -> Merge Sort Aþamalarý:

[16,21,11] [8,12,22]
[16,21] / [11] [8,12] / [22]
[16] - [21] / [11] [8] - [12] / [22]
[16,21] / [11] [8,12] / [22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]

Step 2: Big-O -> O(nlogn)