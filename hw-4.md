# Production.Product tablosunda ProductID'si 3 olan satırın, Name'nin uzunluğunu ekrana getirdik.

## `select len(Name) from Production.Product where ProductID = 3 `

# Production.Product tablosunda SafetyStockLevel değerlerine göre gruplandırdık ve count sütununun başlığını adet olarak değiştirdik.

## `select SafetyStockLevel ,count(*) as adet from Production.Product group by SafetyStockLevel `

# Sales.Customer tablosunda TerritoryID değerlerini grup halinde getirdik ve count'larını miktar olarak adlandırdıktan sonra değerleri büyükten küçüğe doğru sıralayıp ekrana getirdik.

## `select TerritoryID, count(*) as miktar from Sales.Customer group by TerritoryID order by count(*) desc `

# HumanResources.Employee tablosunda OrganizationLevel sütunundaki 1'den büyük değerleri grup halinde ekrana getirip küçükten büyüğe doğru sıraladık.

## `select OrganizationLevel, count(*) from HumanResources.Employee where OrganizationLevel >1 group by OrganizationLevel order by count(*) asc `
