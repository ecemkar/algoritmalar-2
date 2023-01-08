## Proje-2

Merge Sort 

[16,21,11,8,12,22] Merge Sort algoritmasına göre sıralarken, küçükten büyüğe sıralama yapmak yerine parçalara bölerek küçük gruplar haline getirip, birleştirirken sıralama yapmaya yönelik çalışıyor.

[16,21,11,8,12,22]
[16,21,11]-[8,12,22]
[16,21]-[11] -- [8,12]-[22]
[16]-[21]-[11] -- [8]-[12]-[22]
[16,21]-[11] -- [8,12]-[22]
[11,16,21] -- [8,12,22]
[8,11,12,16,21,22] şeklinde olur.

Big-O n(logn) olur.