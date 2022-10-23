Veri Yapıları ve Algoritmalar eğitiminin ikinci projesi 
[Patika.dev](https://www.patika.dev/tr) , [Patika.dev/Esra Çağlayan](https://app.patika.dev/esracaglayan)
 ## Soru 1: [16,21,11,8,12,22] dizisinin Merge Sort aşamalarını yazın.
 * Diziyi ikiye bölerek başlıyoruz. Tek eleman oluncaya kadar bölmeye devam ediyoruz. 
 
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |- |- |- |- |- |- |- |- |- |- |- |- |
 |  |  |  |16|21|11|8 |12|22|  |  |  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |  |16|21|11|  |  |8 |12|22|  |  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |  |16|21|  |11|  |  |8 |  |12|22|  |
 |  |  |  |  |  |  |  |  |  |  |  |  |
 |16|  |21|  |11|  |  |8 |  |12|  |22|
 
 * Sıralama mantığına göre ikili birleştirme ile başlanır. Birleştirme işlemine devam edilir. Son adımda istenen sıralama bulunur.

|  |  |  |  |  |  |  |  |  |  |  |  |
|- |- |- |- |- |- |- |- |- |- |- |- |
|16|  |21|  |11|  |  |8 |  |12|  |22|
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |16|21|  |11|  |  |8 |  |12|22|  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |11|16|21|  |  |8 |12|22|  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |8 |11|12|16|21|22|  |  |  |

## Soru 2: Big-O gösterimini yazınız.

Merge işlemi için dizinin uzunluğu olan n işlem yapıldığı için O(n*(logn)) -> O(6*(log6)) diyebiliriz.

 
 
