# Merge-Sort-Projesi
Patika Dev Projem

[16,21,11,8,12,22]
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Başlangıçta dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar bölüyoruz. Tek eleman kalana kadar İşleme devam ediyoruz.

Diziyi ikiye bölerek yeniden yazıyoruz:

[16,21,11] - [8,12,22]

Tekrar ikiye bölüyoruz:

[16,21], [11]   -   [8], [12,22]      

Tekrar ikiye bölüyoruz:

[16], [21], [11]   -   [8], [12], [22] 

Birleştiriyouruz:

[16,21], [11]  -   [8], [12,22] 

Tekrar birleştiriyoruz: 

[11,16,21] - [8,12,22]

Tekrar birleştiriyoruz: 

[8,11,12,16,21,22]

2. Big-O gösterimini yazınız

Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. 
Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
