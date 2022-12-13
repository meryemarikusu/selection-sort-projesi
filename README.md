## Selection Sort Projesi

[22,27,16,2,18,6]-> Insertion Sort

***Yukarıda verilen dizinin sort türüne göre aşamaları şu şekildedir:***

- Insertion Sort'a göre; verilen örüntüye ait elemanlara tek tek bakarak, küçükten büyüğe doğru sıralama senaryosunda ilk olarak en küçük sayı 2 ile en baştaki sayı 22'nin yeri değiştirilir. 

```[2|,27,16,22,18,6]```

- Bir sonraki aşamada dizideki 2. en küçük elemanı buluyoruz. Bu duruma göre 6 sayısı ile 2. sıradaki 27 sayısının yeri değiştirilir.

```[2,6|,16,22,18,27]```

- Oluşan yeni sayı dizindeki 3. en küçük eleman 16 olduğu için hiç yer değiştirmiyoruz.

```[2,6,16|,22,18,27]```

- Sayı dizisinin 4. en küçük elemanı 18 sayısı olacağı için 22 sayısı ile 18 sayısının yerleri değiştirilir.

```[2,6,16,18|,22,27]```

- Sayı dizisinin 5. elemanı 22 ve 6. elemanı 27 sıralı olduğu için insertion sort sıralaması tamamlanmıştır.

```[2,6,16,18,22,27]```

- *Big O notation gösterimi: "O (n^2)'dir".*  

- Time Complexity: [2,6,16,18,22,27] şeklinde dizi insertion sort'a göre sıralandığında, aradığımız sayı olan 18'in dizinin ortalarında olması nedeniyle case'i *average case* kapsamına girer.

---

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. adım: En küçük sayı 2 ile en baştaki sayı 7 yer değiştirir.

```[2|,3,5,8,7,9,4,15,6]```

2. adım: En küçük 2. sayı 3 olduğu için herhangi bir işlem yapmayız.

```[2,3|,5,8,7,9,4,15,6]```

3. adım: En küçük 3. sayı 4 olduğu için, 4 ile 3. sıradaki sayının yani 5'in yeri değiştirilir.

```[2,3,4|,8,7,9,5,15,6]```

4. adım: En küçük 4. sayı 5 olduğu için, 5 ile 4. sıradaki sayının yani 8'in yeri değiştirilir.

```[2,3,4,5|,7,9,8,15,6]```

[PatikaDev](https://app.patika.dev/meryemarikusu)
