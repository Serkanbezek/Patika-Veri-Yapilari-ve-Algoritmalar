# Proje 2
[16,21,11,8,12,22] -> Merge Sort

1-)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
2-)Big-O gösterimini yazınız.  

# Soruların Cevapları

1-) 1.adım --> [16,21,11][8,12,22]  
    2.adım --> [16,21][11][8,12][22]  
    3.adım --> [16][21][11][8][12][22]  
    4.adım --> [16,21][8,11][12,22]  
    5.adım --> [8,11,16,21][12,22]  
    6.adım --> [8,11,12,16,21,22]  
    
2-) 2^x = n  
    logn = x  
    O(nlogn)
