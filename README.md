# Merge-sort
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Çözüm:1
1.Adım key dizi[1]= [16,21,11,8,12,22]
2.Adım key dizi[2]= [16,21,11] [8,12,22]
3.Adım key dizi[3]= [16,21] [11] [8,12] [22]
4.Adım key dizi[4]= [16] [21] [11] [8] [12] [22]
5.Adım key dizi[5]= [16,21] [11]  [8,12] [22]
6.Adım key dizi[6]= [11,16,21]    [8,12,22]
7.Adım key dizi[7]= [8,11,12,16,21,22]

Big-O gösterimini yazınız.
Çözüm:2
O(logn)
