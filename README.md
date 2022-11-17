# Patika.dev-Algoritma-ve-Veri-Yap-lar-
Algoritma ve veri yopıları ödevleri 
# Selection Örneği Çözümü
Selection sıralama algoritmasında dizi içerisindeki elemanlar teker teker kontrol edilerek sıralanır.

[22,27,16,2,18,6]  (n)

[2,27,16,22,18,6] (n-1)

[2,6,16,22,18,27] (n-2)

[2,6,16,22,18,27] (n-3)

[2,6,16,18,22,27] (n-4)

[2,6,16,18,22,27] (n-5)

Big-O gösterimi: n+(n-1)+(n-2)......+1= (n.(n+1))/2= (n^2+n)/2  Big O Notation denklemin en yüksek dereceli elemanını kabul etiğine göre; **Big O Notation= O(n^2)**

---

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
**Average case**

---
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]
