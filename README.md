# Proyecto - SQL
Este repositorio contiene el proyecto final del curso de SQL con SQL Server para obtener el diploma en Análisis de Datos.

## Muestra del código
```SQL Server 2014 Management Studio
SELECT c.CompanyName, SUM(soh.TotalDue) AS Total 
FROM SalesLT1.Customer AS c
LEFT JOIN SalesLT.SalesOrderHeader AS soh ON c.CustomerID = soh.CustomerID
GROUP BY c.CompanyName ORDER BY Total DESC
```

## Muestra del modelo Entidad Relación

<img align="left" alt="JPG" src="https://user-images.githubusercontent.com/98499583/151683875-3b6eb3c8-a7c8-4b6f-ba8f-f062d16f1deb.JPG" width="40%" height="auto" /> 
