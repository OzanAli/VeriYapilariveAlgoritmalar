# Insertion Sort Project
Project for patika.dev

> Veri Yapıları ve Algoritmalar Dersi Insertion Sort Projesi

Ozan Ali Altundal

[Patika.dev](www.patika.dev)

### Soru_1

[22,27,16,2,18,6] --> Insertion Sort

Step.0 --> [22,27,16,2,18,6] n

Step.1 --> [2,27,16,22,18,6] n-1

Step.2 --> [2,6,16,22,18,27] ...

Step.3 --> [2,6,16,18,22,27] ...

Step.4 --> [2,6,16,18,22,27] ...

Step.5 --> [2,6,16,18,22,27] 1


> Output --> [2,6,16,18,22,27]

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

Step.0 --> [7,3,5,8,2,9,4,15,6]

Step.1 --> [2,3,5,8,7,9,4,15,6]

Step.2 --> [2,3,5,8,7,9,4,15,6]

Step.3 --> [2,3,4,8,7,9,5,15,6]

Step.4 --> [2,3,4,5,7,8,8,15,6]
