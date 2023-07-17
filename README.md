# hakk-mda
Kodluyoruz Eğitim kapsamında açtığım ikinci repo
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
22 27de kü.ük olduğu için bir şey yapmıyacağız 
16 ilk 2 sayıdan büyük olduğu için en başa geçecek[16,22,27,2,18,6]
2 ilk 3 sayıdan büyük olduğu için en başa geçecek[2,16,22,27,18,6]
18 ilk 2 sayıdan büyük olduğu için 3.sıraya geçecek[2,16,18,22,27,6]
6 sadece ilk sayıdan büyük olduğu için 2. sırada olacak[2,6,16,18,22,27]

Big-O gösterimini yazınız.
  O(nkaredir)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması. 

worst case olması için en sonda olması gerekir ama 18 sayımız 5.sırada o yüzden değil
best case olması için en başta olması gerekirdi ama en başta da olmadığı için best case olamaz
average case olması için ortada veya sonda olmaması gerekir ve 5. sırada olduğu için 18 sayısı average casedir
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] bu dizenin en küçük sayısı 2 o yüzden 2 ile en baştaki 7 sayısının yerlerini değiştiriyoruz [2,3,5,8,7,9,4,15,6]
2den sonraki en küçük sayı 3 o yüzden 2den sonraki sayı ile 3ün yerini değiştirmemiz gerekir ama zaten 3 olduğu için işlem  yapmamız gerkekmez
3ten sonraki en küçük sayı 4 üçten sonraki sayı ise 5 o yüzden 4 ile 5i yer değiştirmemiz gerekir. [2,3,4,8,7,9,5,15,6]
4ten sonraki en küçük sayı 5 o yüzden beş ile 4ten sonraki sayı yani 8i yer değiştirmemiz gerekir.  [2,3,4,5,7,9,8,15,6]
