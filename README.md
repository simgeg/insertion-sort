# patika.dev

[22,27,16,2,18,6]-> Insertion Sort

S1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. 

S2) Big-O gösterimini yapınız.

S3)Time Complexity;

Average case: Aradığımız sayının ortada olması,

Worst case: Aradığımız sayının sonda olması, 

Best case: Best case: Aradığımız sayının dizinin en başında olması.

S4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

S5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

C1) 
Aşamalar: 

[2,27,16,22,18,6]
    
[2,6,16,22,18,27] 
    
[2,6,16,18,22,27]
    
C2) Big-O notation;

Worst case: n+(n-1)+(n-2)+.....+1 = (n)*(n+1)/2 --> O(n²)

Average Case: O(n²)

Best Case: O(n)

C3) Time Complexity;

Worst case: [27,22,18,16,6,2]
     
Avarage Case: [2,6,16,18,22,27]
    
Best case:  [2,6,16,18,22,27]
    
    
C4) Dizi sıralandıktan sonra 18 sayısı ortada olduğu için average case kapsamına girer.

C5) İlk dört adım;

Bİrinci adım: [2,3,5,8,7,9,4,15,6]

İkinci adım: [2,3,4,8,7,9,5,15,6]
    
Üçüncü adım: [2,3,4,5,7,9,8,15,6]
    
Dördüncü adım: [2,3,4,5,6,9,8,15,7] 

www.patika.dev
