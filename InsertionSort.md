## INSERTION SORT PROJESİ
1)[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin Insertion Sort algoritmasına göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


#### Insertion Sort aşamaları
1.Adım: [**2**,27,16,**22**,18,6] --> En küçük sayıyı bulur, birinci eleman ile en küçük sayıyı yer değiştirir,sıradaki elemana geçilir

2.Adım: [2,**6**,16,22,18,**27**] --> En küçük ikinci sayıyı bulur,ikinci eleman ile bu sayıyı yer değiştirir,sıradaki elemana geçilir,

3.Adım: [2,6,**16**,18,22,27] --> Üçüncü elemanın en küçük üçüncü sayı olduğu için yer değişikliği olmaz,sıradaki elemana geçilir,

4.Adım: [2,6,16,**18**,22,27] --> Dördüncü elemanın en küçük dördüncü sayı olduğu için yer değişikliği olmaz,sıradaki elemana geçilir,

5.Adım: [2,6,16,18,**22**,27] --> Beşinci elemanın en küçük beşinci sayı olduğu için yer değişikliği olmaz,sıradaki elemana geçilir,
u
6.Adım: [2,6,16,18,22,**27**] --> Altıncı elemanın en küçük altıncı sayı olduğu için yer değişikliği olmaz, son eleman olduğu için sorting işlemi tamamlanır.

#### Big-O gösterimi
Big-O notation = O(n^2)  (bu örnek için n=6)

#### Time Complexity
**Average case:** Aradığımız sayının 16 olması.
<br>
**Worst case:** Aradığımız sayının 6 olması.
<br>
**Best case:** Aradığımız sayının 22 olması.

<br>
<br>
2)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
<br>
<br>
1.Adım: [**2**,3,5,8,**7**,9,4,15,6] --> En küçük sayıyı bulur, birinci eleman ile en küçük sayıyı yer değiştirir,

2.Adım: [2,**3**,5,8,7,9,4,15,6] --> En küçük ikinci sayıyı bulur,ikinci eleman ile bu sayıyı yer değiştirir,
,
3.Adım: [2,3,**4**,8,7,9,**5**,15,6] --> Üçüncü elemanın en küçük üçüncü sayı olduğu tespit edilir, yer değişikliği olmaz,sıradaki elemana geçilir,

4.Adım: [2,3,4,**5**,7,9,**8**,15,6] --> Dördüncü elemanın en küçük dördüncü sayı olduğu tespit edilir, yer değişikliği olmaz,sıradaki elemana geçilir
