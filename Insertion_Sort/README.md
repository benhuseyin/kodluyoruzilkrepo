# Proje 1 - Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


# Cozum:

# [22,27,16,2,18,6] -> Insertion Sort

1. Asama
- 22 ve 27 karsilastirilir. 22 27'den kucuk oldugu icin islem yapilmaz.
- Dizinin son hali: [22,27,16,2,18,6]

2. Asama
- 27 ve 16 karsilasatirilir. 16 27 den ve 22'den kucuktur ve bu yuzden en basa alinir. 
- Dizinin son hali: [16,22,27,2,18,6]

3. Asama
- 27 ve 2 karsilastirilir. 2 sol tarafta siralanan tum degerlerden kucuk oldugu icin basa alinir.
- Dizinin son hali: [2,16,22,27,18,6]

4. Asama
- 18 ile sol tarafta siralanan degerler ile kiyaslamaya devam ediyoruz. 18>16 && 18<22 oldugu icin tam aralarinda yer almak durumundadir.
- Dizinin son hali: [2,16,18,22,27,6]

5. Asama
- 6 ile sol tarafta siralanan degerler kiyaslanir. 6>2 && 6<16 oldugu icin tam aralarina yerlestirilir.
- Dizinin son hali: [2,6,16,18,22,27]


- Dizinin son hali: [2,6,16,18,22,27]
Big O: n^2
18: Aradigimiz sayi ortada oldugu icin Average Case'e girer.



# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Asama
- 7 ile 2 yer degistirir. [2,3,5,8,7,9,4,15,6]

2. Asama
- Degisim olmaz

3. Asama
4 ile 5 yer degistirir. [2,3,4,8,7,9,5,15,6]

4. Asama
5 ve 8 yer degistirir. [2,3,4,5,7,9,8,15,6]
