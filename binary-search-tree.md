# Problem
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
```

## Solution
```
1. Verilen array sirali hale getirilir.
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

2. Verilen arrayde ortadaki sayi 4'tur. Root elemanimiz = 4

             4
        /         \
       1           7
      / \         /  \
     0   2       6    8
          \     /      \  
           3   5        9
     
- 4'un solunda 1, saginda 7 elemani bulunur.
- 1'in solunda 0, saginda 2 elemani bulunur.
- 7'nin solunda 6, saginda 8 elemani bulunur.
- 2'nin saginda 3 elemani bulunur.
- 6'nin solunda 5, 8'in saginda 9 elemani bulunur.
```
