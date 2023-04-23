# HumanResources.Employee tablosu ile Person.Person tablosunda bulunan BusinessEntityID değerini birlikte görebilmek için INNER JOIN sorgusu ile ekrana getirdik.

## `select * from HumanResources.Employee inner join Person.Person on HumanResources.Employee.BusinessEntityID = Person.Person.BusinessEntityID `

# Sales.SalesOrderHeader tablosu ile Sales.Customer tablosunda bulunan TerritoryID değerinin eşleşenlerini görmek için INNER JOIN sorgusunu kullandık. Sorguyu gerçekleştirirken tabloların kısaltılmış hali ile gerçekleştirdik.

## `select * from Sales.SalesOrderHeader SOH inner join Sales.Customer SC on SOH.TerritoryID = SC.TerritoryID `






# Production.Product

## Production.Product
