

	*** CONJUNTO DE MÉTRICAS POR PAÍS Y AÑO QUE MIDEN RIESGO/DESARROLLO DE UN PAÍS EN DIVERSAS ÁREAS ***


|||| Dataset "87f75e78-f12c-4ad6-9b99-d2b5adf9caa7_Data" (World Bank) ||||

> Las 2 variables de "Poverty" podrían removerse debido a la gran falta de información en algunos paises
> Datos nulos: *Los de Ukraine de 2022 podrían sacarse de la media de dos años anteriores. 
	       *Venezuela: Se encontraron los datos faltantes de PBI en datos del FMI y los de "Inflation, GDP deflator" en el dataset "Inflation-data" > hoja "def_a"
> Link: https://databank.worldbank.org/GDP---Inflation---Country-Risk/id/ae8fd58a#



|||| Dataset "Inflation-data" (World Bank) ||||

> Se extrae solo la hoja "fcpi_a" que es la inflacion anual de alimentos
> Debe transponerse debido a que los años están en formato de columna
> Link: https://www.worldbank.org/en/research/brief/inflation-database

*Extrater de la hoja "def_a" los datos faltantes de Venezuela para los años 2015-2022 de la variable "Inflation, GDP deflator (annual %)"



|||| Dataset "imf-dm-export-20240717" (International Monetary Fund) |||||

> Datos históricos de crecimiento real del PBI en Venezuela. 
> Transponer porque años están como columnas. 
> Extraer datos faltantes de Venezuela para los años 2015-2022
> Link: https://www.imf.org/external/datamapper/NGDP_RPCH@WEO/OEMDC/ADVEC/WEOWORLD/VEN