# InsertionSort

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-[2,27,16,22,18,6]
2-[2,6,16,22,18,27]
3-[2,6,16,22,18,27]
4-[2,6,16,18,22,27]
5-[2,6,16,18,22,27] 


2.Big-O gösterimini yazınız.

n+(n-1)+(n-2)+...+1 -> Big-O gösterimi O(n^2) olur.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Average case:n/2 işlem(3-4)
Worst Case:n tane işlem(6)
Best Case:1 işlem
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Avarage case kapsamında olur.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


[7, 3, 5, 8, 2, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]
