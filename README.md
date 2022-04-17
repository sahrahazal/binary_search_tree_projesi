# Binary Search Tree Projesi

#### Proje 3
**[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
**Örnek:** root x'dir. root'un sağından y bulunur. Solda z bulunur vb.

```
Root: 7'dir. 
**Dizideki sırayla devam ediyorum.
5: 7'den küçük olduğu için sol tarafa alıyorum.
1: Sol taraftaki 5'ten sonra geliyor.
8: 7'den büyük olduğu için sağ tarafa alıyorum.
3: 7'den küçük, sol taraftan devam ediyorum. 5 geliyor. 5' ten sonra 1 geldiği için 5'in sol kısmından edge çekiyorum ve subtree'si oluyor.
6: 7'nin solundan bakıyorum 5 var. 5'ten büyük olduğu için 5'in sağ tarafına edge ile yeni subtree oluşturuyorum.
0: 7'den küçük, 5'ten küçük, 1'den de küçük olduğu için 1'den sonra edge çekiyorum ve en sona yazıyorum.
9: 7'den büyük sağ tarafta 8 vardı. 8'den de büyük 8'den sonra edge yapıyorum ve sağ tarafın en sonuna yazıyorum.
4: 7'den küçük soldan devam ediyorum. 5'den sonra 1 var. O zaman subtree'lerine bakıyorum. Sağ tarafında 6 var. 4, 6'dan küçük o zaman sol tarafta ki 3'ün sağ tarafına yazıyorum.
2: 7'den küçük soldan devam ediyorum. 5'den sonra 1 var. O zaman subtree'lerine bakıyorum. Sağ tarafında 6 var. 2, 6'dan küçük o zaman sol tarafta ki 3'ün sol tarafına yazıyorum.


                              [7]
                             /   \
                          [5]     [8]
                         /  / \      \   
                      [1]  [3] [6]    [9]
                     /    /   \ 
                  [0]  [2]     [4]

```



www.patika.dev
