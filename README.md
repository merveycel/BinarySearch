# BinarySearch
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  
## dizisinin Binary-Search-Tree aşamaları;  
x = root;  
x = 6 olarak seçtim 

İlk olarak diziyi küçükten büyüğe sıraladık

[0,1,2,3,```4```5,6,7,8,9] --> ortadaki sayı 4. 4'ün solundaki sayılar 6'dan küçük olduğu için çıkartıldı; 

[~~0,1,2,3,~~```4```5,6,7,8,9] 

[4,5,6,```7```,8,9] --> ortadaki sayı 7 oldu. 6, 7'den küçük olduğu için 7'nin sağ tarafı elendi;  

[4,5,6,```7```,~~8,9~~]  

[4,```5```,6,7] --> ortadaki sayı 5 oldu. 6, 5'den büyük olduğu için 6'nın sol tarafı silindi;  

[~~4~~,```5```,6,7]  

[5,```6```,7] --> yeni diziye göre ortadaki sayı 6'dır. Ve sonuç bulunur!   
***
www.patika.dev