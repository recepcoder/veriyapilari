# Veri Yapıları ve Algoritmalar
## Merge Sort Projesi
### Ödev 
![Project 2](project2.png)
* Sıralı olmayan dizi ortadan iki eşit parçaya ayrılır.<br>
``[16,21,11]``  ve  ``[8,12,22]``
* Bu Ayırma işlemleri alt diziler en fazla 2 olana kadar yapılır.<br>
``[16,21] [11]``  ve ``[8] [12,22]`` 
* Alt diziler kendi içinde sıralanır.<br>
``[11,16,21]`` ve ``[8,12,22]``
* Sıralı alt diziyi tek dizi halinde birleştirilir.<br>
``[8,11,12,16,21,22]``
---
<br>
Big-O Gösterimi : O ( nlogn )