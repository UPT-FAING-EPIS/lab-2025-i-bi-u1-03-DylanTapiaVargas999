[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/RF0fG4Wt)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19285469)
# SESION DE LABORATORIO N° 03: Visualización de Datos con PowerBI

### Nombre:

## OBJETIVOS
  * Comprender la organización la información de nuestros datos de tal manera que todos los que los vean 
puedan comprender sus implicaciones y cómo actuar sobre ellos con claridad.

## REQUERIMIENTOS
  * Conocimientos: 
    - Conocimientos básicos de cualquier IDE.
  * Hardware:
    - Virtualization activada en el BIOS.
    - CPU SLAT-capable feature.
    - Al menos 4GB de RAM.
  * Software:
    - Docker Desktop 
    - PowerBI 2023 o superior
## CONSIDERACIONES INICIALES
  * Clonar el repositorio mediante git para tener los recursos necesarios.
  * Restauar la base de datos como AdventureWorksLT
  * Colocar su nombre en el archivo
  * Guardar el archivo de trabajo con el nombre lab03.pbix
    
## DESARROLLO

Ejercicio 1: Conectando a Power BI a datos
Tarea 1: Conectar a datos existentes
1. Abrir SQL Server Management Studio, y conectar a la instancia de base de datos (local) utilizando 
autenticación de Windows.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/f8bbd1e7-9a76-4234-96a7-3f5588ccc8b3)
2. En el menú Archivo (File), en el submenu Abrir (Open), hacer click en Project/Solution, y buscar el archivo Project.ssmssln
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/40e7c0b5-a747-419b-b898-8ce80c118c6b)

3. En el Explorador de Soluciones, expandir Consultas (Queries), y luego hacer doble click en el archivo Lab Exercise 1.sql.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/d7f174f1-808b-4cdf-8115-ffa0d2210789)
4. Abrir Power BI Desktop.
5. En la ventana Power BI Desktop, hacer click en Obtener Data (Get Data).
6. En el cuadro Obtener Datos, click base de datos Microsoft SQL, y entonces click en Conectar
7. En la ventana base de datos Server database, En Servidor, escribir (local).
8. En Base de Datos (opcional), tipear AdventureWorksLT.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/dd93372c-0388-493c-ba4f-9a2610c76225)
9. Expandir el cuadro Opciones Avanzadas. Copiar el script Task 1 del archivo Lab Exercise 1.sql. y pegar la consulta en Power BI, en el cuadro sentencia SQL. Luego presionar OK.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/23156e30-2a08-4faf-aed4-273ee0317975)
10. En la ventana de vista preliminar click en Cargar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/16a293b4-96d7-4403-a950-375c29413f23)
11. En Power BI Desktop, click Obtener Datos y luego click en Mas.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/3fd53f9f-f9de-4feb-bbb7-446d2fb1fd3d)
12. Repetir los pasos del 6 al 10, utilizando el script Task 2.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c62e76d5-0333-44a3-9e9c-d5d48100fed4)
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/5c9ad8c1-cf1f-4c89-8a84-b58e353801ea)
13. De regreso en el reporte. Guardar el archivo como AdventureWorksLT Sales.pbix.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/f453f333-0b62-4d53-8f50-0ada9f121bed)

## Tarea 2: Graficar Datos
1. En el panel Campos (Fields), click derecho sobre Query1, Renombrar, tipear Customers y presionar Enter.
2. Para el Query2, hacer lo mismo del paso 1 y colocar el nombre Sales.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/099dcb50-17e4-472b-93f7-00fb6ca6e2b7)
3. Expandir ambas tablas para ver todas las filas.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/75f002bb-6bad-45e4-b900-d8c0a55cb11a) ![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/10422248-56da-4aa4-bdb5-b6ed55dfbd6f)
4. En la barra de navegación, click Datos (Data).
5. In the Fields pane, click the Customers table, if it is not already selected.
6. Right-click the NameStyle column, and click Delete.
7. In the Delete Column dialog box, click Delete.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/e68180bb-01fc-487d-b2f7-0708f75421c4)
8. Repetir el paso 6 y 7 para la columna SalesPerson.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/e721c962-be16-4076-bfed-bad6b643a8d3)
9. Right-click the CustomerID column, and then click Hide in Report View.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/380905dd-8680-4838-bf41-b2a4633c282d)
10. Click the AddressLine1 column header.
11. On the Modeling ribbon, in the Properties group, click Data Category: Uncategorized, and then click Address.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/8255564e-3ed9-4fad-a363-9b7a995ae5bf)
12. Click the City column header.
13. On the Modeling ribbon, in the Properties group, click Data Category: Uncategorized, and then click City.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/b1e54c80-1505-478d-b714-a012318c26a9)
14. Click the StateProvince column header.
15. On the Modeling ribbon, in the Properties group, click Data Category: Uncategorized, and then click State or Province.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c4f979b8-ac49-4b7d-8221-835b965906f2)
16. Click en el encabezado de columna CountryRegion.
17. On the Modeling ribbon, in the Properties group, click Data Category: Uncategorized, and then click Country/Region.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/bfb85517-2877-4915-b84c-2a27353a12ff)
18. Click en el encabezado de columna PostalCode.
19. On the Modeling ribbon, in the Properties group, click Data Category: Uncategorized, and then click Postal Code.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/b8ecd68b-1534-46f5-9eff-4d91653cbb7b)
20. On the Modeling ribbon, in the Calculations group, click New Column, and then in the formula bar, type the 
following expression and press Enter:
FullAddress = Customers[AddressLine1] & ", " & Customers[City] & ", " &
Customers[StateProvince] & ", " & Customers[CountryRegion] & ", " &
Customers[PostalCode]
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/f54ee14a-2e64-4329-a00f-0b597c651ea8)
21. In the Fields pane, click Sales.
22. Right-click the RevisionNumber column, and click Delete.
23. In the Delete Column dialog box, click Delete.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/db9dea58-5ac1-4518-81b6-50e5903fe15b)
24. Realizar el paso 23 y 24 para la columna SalesOrderNumber.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/6573311c-3a24-4671-8fb6-2c5f98412203)
25. Right-click the CustomerID column, and then click Hide in Report View.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/d323960b-e469-4a85-9145-388af7802e8c)
26. Realizar el paso 25 para las columnas SalesOrderID y SalesOrderDetailID.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/3b45884a-32cf-490a-8ba8-88ce704c5465)
27. On the Modeling ribbon, in the Calculations group, click New Column, and then in the formula bar, type the following expression and press Enter:
LineTotal = Sales[OrderQty] * Sales[ListPrice]
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/bb9de6ef-d554-41a1-ba70-127e71969776)
28. Click the LineTotal column header.
29. On the Modeling ribbon, in the Formatting group, click Format: General, point to Currency, and then click $ English (United States).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/7d9e218b-9d87-4e0c-a41d-d60efb016504)
30. On the Modeling ribbon, in the Calculations group, click New Measure, and then in the formula bar, type the following expression and press Enter.
TargetSales = SUM('Sales'[LineTotal]) * 1.2
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/35cb4542-41b3-4a2b-ae48-0402d2bb1c90)
31. Click Save, and then leave Power BI Desktop open for the next task.
    
### Tarea 3: Combinar Data
1.	En el Explorador de archivos, y luego abre el archivo States.xlsx.
2.	En la hoja de cálculo States, selecciona todos los valores de las dos columnas y luego presiona Ctrl+C.
3.	En Power BI Desktop, en la pestaña Inicio, haz clic en Introducir datos.
4.	En el cuadro de diálogo Crear tabla, haz clic en la tabla y luego presiona Ctrl+V. Power BI detecta que la primera fila es un encabezado de columna.
5.	En el cuadro Nombre, escribe Ventas por Estado y luego haz clic en Cargar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/83d13329-a92a-4635-b7bb-93907910756a)
6.	En la pestaña Inicio, haz clic en Obtener datos y luego en Web.
7.	En el cuadro de diálogo Desde la web, en el cuadro de URL, escribe http://en.wikipedia.org/wiki/List_of_U.S._state_abbreviations y luego haz clic en Aceptar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/36570212-3bf1-4590-add2-b7b914b00f85)
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/91027607-4ac3-4358-8a77-9e1391e967ac)
8.	En el cuadro de diálogo Navegador, selecciona Códigos y abreviaturas para estados, territorios y otras regiones de EE. UU., y luego haz clic en Cargar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/2ea346e5-cb5b-4ec7-bb3e-81469742f5a5)
9.	En el panel Campos, haz clic en Códigos y abreviaturas para estados, territorios y otras regiones para mostrar los datos. La tabla tiene 26 filas en la parte inferior que no son necesarias.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c562ad3c-1dc2-494e-9a13-c8db34504804)
10.	En la pestaña Inicio, en el grupo Datos externos, haz clic en Editar consultas y luego en Editar consultas.
11.	En el Editor de consultas, en el panel Consultas, haz clic en Códigos y abreviaturas para estados, territorios y otras regiones.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/6c0365d5-edc0-4289-a977-36a94d9784b7)
12.	En la pestaña Inicio, haz clic en Reducir filas, clic en Quitar filas y luego en Quitar filas inferiores.
13.	En el cuadro de diálogo Quitar filas inferiores, en el cuadro Número de filas, escribe 26 y luego haz clic en Aceptar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/65374a95-f781-4df9-9cb8-2cee26f3f03b)
14.	Haz clic en el encabezado de la columna ANSI2 y luego mantén presionada la tecla Ctrl mientras seleccionas todas las columnas hacia la derecha. Esto selecciona varias filas.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/6c2c4efb-8c44-4ac6-aeb2-b17fc2559d5e)

15.	Aún manteniendo presionado Ctrl, haz clic en las columnas Nombre y estado de la región2 y Encabezado para incluirlos en la selección.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/3504f143-fd34-41a0-98b7-d8ba04156fac)
16.	En la pestaña Inicio, haz clic en Administrar columnas, clic en Quitar columnas y luego en Quitar columnas.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/f37e2d07-382c-4b32-8258-656fe8f1e843)
17.	En el panel Configuración de la consulta, bajo Propiedades, en el cuadro Nombre, escribe Estados con códigos y luego presiona Enter.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/1fcf10b8-0dab-416c-aabe-bfc85999cb77)
18.	En la pestaña Inicio, en el grupo Transformar, haz clic en Usar primera fila como encabezados.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/56ead04f-4649-41d4-ad73-0e2eb57ca09d)
19.	Haz clic con el botón derecho en el encabezado de la columna Estados Unidos de América, haz clic en Renombrar, escribe Nombre del estado y luego presiona Enter.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/70c2cd87-6703-4324-89a3-d43599edaf93)
20.	Haz clic con el botón derecho en el encabezado de la columna US USA 840, haz clic en Renombrar, escribe Código de estado largo y luego presiona Enter.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/df252294-4acd-4324-8300-15b3952ffbdd)
21.	Haz clic con el botón derecho en el encabezado de la columna US, haz clic en Renombrar, escribe Código de estado corto y luego presiona Enter.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/42cc3c25-7836-42d3-8133-49e2dbdbe56a)
22.	En el panel Consultas, haz clic en Ventas por Estado.
23.	En la pestaña Inicio, haz clic en Combinar y luego en Combinar consultas.
24.	En el cuadro de diálogo Combinar, en la tabla Ventas por Estado, haz clic en la columna Estados.
25.	En la lista, haz clic en Estados con códigos, haz clic en la columna Nombre del estado y luego haz clic en Aceptar. Se agrega una nueva columna a la tabla que contiene la tabla Estados con códigos fusionada.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/cdd17a37-d821-48e0-b3d0-cf8d4e4fbe57)
26.	En el encabezado de la columna, haz clic en el icono de Expandir, desmarca (Seleccionar todas las columnas), selecciona Código de estado corto y luego haz clic en Aceptar. La columna ahora muestra solo los códigos de estado.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/2737a3de-1f12-48c5-9261-e5237b8e1cf0)![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/8e429f7f-25f1-47dd-aa56-c8ff3c27f1bb)
27.	Haz clic con el botón derecho en la columna, haz clic en Renombrar, escribe Código de estado y luego presiona Enter.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/71ab9412-eb60-4e3b-a198-2d311a9011d8)
28.	En el menú Archivo, haz clic en Cerrar y aplicar.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/4528481e-aa70-4e84-b6c7-95e9dffcf719)
29.	En el panel Campos, haz clic con el botón derecho en Estados con códigos y luego haz clic en Ocultar en la vista de informe.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/919eea86-c7de-4e17-821d-afb08884899f)
## Ejercicio 2: Construyendo Reportes en Power BI
## Tarea 1: Crear un Gráfico
1.	En Power BI Desktop, en la barra derecha de navegación, haz clic en Reporte (Report).
2.	En el panel de Visualizaciones (Visualizations), haz clic en Gauge.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/5bcdb276-7c82-42ce-a896-f28695f03359)
3.	Arrastra el campo LineTotal de la tabla Sales a la propiedad Valor (Value) del objeto gauge.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/586dcb19-e7c1-4979-9d7d-6c25831d246b)
4.	Arrastra la medida TargetSales de la tabla Sales a la propiedad Valor destino (Target value) del objeto gauge.
 ![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/ca6ed564-74dd-4eb3-982f-2a3eeebe25c5)
5.	Haz clic en Formato (Format), expande Eje del medidor (Gauge axis), y luego en el cuadro Max, escribe 146000. 
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/24774d26-9fe1-4437-a212-affa39ecbae5)
6.	Expande Título (Title), en el cuadro Texto de Título (Title Text), escribe Meta de Ventas (Target Sales), y luego haz clic en Centro (Center).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/01efecad-f7de-4e87-b5a0-0cd72ccf35c9)
7.	Haz clic en el lienzo del informe (report canvas), y luego arrastra el campo CompanyName de la tabla Customers al informe. Power BI crea automáticamente una tabla.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/ac8d6375-33f2-412e-a71b-5361f2386c92)
8.	Arrastra el campo LineTotal de la tabla Sales al informe.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/731d456f-914d-41ee-967a-402efd2ffb5d)
9.	Asegúrate de que la tabla esté seleccionada, y luego en el panel de Visualizaciones, haz clic en Gráfico circular (Pie chart).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/923a125f-9728-4593-8557-ff992d8644ed)
10.	Expande el gráfico para que todos los nombres de empresa sean visibles utilizando las manijas de redimensionamiento en el borde del gráfico.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c8d34ab8-a4e6-453d-87fc-745dbae3f7d4)
11.	Con el enfoque aún en el gráfico circular, haz clic en Formato (Format), y luego expande Título (Title).
12.	En el cuadro Texto del Título (Title Text), escribe Principales Clientes por Ventas, y luego haz clic en Centro (Center).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/665d9540-9ae6-4c4a-8171-afb895c8b71e)
13.	Arrastra el campo MainCategory de la tabla Sales al lienzo del informe. Power BI crea una tabla.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/145090e3-5716-4832-a32f-779d4d8e7767)
14.	Arrastra el campo OrderQty dentro de la tabla.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/2470329d-0948-4df0-89fb-06c90a68e4ba)
15.	En el panel de Visualizaciones, haz clic en Gráfico de barras apiladas (Stacked bar chart).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/4dbb13c5-0ceb-422f-a6a1-0e73ad85e33c)
16.	En el panel de Visualizaciones, haz clic en Campos (Fields).
17.	Arrastra el campo OrderQty a la propiedad Saturación de color (Color saturation). Nota que los colores cambian.
18.	En el panel de Visualizaciones, haz clic en Análisis (Analytics), expande Línea constante (Constant Line), y luego haz clic en Añadir (Add).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/50312c2f-9900-4d2e-89fe-270cd840501a)
19.	En el cuadro Valor (Value), escribe 500.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/fd99da9d-a716-491c-8420-1187b7bca83f)
20.	Cambia el Color a rojo, activa Etiqueta de datos (Data label), y luego cambia el color a rojo.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/ab4a4caf-5dbc-4078-8a36-b989682debfa)
21.	En el panel de Visualizaciones, haz clic en Formato (Format), y expande Título (Title).
22.	En el cuadro Texto de Título (Title Text), escribe Órdenes por Categoría Principal, y luego haz clic en Centro (Center).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c893b0f8-1f35-4f13-b96e-1efd91fdf929)
23.	Haz clic en el lienzo del informe para darle enfoque, y luego en el panel de Visualizaciones, haz clic en Gráfico de donut (Donut chart).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/8c13492a-ef44-4647-bb7c-4c9abda4e7b1)
24.	En la tabla Sales, selecciona MainCategory y LineTotal.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/fdca7162-6c1f-4a1a-aa77-012017ce8401)
25.	En el panel de Visualizaciones, haz clic en Formato (Format), y luego expande Título (Title).
26.	En el cuadro Texto de Título (Title Text), escribe Ventas por Categoría Principal, y luego haz clic en Centro (Center).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/85a7abee-1765-4ff3-8098-4fae9122e554)
27.	Arrastra el campo Product de la tabla Sales al lienzo del informe. Power BI crea una tabla.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/0c97c95d-e43f-4d08-a1b1-5237f91ded14)
28.	Arrastra el campo LineTotal de la tabla Sales al gráfico de la tabla de productos.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/962a824e-9c28-4a2d-a79a-3d88a734a185)
29.	En la tabla Sales, selecciona el campo MainCategory.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/1d7a25fe-93e0-4752-abe3-6be50a894569)
30.	En el panel de Visualizaciones, haz clic en Campos (Fields).
31.	En el panel de Filtros, expande LineTotal (All).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/e02b5674-0ae9-484d-b190-61dded893243)
32.	En la lista de valores Mostrar elementos cuando, selecciona es mayor que, y luego en el cuadro de abajo, escribe 32000.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/0a99049c-76ca-4ca0-b856-562c5e894510)
33.	Haz clic en Aplicar filtro (Apply filter).
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/89787a29-100a-4dd6-bdf7-e995b80c5c77)
34.	Expande MainCategory (All), y luego selecciona Bikes.


![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/de52307c-2496-4050-acb1-33a4543d9ec5)![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/a89632c9-8236-4369-ad9d-bfc9645bb530)

35.	En el panel de Visualizaciones, haz clic en Gráfico de columnas apiladas (Stacked column chart).


![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c7251881-4067-4484-aac5-6fe329f2abc4)
36.	En el panel de Visualizaciones, haz clic en Formato (Format), y luego expande Título (Title).
37.	En el cuadro Texto de Título (Title Text), escribe Top 10 Ventas de Bicicletas, y luego haz clic en Centro (Center).

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/7a4e1534-9651-4025-a3f1-6e2229b3ec12)
38.	En el panel de Visualizaciones, haz clic en Análisis (Analytics), expande Línea constante (Constant Line), y luego haz clic en Añadir (Add).
39.	En el cuadro Valor (Value), escribe 35000, y luego establece el Color en rojo.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/e5e549e0-56f1-487d-b8d2-c70596f3b218)
40.	Activa Etiqueta de datos (Data label), y luego establece el Color en rojo.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/86a53f7e-51dd-4bc4-ad77-66b09db89c77)

41.	Expande el gráfico para llenar el espacio restante en el lienzo del informe. Si es necesario, mueve tus visualizaciones para que encajen.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/5d566a80-569e-4b32-81de-c1bb113be596)
42.	Haz clic en Guardar (Save).

## Tarea 2: Crear una Visualización de Mapa
1.	En la parte inferior del informe, haz clic en el icono + para agregar una nueva página.	

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/024305f9-d969-431c-8dc6-cb83dc0d11bb)
2.	En el panel Campos (Fields), en la tabla Customers, selecciona el campo City. Power BI añade un mapa al informe.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/5592c70d-34a0-4eaa-bf0f-bd2ddbe39fad)

3.	En el panel Campos (Fields), en la tabla Sales, selecciona el campo LineTotal.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/41e3abeb-6dd4-4131-92e8-dc6d99ede406)

4.	Usando la herramienta de agarre en el lado derecho del gráfico, redimensiona el mapa para mostrar todas las burbujas.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/e8c13ed8-07a4-4c9e-86fa-9fea1e64036a)

5.	Observa que las burbujas tienen un tamaño proporcional para representar los datos.
6.	En el panel Visualizaciones (Visualizations), haz clic en Formato (Format), y luego expande Título (Title).
7.	En el cuadro Texto de Título (Title Text), escribe Ventas Mundiales por Ciudad, y luego haz clic en Centro (Center).

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/78e09433-1f6e-4be9-a2b8-273dbd196fc7)

8.	Haz clic en el lienzo del informe, y luego en la tabla Ventas por Estado, selecciona la columna State Code. Power BI añade automáticamente un mapa.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/9f39fd3a-6ad6-493d-b440-824cf2758779)

9.	En la tabla Ventas por Estado, selecciona la columna SalesYTD.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/0fd0bef9-46f6-40a4-acda-b999c49469b9)

10.	En el panel Visualizaciones (Visualizations), haz clic en Mapa Relleno (Filled Map). Usando la herramienta de agarre en el lado derecho y en la parte inferior del gráfico, redimensiona el mapa para mostrar todos los estados.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/318adb65-697c-4a2a-8bbf-e8e74f888ebb)

11.	Observa que las ventas se agrupan en una zona.
12.	Posiciona el cursor en California (CA) para ver la cifra de ventas. El valor no ha sido formateado como moneda.

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/cc3fc508-eb1e-482f-8626-0466b9bea9ec)
13.	En la tabla Ventas por Estado, haz clic en la columna SalesYTD.
14.	En la cinta de Modelado, selecciona Formato: General, haz clic en Moneda, y luego selecciona $ English (United States).

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/c3cdac94-9ef7-4f37-92ba-b60a5b6cd5b7)
15.	Posiciona el cursor en California (CA) en el mapa, y observa que el valor ha sido formateado.
![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/340adda4-bc74-43ef-a5c1-380902131548)
16.	En el panel Visualizaciones (Visualizations), haz clic en Formato (Format), y luego expande Título (Title).
17.	En el cuadro Texto de Título (Title Text), escribe Ventas por Estado, y luego haz clic en Centro (Center).

![image](https://github.com/UPT-FAING-EPIS/lab-2024-i-bi-u1-03-LuiguiNina/assets/142851384/0a4be1ca-4f51-4fd2-a36d-768e5b9322c0)

18.	Haz clic en Guardar (Save), y luego deja el informe abierto para el próximo ejercicio.

---
## Actividades
1. Crear la infraestructura para una base de datos Azure SQL utilizando Terraform, en la ruta infra/main.tf.
2. Construir una automatización en github actions (.github/workflows/bd.yml) que despliegue la infraestructura de base de datos utilizando Terraform y una herramienta para ejecutar la restauracion de la base de datos (Powershell, Liquibase u otro)
3. Conectar el dashboard con la base de datos, subir la captura de la conexion en el archivo conexion.png
4. Construir una automatizacion que despliegue el Dashboard de PowerBI en su espacio (.github/workflows/publish_dashboard.yml), puede utilizar un actión como este https://github.com/marketplace/actions/power-bi-pipeline-deploy o similar.
