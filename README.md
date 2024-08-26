# insertionsortproje
[22,27,16,2,18,6]->Insertion sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
1.Avarage case: Aradığımız sayının ortada olması.
2.Worst case: Aradığımız sayının sonra olması.
3.Best case: Aradığımız sayının dizinin en başında olması. 
[22,27,16,2,18,6]->En küçük sayıyı bul. Burada 2. Bu sayıyı en başa yaz. Baştaki sayıyı da 2'nin yerine yaz. (n tane işlem yapıldı.)
[2,27,16,22,18,6]->2 artık sabit. Kalan sayıların içindeki en küçük sayıyı bul ve 27 ile yer değiştir. ((n-1) işlem yapıldı.)
[2,6,16,22,18,27]->2 ve 6 sabit.Kalan sayılar içinden en küçük sayıyı bul.Burada 18. 18 ile 22'nin yerini değiştir. ((n-2) işlem yapıldı.) 
[2,6,16,18,22,27]->2,6,16 ve 18 sabit. 22<27. (Bir işlem kalana kadar bu işlemlere devam edildi.)
18 sayısı avarage case durumunda.
Big-O gösterimi: 
n+(n-1)+(n-2)+(n-3)+...+1=n.(n+1)/2=n^2+n/2 
O(n^2)
