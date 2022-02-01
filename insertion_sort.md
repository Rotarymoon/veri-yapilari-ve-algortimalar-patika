[22,27,16,2,18,6]

#Sort aşamaları

I - [2,27,16,22,18,6] 
        #2 en önde

II - [2,6,16,22,18,27] 
        #6, 2. sırada

III - [2,6,16,18,22,27] 
        #18 ile 22 yer değişikliği

#Big-O Notation gösterimi

Dominant faktör - n [22,27,16,2,18,6] -- O(n)

#Time Complexity

    Worst case: O(n) 
    Average case: O(n/2) dominant faktör n 
    Best case: 1

Sıralamadan sonra 18 sayısı --> Average case kapsamında girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;

I- [2,3,5,8,7,9,4,15,6]
II- [2,3,4,8,7,9,5,15,6] 
III- [2,3,4,5,7,9,8,15,6] 
IV- [2,3,4,5,6,9,8,15,7]