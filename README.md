# BinarySearchTree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Cevap
----------------
Binary Search Treede en üstte bulunan node Root olarak adlandırılır.
Root’tan küçük değere sahip olan node’lar Root’un sol tarafında yer alır
Root’tan büyük değere sahip olan node’lar Root’un sağ tarafında yer alır.


Ağacın ilk node’u her zaman root node’dur. Eğer bir root yoksa ilk eklenen node’u root’a atarız.
root 7 dir.rootun sağında 5 bulunur solunda ise 8 bulunur. 8 in solunda 9 bulunur. 5 in solunda 6 sağında 1 bulunur.1 in sağında 0 solunda 3 bulunur 3 ün sağında 2 solunda 4 bulunur.Aşağıda da ağaç yapısını şema ile göstermeye çalıştım.


  
                               7
                               
                           8           5 
                        
                        9            6       1
                                         
                                            3      0
                                          4   2
                                         
