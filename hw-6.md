# HumanResources.Employee tablosu ile Person.Person tablosunda bulunan BusinessEntityID değerini birlikte görebilmek için LEFT JOIN sorgusu ile ekrana getirdik.

## `select * from HumanResources.Employee left join Person.Person on HumanResources.Employee.BusinessEntityID = Person.Person.BusinessEntityID`

# Sales.SalesOrderHeader tablosu ile Sales.Customer tablosunda bulunan TerritoryID değerini birlikte görebilmek için RIGHT JOIN sorgusu ile ekrana getirdik.

## `select * from Sales.SalesOrderHeader right join Sales.Customer on Sales.SalesOrderHeader.TerritoryID = Sales.Customer.TerritoryID`
