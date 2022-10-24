# Binary-Search-Tree-Projesi
Veri Yapıları ve Algoritmaları üçüncü projesi, [Patika.dev](https://www.patika.dev/tr) , [Patika.dev/Esra Çağlayan](https://app.patika.dev/esracaglayan)
## Soru 1:  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Çözüm yöntemi: root=7 için dizinin bir sonraki elemanına bakılır. Eleman 7 den küçükse sola, büyükse sağa yazılır. Dizinin tüm elemanları bitene kadar root un yanındaki sayılar takip edilerek ağaç oluşturulur.


                                7
                             /     \
                           5        8
                         /   \       \
                       1      6       9
                     /   \          
                   0      3
                        /   \
                       2     4
