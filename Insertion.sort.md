# Insertion Sort Project
Project for patika.dev

> Veri Yapıları ve Algoritmalar Dersi Insertion Sort Projesi

Ozan Ali Altundal

[Patika.dev](www.patika.dev)

## Part 1
### Soru 1


| Adım0 | 22 | 27 | 16 | 2 | 18 | 6 | 
| ----- | -- | -- | -- | - | -- | - |

| Adım1 | 2 | 27 | 16 | 22 | 18 | 6 | 
| ----- | - | -- | -- | -- | -- | - |

| Adım2 | 2 | 6 | 16 | 22 | 18 | 27 | 
| ----- | - | - | -- | -- | -- | -- |

| Adım3 | 2 | 6 | 16 | 22 | 18 | 27 | 
| ----- | - | - | -- | -- | -- | -- |

| Adım4 | 2 | 6 | 16 | 18 | 22 | 27 | 
| ----- | - | - | -- | -- | -- | -- |

| Adım5 | 2 | 6 | 16 | 18 | 22 | 27 | 
| ----- | - | - | -- | -- | -- | -- |

Sonuç:

| 2 | 6 | 16 | 18 | 22 | 27 | 
| - | -- | -- | -- | -- | - |


### Soru_2
n + (n-1) + (n-2) + ... + 1 = n.(n+1)/2 

**Dominant olan terim** Big O notationda dikkate alınır.

> Big O notation ---> O(n.n)

### Soru_3

Best Case: Sıranın en baştan küçükten büyüğe doğru, düzgün bir biçimde sıralanmış olma durumu

***Big O notation --> O(n)***

Average Case: Sıranın rastgele dağıldığı, genelde beklenilen durum

***Big O notation --> O(n.n)***

Worst Case: Sıranın olabilecek en kötü şekilde sıralanmış olma durumu

***Big O notation --> O(n.n)***

### Soru_4

18 Sayısı sıranın ortasında olduğu için, average case kapsamına girer.



## Part 2


| Adım0 | 7 | 3 | 5 | 8 | 2 | 9 | 4 | 15 | 6 |
| ----- | - | - | - | - | - | - | - | -- | - | 

| Adım1 | 2 | 3 | 5 | 8 | 7 | 9 | 4 | 15 | 6 |
| ----- | - | - | - | - | - | - | - | -- | - | 

| Adım2 | 2 | 3 | 5 | 8 | 7 | 9 | 4 | 15 | 6 |
| ----- | - | - | - | - | - | - | - | -- | - | 

| Adım3 | 2 | 3 | 4 | 8 | 7 | 9 | 5 | 15 | 6 |
| ----- | - | - | - | - | - | - | - | -- | - | 

| Adım4 | 2 | 3 | 4 | 5 | 7 | 9 | 8 | 15 | 6 |
| ----- | - | - | - | - | - | - | - | -- | - | 
