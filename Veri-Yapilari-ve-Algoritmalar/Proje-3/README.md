# Proje-3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız?
###### İkili arama ağacında, bir düğüm her iki tarafa (sağ ve sola) referans verebilir.Root sayısının, sağ tarafında kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar yer alır.

|   Açıklama   |  |  |  |
|--            |- |- |- |
|   **root=7** |  | 7|  |


**5 sayısı 7'den küçük olduğunda 7'nin soluna eklenir.**
|   Açıklama   |        |  |  |
|--            |-       |- |- |
|              |        |  | 7|
|              |        | /|  |
|**5 ekledik** |**5**   |  |  |

**1 sayısı 5'ten ve 7'den küçük olduğundan, 1 sayısı 7 ve 5'in soluna eklenir.**
|    Açıklama  |        |  |  |  |  |
|            --|--      |--|- |- |- |
|              |        |  |  |  | 7|
|              |        |  |  | /|  |
|              |        |  | 5|  |  |
|              |        | /|  |  |  |
|**1 eklendi** |**1**   |  |  |  |  |

**8 sayısı 7'den büyük olduğundan, 8 sayısı 7'nin sağına eklenir.**
|    Açıklama  |  |  |     |  |  |  |     |
|--            |--|--|-    |- |- |- |-    |
|              |  |  |     |  | 7|  |     |
|              |  |  |     | /|  |\ |     |
|**8 eklendi** |  |  | 5   |  |  |  |**8**|
|              |  | /|     |  |  |  |     |
|              |1 |  |     |  |  |  |     |

**3 sayısı, 7 ve 5'ten küçük olduğundan 5'in soluna, 3 sayısı, 1'den büyük olduğundan 1'rin sağına eklenir.**
|    Açıklama  |  |  |     |  |  |  |  |
|--            |--|--|-    |- |- |- |- |
|              |  |  |     |  | 7|  |  |
|              |  |  |     | /|  |\ |  |
|              |  |  | 5   |  |  |  |8 |
|              |  | /|     |  |  |  |  |
|              |1 |  |     |  |  |  |  |
|              |  |\ |     |  |  |  |  |
|**3 eklendi** |  |  |**3**|  |  |  |  |

**6 sayısı, 7'den küçük oduğundan 7'nin soluna, 6 sayısı, 5'ten büyük olduğundan 5'in sağına eklenir.**
|    Açıklama  |  |  |  |  |     |  |  |
|--            |--|--|- |- |-    |- |- |
|              |  |  |  |  | 7   |  |  |
|              |  |  |  | /|     |\ |  |
|              |  |  | 5|  |     |  |8 |
|              |  | /|  |\ |     |  |  |
|**6 eklendi** |1 |  |  |  |**6**|  |  |
|              |  |\ |  |  |     |  |  |
|              |  |  | 3|  |     |  |  |

**0 sayısı, 7'den 5'ten ve 1'den küçük olduğu için 1'rin soluna eklenir.**
|    Açıklama  |     |  |  |  |  |  |  |  |  |
|--            |--   |--|- |- |- |- |- |- |- |
|              |     |  |  |  |  |  | 7|  |  |
|              |     |  |  |  |  |/ |  |\ |  |
|              |     |  |  |  | 5|  |  |  |8 |
|              |     |  |  |/ |  |\ |  |  |  |
|              |     |  | 1|  |  |  |6 |  |  |
|              |     | /|  |\ |  |  |  |  |  |
|**0 eklendi** |**0**|  |  |  | 3|  |  |  |  |

**9 sayısı, 7'den ve 8'den büyük olduğundan, 9 sayısını 8'in sağına eklenir.**
|    Açıklama  |  |  |  |  |  |  |  |  |  |  |     |
|--            |--|--|- |- |- |- |- |- |- |- |-    |
|              |  |  |  |  |  |  | 7|  |  |  |     |
|              |  |  |  |  |  | /|  |\ |  |  |     |
|              |  |  |  |  | 5|  |  |  |8 |  |     |
|              |  |  |  |/ |  |\ |  |  |  |\ |     |
|**9 eklendi** |  |  | 1|  |  |  |6 |  |  |  |**9**|
|              |  |/ |  |\ |  |  |  |  |  |  |     |
|              | 0|  |  |  | 3|  |  |  |  |  |     |

** 4 sayısı, 7'den ve 5'ten küçük olduuğu için 5'in soluna, 4 sayısı, 1'den ve 3'ten büyük olduğundan 3'ün sağına eklenir.
|    Açıklama  |  |  |  |  |  |  |     |  |  |  |  |
|--            |--|--|- |- |- |- |-    |- |- |- |- |
|              |  |  |  |  |  |  | 7   |  |  |  |  |
|              |  |  |  |  |  | /|     |\ |  |  |  |
|              |  |  |  |  | 5|  |     |  |8 |  |  |
|              |  |  |  | /|  |\ |     |  |  |\ |  |
|              |  |  | 1|  |  |  | 6   |  |  |  |9 |
|              |  | /|  |\ |  |  |     |  |  |  |  |
|              | 0|  |  |  |3 |  |     |  |  |  |  |
|              |  |  |  |  |  |\ |     |  |  |  |  |
|**4 eklendi** |  |  |  |  |  |  |**4**|  |  |  |  |

**2 sayısı, 7'den ve 5'ten küçük olduğu için 5'in soluna, 2 sayısı, 1'den büyük olduğundan 1'in sağına ve 3'ten küçük olduğundan 3'ün soluna eklenir.
|    Açıklama  |  |  |     |  |  |  |  |  |  |  |  |
|--            |--|--|-    |- |- |- |- |- |- |- |- |
|              |  |  |     |  |  |  | 7|  |  |  |  |
|              |  |  |     |  |  | /|  |\ |  |  |  |
|              |  |  |     |  | 5|  |  |  |8 |  |  |
|              |  |  |     | /|  |\ |  |  |  |\ |  |
|              |  |  |1    |  |  |  | 6|  |  |  |9 |
|              |  | /|     |\ |  |  |  |  |  |  |  |
|              | 0|  |     |  |3 |  |  |  |  |  |  |
|              |  |  |     | /|  |\ |  |  |  |  |  |
|**2 eklendi** |  |  |**2**|  |  |  |4 |  |  |  |  |


## Patika Link

[patika.dev](https://app.patika.dev/cengizkadir)








