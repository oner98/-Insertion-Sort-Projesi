# -Insertion-Sort-Projesi
Kodluyoruz Eğitimi kapsamında açtığım bir proje
Verilen dizi: [22, 27, 16, 2, 18, 6]

Insertion Sort algoritmasını adım adım uygulayalım:

İlk adım (i=1): [22, 27, 16, 2, 18, 6]

27 zaten yerinde, değişiklik yok.
İkinci adım (i=2): [22, 27, 16, 2, 18, 6]

16, 27'den küçük olduğu için 27'nin önüne taşınır: [22, 16, 27, 2, 18, 6]
16, 22'den küçük olduğu için 22'nin önüne taşınır: [16, 22, 27, 2, 18, 6]
Üçüncü adım (i=3): [16, 22, 27, 2, 18, 6]

2, 27'den küçük olduğu için 27'nin önüne taşınır: [16, 22, 2, 27, 18, 6]
2, 22'den küçük olduğu için 22'nin önüne taşınır: [16, 2, 22, 27, 18, 6]
2, 16'dan küçük olduğu için 16'nın önüne taşınır: [2, 16, 22, 27, 18, 6]
Dördüncü adım (i=4): [2, 16, 22, 27, 18, 6]

18, 27'den küçük olduğu için 27'nin önüne taşınır: [2, 16, 22, 18, 27, 6]
18, 22'den büyük olduğu için yerinde kalır.
Beşinci adım (i=5): [2, 16, 22, 18, 27, 6]

6, 27'den küçük olduğu için 27'nin önüne taşınır: [2, 16, 22, 18, 6, 27]
6, 18'den küçük olduğu için 18'in önüne taşınır: [2, 16, 22, 6, 18, 27]
6, 22'den küçük olduğu için 22'nin önüne taşınır: [2, 16, 6, 22, 18, 27]
6, 16'dan küçük olduğu için 16'nın önüne taşınır: [2, 6, 16, 22, 18, 27]
6, 2'den büyük olduğu için yerinde kalır.
Sonuç: [2, 6, 16, 18, 22, 27]

Big-O Gösterimi
Insertion Sort'un en kötü durum (worst case) zaman karmaşıklığı: O(n^2)

Time Complexity Case'i
Dizi sıralandıktan sonra 18 sayısı ortada yer almaktadır. Bu yüzden 18 sayısı Average Case kapsamına girer.

Selection Sort Aşamaları
Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort algoritmasını adım adım uygulayalım:

İlk adım:

Minimum değeri bul ve en baştaki ile değiştir: [2, 3, 5, 8, 7, 9, 4, 15, 6]
İkinci adım:

Kalan kısmın minimum değerini bul ve ikinci eleman ile değiştir: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Üçüncü adım:

Kalan kısmın minimum değerini bul ve üçüncü eleman ile değiştir: [2, 3, 4, 8, 7, 9, 5, 15, 6]
Dördüncü adım:

Kalan kısmın minimum değerini bul ve dördüncü eleman ile değiştir: [2, 3, 4, 5, 7, 9, 8, 15, 6]
Sonuç olarak, Selection Sort algoritmasına göre ilk 4 adımda dizi şu hale gelir: [2, 3, 4, 5, 7, 9, 8, 15, 6]
