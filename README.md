### VeriYapilariProjeleri-patika.dev

# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
[22,27,16,2,18,6]
[2,27,16,22,18,6]  //ilk adım 
[2,6,16,22,18,27]  
[2,6,16,22,18,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]
```
### 2. Big-O gösterimini yazınız.
```
O(n^2)
```
### 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
```
Average case
[22,16,2,6,18,27]

Worst case
[27,22,18,16,6,2]

Best case
[2,6,16,18,22,27]
```
### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Ortada bulunduğu için average case kapsamına girer. 
```
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```

# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort
### *Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```
  [16,21,11]           |  [8,12,22]
[16]  ||   [21,11]     | [8] ||   [12,22]
[16]  || [21] ||| [11] | [8] || [12] ||| [22]
[16]  || [11,21]       | [8] || [12,22]
[11,16,21]             | [8,12,22]
[8,11,12,16,21,22]

```

### *Big-O gösterimini yazınız.
```
O(nlogn)
```

