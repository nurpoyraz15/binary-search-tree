# binary-search-tree

## PROJE 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.<br>

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.<br>

## ÇÖZÜM
root 5'dir. Rootun sağında kendisinden büyükler yer alırken solunda ise küçükler bulunur. Buna göre rootun sağında; 1,3,0,4 ve 2 bulunur. Solunda ise 7,8,6,9 bulunmaktadır. <br>
Solundaki sayıları 0,1,2,3,4 olarak sıralamamız gerekir. solundaki veriler için de 6,7,8,9 şeklinde olmalıdır.<br>
Bizim bulmamız istenilen bir veri için rootun durumuna göre sağına soluna bakmamız gerekir. <br>
Binary search treesi için veriyi bulmak için roottan başlayarak yapmamız gereken işlem bu şekildedir. <br>
