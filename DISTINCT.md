<h1 align="center">DISTINCT(tekrarı önleme)</h1>

<p style="text-align; font-size: 16px; font-weight: bold;">
    Kısacası burası bize tekrardan aynı değer olduğu zaman 1 tanesini saydırır. Yani tekrarı önler.
    
    dikkat et fazla yük bindirme!
</p>

```sql
SELECT DISTINCT title FROM film;
```
  - burada film tablosundaki başlıkları tekrarlamadan getirir    

```sql
SELECT COUNT(DISTINCT title) FROM film;
```
  - burada ise film tablosunun başlıklarının tekrarlama olmadna kaç tane olduğunu buluruz.

