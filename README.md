## Insertion sort

[22,27,16,2,18,6]   --> Insertion sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: 
Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

-------
**Verilen örüntüye ait en küçük elemanı buluyoruz ve baştaki sayı ile yer değiştiriyoruz.Her elemanı tek tek inceleyip örüntüyü tamamlıyoruz.**

[2,27,16,22,18,6] En küçük sayı 2 olduğu için onu başa alıyoruz 22 sayısını onun yerine koyuyoruz.

[2,6,16,22,18,27]  2.aşama

[2,6,16,18,22,27]  son aşama

**O(n^2)**

18 sayısı dizinin ortasında bulunduğu için average case  kapsamına girer.


