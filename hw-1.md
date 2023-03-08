# Production.Product tablosunu ekrana getirdik.

## `select * from Production.Product `

# Production.Product tablosunda bulunan SafetyStockLevel verisini 600 ve 1000 arasında getirdik.

## `select * from Production.Product where SafetyStockLevel >= 600 and SafetyStockLevel <=1000 `

# Production.Product tablosunda bulunan MakeFlag verisinin sıfıra eşit olanlarını getirdik.

## `select * from Production.Product where MakeFlag = 0 `

# Production.Product tablosunda bulunan Color verisini Black olarak getirdik.

## `select * from Production.Product where Color = 'Black' `

# Production.Product tablosunda bulunan ProductNumber verisinin içinde ki F harfi ile başlayanları getirdik.

## `select * from Production.Product where ProductNumber like 'F%' `

# Production.Product tablosunda yer alan Name verisi içerisinde a harfi bulunanları getirdik.

## `select * from Production.Product where Name like '%a%' `
