Arrayı ikiye böldük.

[16,21,11] ve [8,12,22]
Sol tarafı tekrar ikiye böldük.
[16,21] ve [11]
Ve tekrar…
[16], [21] elde edildi. Sorting yapmaya başlıyoruz en küçük 16 olduğu için aynen yazıyoruz.
[16,21], [11] 
[11,16,21]
Aynı işlemleri sağ tarafta da uyguluyoruz.
[8,12,22]
[8,12], [22]
[8], [12]
[8,12], [22]
[8,12,22]
Sağ ve sol arrayleri birlikte işleme sokuyoruz.
[11,16,21], [8,12,22]
[8,11,12,16,21,22] 


Big O notation: O(n*logn)