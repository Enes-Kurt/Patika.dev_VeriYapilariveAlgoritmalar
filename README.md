# Patika.dev_VeriYapilariveAlgoritmalar

[Patika.dev](https://app.patika.dev/) "Veri Yapıları ve Algoritmaları" dersi projeleri.

- Insertion Sort Projesi - Proje 1
- Marge Sort Projesi - Proje 2
- Binary Search Tree Projesi - Proje 3


## Insertion Sort Projesi - Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


### 1- Insertion Sort Aşamaları

1. [22,27,16,2,18,6]
2. [22,27,16,2,18,6]
3. [16,22,27,2,18,6]
4. [2,16,22,27,18,6]
5. [2,16,18,22,27,6] 
6. [2,6,16,18,22,27]


### 2- Big-O Gösterimi

- Best Case    --> O(n)
- Avarage Case --> O(n^2)
- Worst Case   --> O(n^2)


### 3- Time Complexity

- Best Case     --> [2,6,16,18,22,27]
- Avarage Case  --> [27,16,18,22,2,6]
- Worst Case    --> [27,22,18,16,6,2]


### 4- "18" Sayısı İçin Case Durumu

Diziin son hali [2,6,16,18,22,27] olduğu ve 18 sayısı ortada kısımlarda kaldığı için case durumu: "Avarage Case" olur.


### 5- [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

1. [7,3,5,8,2,9,4,15,6]
2. [3,7,5,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [3,5,7,8,2,9,4,15,6]



## Marge Sort Projesi - Proje 2

[16,21,11,8,12,22] -> Merge Sort

1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

### 1- Merge Sort Aşamaları

- Sayı dizisini sürekli 2 ye bölerek elde edilen diziner 2 veya daha az eleman sayısına ulaştığında bölme işlemi kesilir.
- Bölme işlemi kesildiiğin andaki her diziyi kendi içinde sıralarız.
- Sıralama bittikten sonra sıraya uygun olarak 2 şerli şekilde tekrar birleştirilir.

              [16,21,11,8,12,22]
               /             \
           [16,21,11]     [8,12,22]
            /      \       /      \
        [16,21]   [11]   [8,12]   [22]
            \      /       \      /
           [11,16,21]     [8,12,22]
                \             /
              [8,11,12,16,21,22]
              
### 2- Big-O Gösterimi         

- Best Case    --> O(n*logn)
- Avarage Case --> O(n*logn)
- Worst Case   --> O(n*logn)

## Binary Search Tree Projesi - Proje 2

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Binary Search Tree Aşamaları

- [7,5,1,8,3,6,0,9,4,2] dizisinin ilk sayısını root olarak seçeriz. Root: 7.
- Root sayısının seçtikten sonra ondan bir sonraki sayıyı yeni sayı olarak seçeriz.
- Seçtiğimiz yeni sayıyı root sayısından başlayarak eğer yeni sayı bir önceki sayıdan büyükse sayının sağına doğru küçükse soluna doğru kök şeklinde ilerletiriz.

                                --1-- (root: 7)
                                
                                  7
                                  
                                --2-- (yeni sayı: 5)
                                
                                  7
                                 / 
                                5    
                                
                                --3-- (yeni sayı: 1)
                                
                                  7
                                 / 
                                5   
                               /    
                              1      
                                
                                --4-- (yeni sayı: 8)
                                
                                  7
                                 / \
                                5   8
                               /    
                              1      
                                
                                --5-- (yeni sayı: 3)
                                
                                  7
                                 / \
                                5   8
                               /    
                              1      
                               \
                                3
                                
                                --6-- (yeni sayı: 6)
                                
                                  7
                                 / \
                                5   8
                               / \   
                              1   6   
                               \
                                3
                                
                                --7-- (yeni sayı: 0)
                                
                                  7
                                 / \
                                5   8
                               / \   
                              1   6   
                             / \
                            0   3
                                
                                --8-- (yeni sayı: 9)
                                
                                  7
                                 / \
                                5   8
                               / \   \
                              1   6   9
                             / \
                            0   3

                                --9-- (yeni sayı: 4)
                               
                                  7
                                 / \
                                5   8
                               / \   \
                              1   6   9
                             / \
                            0   3
                             \
                              4
                               
                               --10-- (yeni sayı: 2)
                               
                                  7
                                 / \
                                5   8
                               / \   \
                              1   6   9
                             / \
                            0   3
                           / \
                          2   4

Patika web adresi : [www.Patika.dev](https://www.patika.dev/)
