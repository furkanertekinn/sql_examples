# Sales.SalesOrderDetail tablosunda UnitPrice verisinde 5.70 ve 714.7043 arasında ki ve CarrierTrackingNumber verisinin son harfi E olanları getirdik.

## `select * from Sales.SalesOrderDetail where UnitPrice between 5.70 and 714.7043 and CarrierTrackingNumber like '%E' `

# Person.Person tablosundan PersonType'ı EM olan ve isminin içerisinde c harfi bulunan ve EmailPromotion'ı 2 ye eşit olanları getirdik.

## `select * from Person.Person where PersonType = 'EM' and FirstName like '%c%' and EmailPromotion = 2 `

# Sales.SalesOrderHeader tablosundan TerritoryID verisini IN komutu ile koşullu olarak ekrana getirdik.

## `select * from Sales.SalesOrderHeader where TerritoryID in(1,2,3) `

# Person.Person tablosundan FirstName ve LastName verilerini ekrana getirdik.

## `select FirstName , LastName from Person.Person `

# Person.Person tablosundan FirstName ve LastName verilerini çekerek başlıklarını türkçeye çevirdik.

## `select FirstName Isim , LastName Soyisim from Person.Person `
