## <p style="text-align: center;">**Caso de Estudio N°3**</p>
_____________________________

Se entrega el siguiente set de datos de una empresa del sector retail, BigMartSales.csv, el cual es un dataset de ventas de 2013 para 1559 productos en 10 tiendas en diferentes ciudades. Además, se han definido ciertos atributos de cada producto y tienda. Debido a la  nueva  coyuntura  que  estamos  viviendo  COVID-19,  han  observado  que  algunos productos que normalmente tenían alta rotación se han estado quedando en el almacén generando un grave problema de sobre stock y quitándoles espacio para otros productos por ende le han encargado al área de analítica de la empresa poder ayudarlos con la manera óptima de realizar el inventario y pedidos a los proveedores pues tienen metas comerciales muy altas en el Q1-2021.



### Las variables que se disponibilizan son:

| Columna                   | Descripción                                               |
|---------------------------|-----------------------------------------------------------|
| Item_Identifier           | ID de producto único.                                    |
| Item_Weight               | Peso del producto.                                       |
| Item_Fat_Content          | ¿El producto es bajo en grasa o no?                       |
| Item_Visibility           | El % del área de visualización total asignado a un producto en una tienda particular. |
| Item_Type                 | La categoría a la que pertenece el producto.              |
| Item_MRP                  | Precio minorista máximo (precio de lista) del producto.   |
| Outlet_Identifier         | ID de tienda único.                                      |
| Outlet_Establishment_Year | El año en que se estableció la tienda.                    |
| Outlet_Size               | El tamaño de la tienda en términos de superficie cubierta.|
| Outlet_Location_Type      | El tipo de ciudad en la que se encuentra la tienda.       |
| Outlet_Type               | Si la tienda es solo una tienda de comestibles o algún tipo de supermercado. |



### Consignas:

1-  Definir  el  problema  de  la  naturaleza  que  se  tiene  a  continuación,  además  de  los objetivos de negocio bien definidos.

**Problema:** Sobre stock de productos a causa de la pandemia que modificaron los hábitos de consumo de los consumidores.

**Objetivos:** 
Poder optimizar el espacio del depósito.
Determinar compras a proveedores que sean acordes a los hábitos de consumo.

2- ¿Qué tipo de variables se utilizan en el problema de negocio?


*Item_Identifier:*
ID de producto único.
Variable categórica nominal.


*Item_Weight:*	
Peso del producto. 
Variable cuantitativa continua

*Item_Fat_Content:*	
El producto es bajo en grasa o no?.
Variable Categórica ordinal


*Item_Visibility:*
El% del área de visualización total de todos los productos en una tienda asignada a un producto en particular.
Variable cuantitativa continua


*Item_Type:*	
La categoría a la que pertenece el producto.
Variable Categórica nominal

*Item_MRP:*	
Precio minorista máximo (precio de lista) del producto.
Variable cuantitativa continua
 

*Outlet_Identifier:*	
ID de tienda única.
Variable categórica nominal.


*Outlet_Establishment_Ye:* El año en que se estableció la tienda.
Variable cuantitativa discreta

*Outlet_Size:*	
El tamaño de la tienda en términos de superficie cubierta 
Variable Categórica ordinal


*Outlet_Location_Type:*	
El tipo de ciudad en la que se encuentra la tienda.Si la tienda es solo una tienda de comestibles o algún tipo
Variable Categórica ordinal

*Outlet_Type:* de supermercado
Variable Categórica ordinal

Item_Outlet_Sales
Variable cuantitativa continua



3- ¿Cómo podríamos resolver este problema de negocio y cumplir con los objetivos planteados a través de la ciencia o analítica de datos?

No supervisado, cluster, según la rotación de las ventas por tienda.

