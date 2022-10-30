# **[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
## **Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## **CEVAP:**

**root=7**

**5 sayısı 7'den küçük olduğunda 7'nin soluna ekleriz.**

**1 sayısı 5'ten ve 7'den küçük olduğunda 7 ve 5'in soluna ekleriz.**

**8 sayısı 7'den büyük olduğunda 7'nin sağına ekleriz.**

**3 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den büyük olduğunda 1'in sağına ekleriz.**

**6 sayısı 7'den küçük olduğunda 7'nin soluna, 5'ten büyük olduğunda 5'in sağına ekleriz.**

**0 sayısı 7'den, 5'ten ve 1'den küçük olduğunda 1'in soluna ekleriz.**

**9 sayısı 7'den ve 8'den büyük olduğunda 8'in sağına ekleriz.**

**4 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den ve 3'ten büyük olduğunda 3'ün sağına ekleriz.**

**2 sayısı 7'den ve 5'ten küçük olduğunda 5'in soluna, 1'den büyük olduğunda 1'in sağına ve 3'ten küçük olduğunda 3'ün soluna ekleriz.**

```

                       7
            5                      8
       1         6                       9
     0    3
        2   4

```
