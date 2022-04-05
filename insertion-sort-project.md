# Problems
 
```
Proje 1
**[22,27,16,2,18,6]** -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

## Solution-1

```

**Insertion Sort**
[22,27,16,2,18,6]
[2,22,27,16,18,6]
[2,6,22,27,16,18]
[2,6,16,22,27,18]
[2,6,16,18,22,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

**Selection Sort (Derste Anlatilan)**
[22,27,16,2,18,6] (n)
[16,27,22,2,18,6] (n-1)
[16,22,27,2,18,6] (n-2)
[2,22,27,16,18,6] (n-3)
[2,16,27,22,18,6] (n-4)
[2,16,22,27,18,6] (n-5)
[2,16,18,27,22,6] (n-6)
[2,16,18,22,27,6] (n-7)
[2,6,18,22,27,16] (n-8)
[2,6,16,22,27,18] (n-9)
[2,6,16,18,27,22] (n-10)
[2,6,16,18,22,27] (1)

```
### Big O Notation
```
**Insertion Sort Icin**
Worst Case   : O(n^2)
Average Case : O(n^2)
Best Case    : O(n)

**Selection Sort Icin**
Worst Case   : O(n)
Average Case : O(n)
Best Case    : O(n)

**18 sayisi ortada oldugundan Average Case kapsamindadir.

```

## Solution-2
### [7,3,5,8,2,9,4,15,6] Dizisinin Insertion Sort'a Göre Ilk 4 Adımı
```
[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]
```
