# Proje 1- Insertion Sort

Proje 1 [22,27,16,2,18,6] -> Insertion Sort  
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 
Big-O gösterimini yazınız. 
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.   
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Insertion-Sort-Aşamaları

[22,27,16,2,18,6]-(n)
[2,27,16,22,18,6]-(n-1)
[2,6,16,22,18,27]-(n-2)
[2,6,16,18,22,27]-(n-3)


# Big-O-Notation

Worst Case: o(n^2)=n+(n-1)+(n-2)+...+1
Average Case: O(n^2)
Best Case: O(n)

# Time-Complexity

Worst Case:[27,22,18,16,6,2]
Best Case: [2,6,16,18,22,27]

# [7,3,5,8,2,9,4,15,6]-İlk-4-Adım

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]


# Proje 2- Merge Sort

[16,21,11,8,12,22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.


# Sort

[16,21,11,8,12,22]

[16,21,11]            [8,12,22] 

[16,21]   [11]      [8,12]   [22] 

[16] [21] [11]      [8]  [12]  [22] 

[16,21]       [8,11]      [12,22]

  [8,11,16,21]          [12,22]	
      
        [8,11,12,16,21,22]
		


# Big-O Notation

O(nlogn)


www.patika.dev

