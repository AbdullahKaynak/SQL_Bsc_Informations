<h1 align="center">UPDATE(GÜNCELLEME)</h1>

<p style="text-align; font-size: 16px; font-weight: bold;">
     Burada tablodaki verilerden istediğimizi güncelleriz. Ama dikkatli ol where kısmında nereyi seçtiğpin çok önemli.
</p>

```sql
UPDATE Instructor
SET city = "Dhaka", country = "BD"
WHERE ins_id = 4;
```



### ⚠️ Önemli Not
SQL'de `UPDATE` ve `DELETE` işlemlerinden önce `WHERE` koşulunun doğruluğundan mutlaka emin olun. Yanlış bir koşul veya koşulun unutulması veri kaybına yol açabilir.