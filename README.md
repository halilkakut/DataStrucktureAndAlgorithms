# DataStrucktureAndAlgorithms
**[22,27,16,2,18,6]**  -> Insertion Sort

1.  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.  Big-O gösterimini yazınız.
3.  Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

## Cevap
1.**[22,27,16,2,18,6]**  n
2.**[2,27,16,22,18,6]**  n-1
3.**[2,6,16,22,18,27]**  n-2
4.**[2,6,16,22,18,27]**  n-3
5.**[2,6,16,18,22,27]**  n-4
6.**[2,6,16,18,22,27]**  n-5
n * (n+1) / 2 = n^2
Time Complexity : Worst case O(n^2)
4. 18 sayısı Average case kapsamına girer.
