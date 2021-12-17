## Proje 2 - Merge Sort

[16,21,11,8,12,22]

SORU 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
Başlangıç:        [16,21,11,8,12,22]
                   /               \
1. Adım:     [16,21,11]          [8,12,22]
                 /   \             /    \
2. Adım:    [16,21]  [11]       [8,12]  [22]
             /   \     \         /   \     \
3. Adım:   [16] [21]  [11]     [8] [12]   [22]
             \   /     /        \   /     /
4. Adım:    [16,21] [11]        [8,12] [22]
              \      /            \     /
5. Adım:     [11,16,21]          [8,12,22]
                  \               /
6. Adım:         [8,11,12,16,21,22]
```

SORU 2: Big-O gösterimini yazınız.

```
O(n*logn)
```
