<h1 align="center">INSERT(Yeni Satır Ekleme)</h1>

<p style="text-align; font-size: 16px; font-weight: bold;">
     veri tabanındaki bir tabloya yeni bir satır (yeni bir kayıt) eklemek için kullanılır.
</p>

- <p>
    <b>
        3 farklı INSERT yöntemi vardır. 
    </b>
</p>

<b>Yöntem 1:</b>

```sql
INSERT INTO tablo_adi (sutun1, sutun2, sutun3)
VALUES (deger1, deger2, deger3);
```


<b>Yöntem 2: Sütunları ezbere bilmelisin </b>

```sql
INSERT INTO Ogrenciler
VALUES ('Ayşe', 'Kaya', 22, 'Ankara');
```


<b>Yöntem 3: Çoklu kayıt ekleme</b>

```sql
INSERT INTO Ogrenciler (isim, soyisim, yas, sehir)
 VALUES 
('Can', 'Demir', 20, 'İstanbul'),
('Elif', 'Yıldız', 23, 'Bursa'),
('Mert', 'Aydın', 21, 'Antalya');
```