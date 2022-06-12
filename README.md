# MergeSort
## Patika.dev Profilim = [https://app.patika.dev/krgzsalih](https://app.patika.dev/krgzsalih)

## Soru - 1
[16,21,11,8,12,22] dizinin sort türüne göre aşamalarını yazınız.

         [16,21,11]      [8,12,22]
        [16] [21,11]    [8] [12,22]
        [16] [21] [11]  [8] [12] [22]
          [16] [11,21]  [8,12,22]
            [11,16,21]  [8,12,22]
             [8,11,12,16,21,22]



## Soru - 2
Big-O gösterimini yazınız.

Tek parça kalıncaya kadar bölündüğünden ve eleman sayısı değişmediğinden yani n olarak kaldığından;
        
        Bunu da     2^x = n
                    logn = x  olarak buluruz.
        

Her işlemde n sayısı ile işlem yapıldığından;

Big-O = O(nlogn) olacaktır.