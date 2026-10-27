<h1 align="center">LIMIT(Sınırlama)</h1>

```sql
SELECT * FROM FilmLocations LIMIT 25;
```
burada ilk 25 tanesini alırız tablonun

```sql
SELECT * FROM tablo
LIMIT 15
OFFSET 10;
```
burada ise ilk 10 tanesini atla ve ondan sonraki 15 tanesi al (11-25'i al)

