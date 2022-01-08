# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1-)Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

2-)Big-O gösterimini yazınız.

3-)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5-)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 # Soruların Cevapları
 1-) 
 1.adım -> [2,27,16,22,18,6]
 2.adım -> [2,6,16,22,18,27]
 3.adım -> [2,6,16,22,18,27] 2.index zaten doğru sırada olduğu için yer değiştirme yapılmadı.
 4.adım -> [2,6,16,18,22,27]
 5.adım -> [2,6,16,18,22,27] 4.index zaten doğru sırada olduğu için yer değiştirme yapılmadı.
 6.adım -> [2,6,16,18,22,27] böylece dizi sıralanmış oldu.
     
 2-) (n*(n+1))/2 = (n^2 + n)/2 --> O(n^2)
 
 3-) 
 Best case --> 2
 Worst case --> 27
 Average case --> 16,18
     
 4-) 18 sayısı Average case kapasımna girer.
 
 5-) 
 1.adım --> [2,3,5,8,7,9,4,15,6]
 2.adım --> [2,3,5,8,7,9,4,15,6] yer değiştirme yapılmadı.
 3.adım --> [2,3,4,8,7,9,5,15,6]
 4.adım --> [2,3,4,5,7,9,8,15,6]
