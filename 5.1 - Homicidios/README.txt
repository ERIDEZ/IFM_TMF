
			*** TASA DE HOMICIDIOS POR CADA 100,000 HABITANTES POR PAÍS Y AÑO (Naciones Unidas y Otros) ***

|||| Dataset "data_cts_intentional_homicide" (Naciones Unidas) ||||

> Filtrar "Victims of intentional homicide" en Indicator 
> Filtrar "Rate per 100,000 population" en "Unit of measurement"
> Filtrar "Total" en el resto de variables
> Link: https://dataunodc.un.org/dp-intentional-homicide-victims
> Datos faltantes:
		 * Bolivia, Venezuela y Portugal se completan con dataset "homicidios_adicionales".
		 * En "homicidios_adicionales" también se agregan datos para China, Senegal y Ukrania.
		 * China: Falta 2022, completar con la media entre 2020 y 2021.
		 * Cuba: Falta 2020 a 2022, completar media de años subyacentes pues no se observa gran variación en los años.
		 * Peru: Falta 2008 a 2010 y 2022. Usar media de años cercanos o usar otra opción como "MissForest".
		 * Rusia: Falta 2022, completar con la media entre 2020 y 2021 ya que no hay mucha variación en los años.
		 * Senegal: Falta todo menos 2015. Evaluar si ese país es verdaderamente relevante cuando hagamos EDA más detallado.
		 * Ukrania: Falta 2011, 2013, 2015, 2016 y 2022. Evaluar completar con la media entre dos años subyacentes o usar otra opcion como "Missforest"		

  * NOTA: evaluar el uso de "Missforest" para completar algunos de datos nulos mediante un arbol de desicion *



|||| Dataset "homicidios_adicionales" (elaboración propia con diversas fuentes) ||||

> Se completan los datos faltantes de Bolivia, Portugal y Venezuela
> Se añaden algunos datos adicionales de China (2021), Senegal (2015) y Ukrania (2022)
> Links:
	*https://datosmacro.expansion.com/demografia/homicidios/bolivia
	*https://www.statista.com/statistics/1268504/homicide-rate-europe-country/
	*https://countryeconomy.com/demography/homicides/portugal?year=2008
	*https://www.observatoriodeconflictos.org.ve/derechos-humanos/informe-2013-del-observatorio-venezolano-de-violencia#:~:text=Al%20finalizar%202013%2C%20cerraremos%20el,por%20cada%20cien%20mil%20habitantes.
	*https://datosmacro.expansion.com/demografia/homicidios/venezuela