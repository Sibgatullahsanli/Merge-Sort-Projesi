# MERGE SORT PROJESİ

### proje 2

[8,11,12,16,21,22] -> Merge Sort
-
+ Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
+ Big-O gösterimini yazınız.

---
Dizinin sort aşamaları;

              [16,21,11,8,12,22]
               /              \
        [16,21,11]           [8,12,22]  
           /    \              /    \
       [16,21] [11]          [8,12] [22] 
         /  \    \            /  \    \
       [16] [21] [11]       [8] [12] [22]
         \   /    /          \   /    /
        [16,21] [11]         [8,12] [22]
            \    /              \    /
         [11,16,21]           [8,12,22]
                 \             / 
                [8,11,12,16,21,22]


Big-O 

Merge Sort’un time complexity’si :

+  Best Case : O(n*log n)  
+ Worst Case : O(n*log n)  
+ Average Case: O(n*log n)



[Patika.dev](www.patika.dev)
