[22,27,16,2,18,6] -> Insertion Sort

22, tek başına olduğu için zaten sıralıdır.
27, 22'den büyük olduğu için sağa kaydırılır: [27,22,16,2,18,6]
16, 27'den küçük olduğu için soluna kaydırılır: [16,27,22,2,18,6]
2, solundaki tüm sayılardan küçük olduğu için ilk sıraya yerleştirilir: 
[2,16,27,22,18,6]
18, 27'den küçük, 16'dan büyük olduğu için araya yerleştirilir: 
[2,16,18,27,22,6]
6, solundaki tüm sayılardan küçük olduğu için ilk sıraya yerleştirilir: 
[2,6,16,18,27,22]
Dizi, artan sırada sıralandığından, sonuç olarak [2,6,16,18,22,27] 
olacaktır.

Big-O gösterimi, insertion sort için O(n^2) olacaktır.

18 sayısı, dizinin ortasında olduğu için average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:

1-[2,3,5,8,7,9,4,15,6]
2-[2,3,5,8,7,9,4,15,6]
3-[2,3,4,8,7,9,5,15,6]
4-[2,3,4,5,7,9,8,15,6]
