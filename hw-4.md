# Production.Product tablosunda ProductID'si 3 olan satırın, Name'nin uzunluğunu ekrana getirdik.

## `select len(Name) from Production.Product where ProductID = 3 `

# Production.Product tablosunda SafetyStockLevel değerlerine göre gruplandırdık ve count sütununun başlığını adet olarak değiştirdik.

## `select SafetyStockLevel ,count(*) as adet from Production.Product group by SafetyStockLevel `
