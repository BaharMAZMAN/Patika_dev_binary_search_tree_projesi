# Patika_dev_binary_search_tree_projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Başlangıç root 5

Adım 1 root'un solunda [0,1,2,3,4], root'un sağında [6,7,8,9]

Adım 2 root'un soluna [0,1,2,3,4] bakalım. 2 elemanını alırsak solda [0,1], sağda [3,4] olur

Adım 3 [0,1] için 1 elemanını alırsak soluna [0] gelir, sağda eleman kalmıyor. sağda [3,4] 3 elemanını alırsak solda eleman olmaz sağa [4] gelir.

Adım 4 root'un sağına [6,7,8,9] bakalım. 8 elemanını alırsak soluna [6,7], sağına [9] gelir. [6,7] için 7 elamanını alırsak soluna [6] gelir, sağında eleman olmaz.

                           5
                           
                     2          8
                     
                  1    3      7    9
                  
                0        4  6
                
 https://www.patika.dev/tr
