# Insert Sort Explanat

 - [22,27,16,2,18,6] -> Insertion Sort
 - [2,27,16,22,18,6] -> Insertion Sort  **En küçük 2 olduğu için bununla EN BAŞTAKİ yer değiştirir.**
 - [2,6,16,22,18,27] -> Insertion Sort  **Üst sıradaki işlem yapldıktan sonra yan tarafına geçilir ve 2. en küçük sayı ile yer değiştirilir.**
 - [2,6,16,22,18,27] -> Insertion Sort  **Aynı işlem sıralı hale gelene kadar tekrar edilir.**
 - [2,6,16,18,22,27] -> Insertion Sort

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## BIG O(n^2)
- Linear Tip (N-1)
- İşlem sayısı 1 azalarak ilerler.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- ###Time Complexity: 
- ***Average case: Aradığımız sayının ortada olması.***
- ***Worst case: Aradığımız sayının sonda olması.*** 
- ***Best case: Aradığımız sayının dizinin en başında olması.***
- ### 18 is Average case
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]
- [2,3,4,5,6,7,8,15,9]
