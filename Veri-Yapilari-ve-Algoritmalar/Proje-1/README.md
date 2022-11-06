# Proje-1
### [22,27,16,2,18,6] - > Insertion Sort

#### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Algoritma, dizinin  üzerinde ileri doğru ilerleyerek, dizinin bir elemanını  alıp geriye doğru sıralama yapar. Sıralamada, sıradaki sayı eğer sıraladığı elemandan daha küçükse o elemanla yer değiştirerek, küçükten büyüğe doğru sıralama yapılır.

İlk sayı (22) olduğu için, hiç bir değişiklik olmaz.
|1. Adım|22|27|16|2|18|6|
|-------|- |- |- |-|- |-|

22 sayısı ile 27 sayısı karşılaştırılır. 22 sayısı küçük olduğu için değişiklik olmaz.
|2. Adım|22|27|16|2|18|6|
|-------|- |- |- |-|- |-|

16 sayısı ile 27 sayısı karşılaştırılır. 16 sayısı küçük olduğu için 16 sayısı ile 27 sayısı yer değiştirir. İkinci aşamada 16 sayısı ile 22 sayısı karşılaştırılır. 16 sayısı küçük olduğu için 22 sayısı ile yer değiştirir.
|3. Adım|22|16|27|2|18|6|--|16|22|27|2|18|6|
|-------|- |- |- |-|- |-|--|- |- |- |-|- |-|

2 sayısı ile 27 sayısını karşılaştırır. 2 sayısı küçük olduğu için yer değiştirir. İkinci aşamada 2 sayısı ile 22 sayısını karşılaştırır. 2 sayısı küçük olduğu için yer değiştirir. Üçüncü aşamada 2 sayısı ile 16 sayısını karşılaştırır. 2 sayısı küçük olduğu için yer değiştirir.
|4. Adım|16|22|2|27|18|6|--|16|2|22|27|18|6|
|-------|- |- |-|- |- |-|--|- |-|- |- |- |-|

|-- |2|16|22|27|18|6|
|---|-|- |- |- |- |-|

18 sayısı ile 27 sayısı karşılaştırılır. 18 sayısı küçük olduğu için yer değiştirir. 18 sayısı ile 22 sayısı karşılaştırılır. 18 sayısı küçük olduğu için yer değiştirir. 18 sayısı ile 16 sayısı karşılaştırılır. 18 sayısı büyük olduğu için yer değişikliği olmaz.
|5. Adım|2|16|22|18|27|6|--|2|16|18|22|27|6|
|-------|-|- |- |- |- |-|--|-|- |- |- |- |-|

6 sayısını gerisinde bulunan 27 sayısı ile karşılaştırır. 6 sayısı küçük olduğu için yer değiştirir. 6 sayısı ile 22 sayısını karşılaştırır. 6 sayısı küçük olduğu için yer değiştirir. 6 sayısı ile 18 sayısını karşılaştırır. 6 sayısı küçük olduğu için yer değiştirir. 6 sayısı ile 16 sayısını karşılaştırır. 6 sayısı küçük olduğu için yer değiştirir. 6 sayısını 2 sayısı ile karşılaştırır. 6 sayısı büyük olduğu için yer değişikliği olmaz.
|6. Adım|2|16|18|22|6|27|--|2|16|18|6|22|27|
|-------|-|- |- |- |-|- |--|-|- |- |-|- |- |

|-------|2|16|6|18|22|27|--|2|6|16|18|22|27|
|-------|-|- |-|- |- |- |--|-|-|- |- |- |- |

#### 2. Big-O gösterimini yazınız.

O( n ^ 2)

#### 3. Time Complexity
##### - Worst case: Aradığımız sayının sonda olması durumudur.
Aranan sayının sonda olması. Tarama zamanını uzatacaktır. Time Comlexity:  O(n ^ 2) olur.

#### - Average case: Aradığımız sayının ortada olması durumudur.
Time Comlexity : O(nlogn) olur.

#### - Best case: Aradığımız sayının dizinin en başında olması durumudur.
Time Comlexity: O(n) olur.

#### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? yazınız.
Dizinin ortasında yer aldığı için, average case kapsamına girer.

#### 2. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

|1. Adım|7|3|5|8|2|9|4|15|6|
|-------|-|-|-|-|-|-|-|- |-|

|2. Adım|3|7|5|8|2|9|4|15|6|
|-------|-|-|-|-|-|-|-|- |-|

|3. Adım|3|5|7|8|2|9|4|15|6|
|-------|-|-|-|-|-|-|-|- |-|

|4. Adım|3|5|7|8|2|9|4|15|6|
|-------|-|-|-|-|-|-|-|- |-|

## Patika Link

[patika.dev](https://app.patika.dev/cengizkadir)
