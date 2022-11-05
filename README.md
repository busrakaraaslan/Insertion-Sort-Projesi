# Insertion-Sort-Projesi 

Patika.dev Insertion-Sort-Projes [Patika.dev] (https://www.patika.dev/tr)

1-[22,27,16,2,18,6] dizinin sort türüne göre aşamalarını yazınız.

  1.Aşama [22,27,16,2,18,6]  n   (önce en küçük eleman ile en baştaki sayı yer değiştirir.)
  
  2.Aşama [2,27,16,22,18,6] n-1 
  
  3.Aşama [2,6,16,22,18,27] n-2
  
  4.Aşama [2,6,16,18,22,27] 1
  
  
  
2-Big-O gösterimini yapınız.

Worst Case = O(n^2)

Average Case = O(n^2)

Best Case = O(n)

3-Time Complexity 

Average case : Aaradığımız sayının ortada olması

Worst case : Aradığımız sayının sonda olması 

Best case : Aradığımız sayının dizinin en başında olması

Average case -> [6,16,22,2,18,27]

Worst case  -> [27,22,18,16,6,2]

Best case -> [2,16,18,22,27]

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

Sıralandıktan sonra 18 sayısı dizinin ortasında bulunur. Bu nedenle average case kapsamına girer.

5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,4,15,6]

[2,3,4,8,7,5,15,6]

[2,3,4,5,7,8,15,6]

[2,3,4,5,6,8,15,7]

[2,3,4,5,6,7,15,8]

[2,3,4,5,6,7,8,15]
