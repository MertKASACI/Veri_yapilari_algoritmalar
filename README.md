
www.patika.dev


# Insertion Sort

1)

[22,27,16,2,18,6]----> Insertion Sort

[22,27,16,2,18,6]---->n

[2,27,16,22,18,6]---->(n-1)

[2,6,16,22,18,27]---->(n-2)

[2,6,16,18,22,27]----> 1

2)

Big-O = n*(n-1)*(n-2)*....1 ~ (n^2)

Big-O = O(n^2)

3)

Time Complexity

best case --->O(n)

average case --->O(n^2)

worst case --->O(n^2)

4)
Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.

5)
[7,3,5,8,2,9,4,15,6] ----> Insertion sort


[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[3,5,7,2,8,9,4,15,6]


# Merge Sort
 
 1)
 [16,21,11,8,12,22]----> Merge Sort
 
 [16,21,11]-[8,12,22]----> 1.bölme
 
 [16] - [21,11] - [8] - [12,22] ----> 2.bölme
 
 [16] - [21] - [11] - [8] - [12] - [22] ----> 3.bölme
 
 [16] - [21,11] - [8] - [12,22] ----> Sırala ve birleştir
 
 [11,16,21] - [8,12,22] ----> Sırala ve birleştir
 
 [8,11,12,16,21,22] -----> Tamamı ile sıralı
 
 2)
 Big-O  = O(n*logn)
 
 
 # Binary Search Tree
 
 [7,5,1,8,3,6,0,9,4,2] ----> Binary Search Tree
 
 1)Root 7'dir ve ilk elemandır
 
 2)5 7'den küçük olduğu için sola yazılır.
 
 3)1 hem 7 hem 5'ten küçük bu nedenle en sola yazılır.
 
 4)8 7'den büyüktür sağa yazılır.
 
 5)3 , 5 ve 7'den küçük fakat 1'den büyüktür . 1'in sağına yazılır.
 
 6)6 7'den küçük fakat 5'ten büyüktür . 5'in sağına yazılır.
 
 7)0 şu ana kadar gelen en küçük sayıdır . 1'in soluna yazılır.
 
 8)9 şu ana kadar gelen en büyük sayıdır . 8'in sağına yazılır.
 
 9)4 , 5 ve 7 den küçük fakat 1 ve 3 den büyüktür . 3'ün sağına yazılır.
 
 10)2 , 5 ve 7 den küçüktür . 1den büyük fakat 3'ten küçüktür . Bu nedenle 3'ün sağına yazılır.
 
                7
              /   \
             5     8
            / \   / \      -------------------------> Binary Search Son Hal
           1   6     9
          / \
         0   3
            / \
           2   4

 
 
 
 


