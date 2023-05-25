# Soru 
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# Cozum
Diziyi ikiye boluyoruz.

LEFT                            RIGHT
[16,21,11]                      [8,12,22]

Ikiye boluyoruz;

LEFT/2                          RIGHT/2
[16,21] [11]                    [8,12] [22]

Butun elemanlari tek kalacak sekilde ayiriyoruz.

LEFT                            RIGHT
[16] [21] [11]                  [8],[12],[22]

Birlestirme

LEFT                            RIGHT
[16,21] [11]                    [8,12], [22]

Birlestirme

LEFT                            RIGHT
[11,16,21]                      [8,12,22]

Left ve Right dizileri karsilastirma. Burada oncelikle en soldaki elemanlar karsilastirilacak. Cunku en kucukleri onlar. 8<11, 11<12 & 11<22  bu yuzden;
[8,11]

Kalan elemanlari karsilastirmaya devam ediyoruz.
16>12, 16<22, bu yuzden;
[8,11,12,16]

Son kalan iki eleman icin de karsilastirma yapilir. 21<22 ve bu yuzden;
[8,11,12,16,21,22]

Big O: O(nlogn)
