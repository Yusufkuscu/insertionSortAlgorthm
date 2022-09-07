# [22,27,16,2,18,6] -> Insertion Sort
[22,27,16,2,18,6]  
## 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
- [22,27,16,2,18,6]
- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]

## 2.Big-O Gösterimini yazınız.
```
 n + n-1 + n-2 + ... + 1 = (n * (n + 1)) / 2 = (n² + n) / 2 = O(n²) 
 O(n^2)
```

## 3.Time Complexity:
 Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

## 4.Dizi Sıralandıktan sonra 18 sayısı handi case kapsamına girer.  
Dizi sıralandıktan sonra 18 sayısı ortada olduğu için Avarage Case kapsamına girer.

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
- [2,3,4,5,6,9,8,15,7]