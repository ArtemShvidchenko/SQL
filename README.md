# 1
1. Carsharing 
2. Авто сервис
3. Наша школа
4. Фаст фуд
5. Библиотека

# 2
SELECT 
	ProductName,
    Price
FROM Products
WHERE
	Price > 20

# 3
SELECT 
	(SupplierName,)
    Country
FROM [Suppliers]

# 4
SELECT 
	ProductName,
    Price,
    Price * .91 AS Price_down
FROM Products
WHERE
	NOT SupplierID='1'

# 5
SELECT 
	ContactName
FROM Customers
WHERE
	NOT Country='France'
    AND
    NOT Country='USA'
