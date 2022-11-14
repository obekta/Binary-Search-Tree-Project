www.patika.dev

# Binary Search Tree Project

## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary Search Tree aşamalarını yazınız:

- Root 7 sayısıdır. Dizide sağa doğru tüm sayılar ile Binary Search Tree'yi oluşturacağız.

- 5, 7'den küçük olduğu için sol tarafına yazılır.

- 1, hem 7'den hem de 5'ten küçük olduğu için 5'in soluna yazılır.

- 8, 7'den büyük olduğu için onun sağına yazılır.

- 3, 7'den büyük, 5'ten küçük ve 1'den büyük olduğu için 1'in sağına yazılır.

- 6, 7'den küçük ama 5'ten büyük olduğu için 5'in sağına yazılır.

- 0, şu ana kadarki en küçük sayı olduğu için 1'in soluna yazılır.

-  9, şu ana kadarki sayıların en büyüğü olduğu için 8'in sağına yazılır.

- 4, 7 ve 5'ten küçük ama 1'den ve 3'ten büyük olduğu için 3'ün soluna yazılır.

- 2, 7 ve 5'ten küçük, 1'den büyük ama 3'ten küçük olduğu için 3'ün soluna yazılır.

                                  7
                                 / \
                               5     8
                              / \     \
                             1   6     9
                            / \
                           0   3
                              / \
                             2   4


   