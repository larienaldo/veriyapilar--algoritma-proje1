# veriyapilar--algoritma-proje1

## 1.[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

1.adım : 22 kendi başına sıralıdır .Dokunulmaz
2.adım : 22|27 kıyaslanır. 22 küçük olduğu için aynı kalır.
3.adım : 27 | 16 kıyaslanır. Yer değiştirilir. [22,16,27,2,18,6]
4.adım : 16|22 kıyaslanır ve yer değiştirilir. [16,22,27,2,18,6]
5.adım : 27|2 kıyaslanır. Daha sonra  22|2 ve 16|2 kıyaslanır. [16,22,2,27,18,6]--> [16,2,22,27,18,6]--> [2,16,22,27,18,6]
6.adım : 27|18 kıyaslanır. Yer değiştirir. Daha sonra 27|18, 22|18 16|18 karşılaştırılır. 16 dah aküçük olduğu için yer değiştirmez. [2,16,22,18,27,6]-->[2,16,18,22,27,6]
7.adım : 27|6 karşılaştırılır. 22|6, 18|6, 16|6 karşılaştırılır.Yer değiştirilir. 2|6 karşılaştırılır.2 küçük olduğu için yer değiştirmezler. [2,16,18,22,6,27]-->[2,16,18,6,22,27]-->[2,16,6,18,22,27]-->[2,6,16,18,22,27]
Sonucumuz budur : [2,6,16,18,22,27]
Big-O : (n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı : Ortada olduğu için Average Case kapsamına girer. "Average case: Aradığımız sayının ortada olması"

## 2.[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1.adım: En küçük sayımız olan 2 yi buluyoruz. İlk sırayla karşılaştırıyoruz.2 7'den küçük olduğu için yer değiştiriyoruz. [2,3,5,8,7,9,4,15,6]
2.adım: İkinci en küçük sayımız 3. İkinci sırada olduğu için yeri aynı kalıyor.
3.adım: Üçüncü en küçük sayımız 4. Üçüncü sıramıza bakıyoruz. 5 ile yer değiştiriyoruz. [2,3,4,8,7,9,5,15,6]
4.adım: Dördüncü en küçük sayımızı (5) dördüncü sıramızla karşılaştırıp yer değiştiriyoruz. [2,3,4,5,7,9,8,15,6]
