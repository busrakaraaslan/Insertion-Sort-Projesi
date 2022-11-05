# Insertion-Sort-Projesi 

Patika.dev Insertion-Sort-Projes [Patika.dev](https://www.patika.dev/tr

1-[22,27,16,2,18,6] dizinin sort türüne göre aşamalarını yazınız.

  1.Aşama [2,22,27,16,18,6] n   (önce en küçük eleman ile en baştaki sayı yer değiştirir.)
  
  2.Aşama [2,6,22,27,16,18] n-1 (devamında ise ikinci en küçük eleman bulunur ve 2.sıra ile değiştirilir.)
  
  3.Aşama [2,6,16,22,27,18] 2-2
  
  4.Aşama [2,6,16,18,22,27] 1
  
  [22,16,27,2,18,6]
  
  [16,22,27,2,18,6]
  
  [16,22,2,27,18,6]
  
  [16,2,22,27,18,6]
  
  [2,16,22,27,18,6]
  
  [2,16,22,18,27,6]
  
  [2,16,18,22,27,6]
  
  [2,16,18,22,6,27]
  
  [2,16,18,6,22,27]
  
  [2,16,6,18,22,27]
  
  [2,6,16,18,22,27]
  
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

[3,7,5,8,2,9,4,15,6]

[3,5,7,8,2,9,4,15,6]

[3,5,7,2,8,9,4,15,6]

[3,5,2,7,8,9,4,15,6]

[3,2,5,7,8,9,4,15,6]

[2,3,5,7,8,9,4,15,6]

[2,3,5,7,8,4,9,15,6]

[2,3,5,7,4,8,9,15,6]

[2,3,5,4,7,8,9,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,7,8,9,6,15]

[2,3,4,5,7,8,6,9,15]

[2,3,4,5,7,6,8,9,15]

[2,3,4,5,6,7,8,9,15]

