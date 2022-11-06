# Proje-2
### [16,21,11,8,12,22] -> Merge Sort

#### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız?
###### Dizi ikiye bölünür. Bölünen diziler tekrar ikiye bölünür. Tek eleman kalıncaya kadar İşleme devam edilir.

|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------  |- |- |- |- |- |- |- |- |- |- |- |- |
|                                                 |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Dizi ikiye bölünür.                              |  |  |16|21|11|  |  |8 |12|22|  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Sol ve sağdaki diziler tekrar ikiye bölünür.     |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Tek eleman kalana kadar bölme yapılır.           |16|  |21|  |11|  |  |8 |  |12|  |22|


######  Bölme işlemi bitikten sonra, tek elemanlı diziler ikili birleştirilir. Sıralı dizi elde edilinceye kadar bu işleme devam edilir.

|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|----------------------------------------------- |- |- |- |- |- |- |- |- |- |- |- |- |
|                                                |16|  |21|  |11|  |  |8 |  |12|  |22|
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|ikili sıralanarak birleştirilir.                |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|Tekrar ikili sıralama yapılarak birleştirilir.  |  |  |11|16|21|  |  |8 |12|22|  |  |
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|Son birleştirmede sıralı dizi elde edilir.      |  |  |  |8 |11|12|16|21|22|  |  |  |
    

#### 2. Big-O gösterimini yazınız.
Merge Sort türü sıralamada dizi sürekli ikiye bölünür. Merge Sort türünde, bölünmüş dizinin uzunluğu n işlem olduğu için O(n*(logn)) -- Big-O(6*(log6)) olur.

## Patika Link

[patika.dev](https://app.patika.dev/cengizkadir)
