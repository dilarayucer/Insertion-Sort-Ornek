# Insertion-Sort-Ornek

[22,27,16,2,18,6]

1.) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.) Big-O gösterimini yazınız.
3.) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


1.) 22 27 16 2 18 6 
    22 | 27 16 2 18 6
    22 27 | 16 2 18 6
    16 22 27 | 2 18 6
    2 16 22 27 | 18 6
    2 16 18 22 27 | 6
    2 6 16 18 22 27 

2.) Best Case: Verilen listenin elemanlarının sıraları bir biçimde olmasıdır. Bu durumda Big-O gösterimi "O(n)" olur.
    Worst Case: Verilen listenin elemanlarının büyükten küçüğe sıralanmasıdır. Bu durumda her eleman kontrol edileceği için elemlanların toplamı formülünden "O(n^2) olur.
    Average Case: Worst case ile aynıdır.
    Sonuç: O(n^2) , O(n)'den üstün olduğu için Big-O (n^2)'dir.
    

4.) Dizi sıralandıktan sonra 18 sayısı "Average Case" kapsamına girer.

----


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

7 3 5 8 2 9 4 15 16  

7 | 3 5 8 2 9 4 15 16  -> 1

3 7 | 5 8 2 9 4 15 16  -> 2

3 5 7 | 8 2 9 4 15 16  -> 3

3 5 7 8 | 2 9 4 15 16  -> 4

