# **BINARY SEARCH TREE PROJECT**
Patika.dev Profile: https://app.patika.dev/emrebanzaroglu

# **PROJECT: Binary Search Tree Project** 

**[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

> Binary Search Tree algoritması elimizde bulunan veri dizisini sıralı olduğunu varsayar ve diziyi her seferinde ikiye bölerek ikili arama yapar. Root belirlenir, roottan küçük olan elemanlar sol tarafa, roottan büyük olanlar sağ tarafa toplanır.

```
1.Adım : Rootumuz -> 6
```

```
2.Adım : Sırayla gidiyoruz, 7 elemanı 6'dan büyük. Sağa ekliyoruz.

              6
               \
                7
```

```
3.Adım : 5 elemanı 6'dan küçük. Sola ekliyoruz.

              6
             / \
            5   7
```

```
4.Adım : 1 elemanı 6'dan küçük. Sola ekliyoruz. Alt elemana iniyoruz. 1 elemanı 5'den küçük 5'in soluna ekliyoruz.

              6
             / \
            5   7
           /
          1
```

```
5.Adım : 8 elemanı 6'dan büyük. Sağa ekliyoruz. Alt elemana iniyoruz. 8 elemanı 7'den büyük 7'nin sağına ekliyoruz.

              6
             / \
            5   7
           /     \
          1       8
```

```
6.Adım : 3 elemanı 6'dan küçük. Sola ekliyoruz. Alt elemana iniyoruz. 3 elemanı 5'ten küçük sola ekliyoruz. Alt elemana iniyoruz. 3 elemanı 1'den büyük 1'in sağına ekliyoruz.

              6
             / \
            5   7
           /     \
          1       8
           \
            3
```

```
7.Adım : 0 elemanı 6'dan küçük. Sola ekliyoruz. Alt elemana iniyoruz. 0 elemanı 5'ten küçük. Alt elemana iniyoruz. 0 elemanı 1'den küçük. 1'in soluna ekliyoruz.

              6
             / \
            5   7
           /     \
          1       8
         / \
        0   3
```

```
8.Adım : 9 elemanı 6'dan büyük. Sağa ekliyoruz. Alt elemana iniyoruz. 9 elemanı 7'den büyük. Sağa ekliyoruz. Alt elemana iniyoruz.9 elemanı 8'den büyük. 8'in sağına ekliyoruz.

              6
             / \
            5   7
           /     \
          1       8
         / \       \
        0   3       9
```

```
9.Adım : 4 elemanı 6'dan küçük. Sola ekliyoruz. Alt elemana iniyoruz. 4 elemanı 5'den küçük. Sol alta devam ediyoruz. 4 elemanı 1'den büyük. 1'in sağından devam ediyoruz. 4 elemanı 3'ten büyük. 3'ün sağına ekliyoruz.

              6
             / \
            5   7
           /     \
          1       8
         / \       \
        0   3       9
             \
              4
```

```
10.Adım : 2 elemanı 6'dan küçük. Sola ekliyoruz. Alt elemana iniyoruz. 2 elemanı 5'den küçük. Sol alta devam ediyoruz. 2 elemanı 1'den büyük. 1'in sağından devam ediyoruz. 2 elemanı 3'ten küçük. 3'ün soluna ekliyoruz ve sonuç.

              6
             / \
            5   7
           /     \
          1       8
         / \       \
        0   3       9
           / \
          2   4
```          
