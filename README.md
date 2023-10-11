# mergesortproject
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
[16,21,11]-----> [8,12,22]
sol kısım
[16]--[21,11]
sağ kısım
[8]--[12,22]
[16]-------[21]-------[11]-------[8]-------[12]------[22]
[16]---------[11,21]---------[8]---------[12,22]

[11,16,21]---------[8,12,22]
birleştiriyoruz
[8,11,12,16,21,22]
Big-O(nlogn)

