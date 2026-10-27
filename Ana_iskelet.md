<h1 align = "center">Burası Ana sütunlar</h1>

```sql
SELECT * FROM table
```
Burada table tablosunun bütün değerleri gelir.
  
```sql
SELECT table_sütun FROM table
```   
  table tablosu içerisindeki table_sütunları getir.

```sql
SELECT * FROM table WHERE yil >2000;
```
table tablosunun yil sütununun 2000 den büyük olan bütün değerlerini getir.

```sql
SELECT Title, Locations, ReleaseYear 
FROM FilmLocations 
WHERE Writer<>"James Cameron";
```
FilmLocations tablosundaki writeri james cameron olmayanların locations ve release year sütunlarını getir


