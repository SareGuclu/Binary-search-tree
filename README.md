# Binary-search-tree
[7,5,1,8,3,6,0,9,4,2]
Root 5,
5'in sağ tarafı 5'den büyük
5'in sol tarafı 5'den küçük

1.step 7>5 =5 - 7
2.step 1<5 =5 - 1
              - 7
              
3.step 8 > 7 =     5
       8 > 5 =   1   7
                        8
4.step 3 < 5 =     5
       3 > 1     1    7
                 3     8
                 
5.step 6 >5  =     5
       6 <7      1    7
                 3   6  8
                 
6.step 0 < 5 =       5
       0 < 1      1     7
                0   3  6  8

7.step 9>5   =        5
       9>8         1      7
                 0   3   6  8
                              9
                              
8.step  4<5   =           5
                      1       7
                    0  3     6  8
                         4        9
                         
9.step  2<5   =            5
        2<3            1        7
                     0   3    6   8
                        2  4        9
