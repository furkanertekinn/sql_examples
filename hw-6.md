# HumanResources.Employee tablosu ile Person.Person tablosunda bulunan BusinessEntityID değerini birlikte görebilmek için LEFT JOIN sorgusu ile ekrana getirdik.

## `select * from HumanResources.Employee left join Person.Person on HumanResources.Employee.BusinessEntityID = Person.Person.BusinessEntityID`

# HumanResources.Employee tablosu ile Person.Person tablosunda bulunan BusinessEntityID değerini birlikte görebilmek için RIGHT JOIN sorgusu ile ekrana getirdik.

## `select * from HumanResources.Employee right join Person.Person on HumanResources.Employee.BusinessEntityID = Person.Person.BusinessEntityID`
