#Patika.dev Veri Yapıları ve Algoritmalar Projeleri
##Insertion Sort Projesi
### Soru
**[22, 27, 16, 2, 18, 6]** 
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
4. **[7, 3, 5, 8, 2, 9, 4, 15, 6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### Çözüm

1.    * 1.Döngü sonunda dizi [2, 27, 16, 22, 18, 6]
      * 2.Döngü sonunda dizi [2, 6, 16, 22, 18, 27]
      * 3.Döngü sonunda dizi [2, 6, 16, 22, 18, 27]
      * 4.Döngü sonunda dizi [2, 6, 16, 18, 22, 27]
      * 5.Döngü sonunda dizi [2, 6, 16, 18, 22, 27]
      * 6.Döngü sonunda dizi [2, 6, 16, 18, 22, 27]

2. Big-O = O(n)
3. Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.
4.    * 1.Döngü sonunda dizi [2, 3, 5, 8, 7, 9, 4, 15, 6]
      * 2.Döngü sonunda dizi [2, 3, 5, 8, 7, 9, 4, 15, 6]
      * 3.Döngü sonunda dizi [2, 3, 4, 8, 7, 9, 5, 15, 6]
      * 4.Döngü sonunda dizi [2, 3, 4, 5, 7, 9, 8, 15, 6]

## Merge Sort Projesi
### Soru
**[16, 21, 11, 8, 12, 22]**
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

### Çözüm

1.  * **[16, 21, 11]** - **[8, 12, 22]**
    * **[16]** - **[21, 11]** - **[8, 12]** - **[22]**
    * **[16]** - **[21]** - **[11]** - **[8]** - **[12]** - **[22]**
    * **[16, 21]** - **[8, 11]** - **[12, 22]**
    * **[8, 11, 16, 21]** - **[12, 22]**
    * **[8, 11, 12, 16, 21, 22]**
2. Big-O = O(nlog(n))

## Binary Search Tree Projesi
### Soru
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

## Çözüm
![BinaryTreeSearching](https://media3.giphy.com/media/lXJcZ5eUiuZtaEi4RX/giphy.gif?cid=790b76114a0091da248e7d68ca0726ed37de0d3f4a9f0a99&rid=giphy.gif&ct=g)