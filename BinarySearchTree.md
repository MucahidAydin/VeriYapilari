# Proje 3
A) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamalarını yazınız.
## Cevap
# A)
            1.durum      7                           7.durum         7  
                                                                   /   \
            2.durum      7                                       5       8
                        /                                      /   \
                       5                                     1       6
                                                            /  \
            3.durum       7                               0      3
                        /                                          
                       5                             8.durum        7
                     /                                            /   \ 
                   1                                            5       8
                                                              /   \       \
            4.durum       7                                  1      6       9
                        /   \                              /   \
                       5      8                          0       3
                     /   
                   1                                 9.durum         7
                                                                   /   \
            5.durum       7                                      5       8
                        /   \                                  /   \       \
                       5      8                               1      6       9
                     /                                      /   \
                   1                                      0       3
                     \                                              \
                       3                                              4
                       
            6.durum       7                          10.durum        7                   
                        /   \                                      /   \
                       5      8                                  5       8
                     /   \                                     /   \       \ 
                   1       6                                  1     6       9
                     \                                      /   \
                       3                                   0      3
                                                                 /  \
                                                               2      4
