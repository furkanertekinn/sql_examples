# Production.Product tablosundan çektiğimiz Name bloğunun başlığını köşeli parantez kullanarak değiştirdik.

## `select Name [Isim Soyisim] from Production.Product `

# Sales.Customer tablosundan çektiğimiz CustomerID bloğunun ismini as komutu ile değiştirdik.

## `select CustomerID as MusteriNumarasi from Sales.Customer `

# Person.Person tablosunda 'count' fonksiyonunu kullanarak toplam kayıt sayısını ekrana getirdik.

## `select count(*) from Person.Person `

# Sales.SalesOrderHeader tablosunda SalesOrderID sütunundaki verilerin toplamını 'sum' fonksiyonu kullanarak görüntüledik.

## `select sum(SalesOrderID) from Sales.SalesOrderHeader `

# Production.Product tablosunda ReorderPoint sütunundaki verilerin ortalamasını 'avg' fonksiyonu kullanarak görüntüledik.

## `select avg(ReorderPoint) from Production.Product `

# Sales.Customer tablosunda TerritoryID sütunundaki verilerin en küçük değerini 'min' fonksiyonu kullanarak ekrana getirdik.

## `select min(TerritoryID) from Sales.Customer `

# Sales.Customer tablosunda StoreID sütunundaki verilerin en büyük değerini 'max' fonksiyonu kullanarak ekrana getirdik.

## `select max(StoreID) from Sales.Customer `
