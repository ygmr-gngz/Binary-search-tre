# Binary-search-tre

7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root: 6 
       
                         6
                       /   \ 
                      5     7
                    /         \
                   1           8
                 /   \           \
                0     3           9
                    /   \      
                   2     4  

                   1.)Önce root değeriolarak 6 belirliyoruz.
                   2.)Sonra 7 deperini ekliyoruz, 6 dan büyük olduğu için sağ tarafına yazılır.
                   3.)Sonra 5 değerine sıra geliyor aynı işlemi de ona yapıyoruz bu sefer küçük oldupu için sol kısma yazılır. 
                   4.)Sonra 1 için de aynı işlemi yapıyoruz bu sefer 5 sayısını baz alarak yapılır ve diğer rakamlarda bir üstünde yazan rakamlara göre eger rakamdan küçük ise soluna, büyük ise sağına yazılır. En son rakam eklendiğinde işlem bitmiş olur.
