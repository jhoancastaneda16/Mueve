# Chiper-Growth
Assesment excel by team growth

Repositorios archivos (www.shorturl.at/uyzS0)

Nuestro reto se enmarca en el contexto del comercio electrónico o del marketing online. Normalmente, cuando se vende algo en Internet, el usuario/cliente llega varias veces (por ejemplo, visitas) al sitio, a menudo también a través de diferentes canales (por ejemplo, correo electrónico, Facebook, Google, etc.), antes de comprar algo (una conversión o transacción).

***DATASETS***

***table_A_conversions.csv:***

Ejemplo de lista de conversiones/ ventas/ transacciones
 * Conv_ID - transaction ID
 * Conv_Date - transaction date
 * Revenue - value of transaction
 * User_ID - an ID of a customer

***table_B_attribution.csv:***

Lista de resultados de atribución para las conversiones

 * Conv_ID - transaction ID (link to table A)
 * Channel - marketing channel
 * IHC_Conv - attributed conversion fraction by the IHC model

Tenga en cuenta que la fracción de conversión atribuida (IHC_Conv), es decir, la fracción de la conversión dada que se atribuye a un determinado canal, suma 1,0 para cada conversión.

***table_C_coupons.csv:***

 * Store ID - Identificador del cliente
 * Store Allocation - Segmento objetivo del cupon
 * Order Created At Date - Fecha de creación de la orden de compra
 * Sales Coupon Code - Nombre del cupon
 * Sales City - Ciudad
 * Sales Net - Neto de venta
 * Discounted Value - Descuento otorgado por el cupon
 
***DESARROLLO***

Obviamente, queremos que analices los datos y nos muestres lo que puedes aprender de ellos.
Pero también queremos que visualices tus hallazgos, que intentes sacar conclusiones "útiles" y que los presentes en un bonito PDF.

Algunas pistas, lista (no exhaustiva) de puntos que podría considerar en su análisis:

Para los archivos table_A_conversions & table_B_attribution, los cuales se cruzan por el campo Conv_ID, esperamos:

 * Rendimiento e impacto de los diferentes canales y cómo cambia a lo largo del tiempo
 * Canales más influyentes para cada usuario
 * Segmentación de usuarios utilizando "Distribución normal" (Construcción campana de gauss en excel)
 * ¿Vemos una evolución en los clientes?
 * Algunas segmentaciones de clientes, identificar los clientes inactivos.
 * Diseñar una campaña para los clientes que tengan una inactividad mayor a 30 días con respecto al max(Conv_Date) del dataset table_A_conversions

Para el archivo table_C_coupons esperamos (PRIORIDAD) :

 * Visión general a lo largo del período 
 * Evaluación de los siguientes KPI 
    * Conversión
    * Inversión
    * Cantidad de ordenes 
    * AOV

***ENTREGABLES***

 * Archivo en Excel o link de googleSheets, con las formulas utilizadas aún visibles (No copiar valores) 
 * Si es posible, algunos gráficos con explicaciones
 * PDF (¡máximo 3-4 páginas!) con una breve explicación de los pasos dados y el resumen de los resultados

***Buena suerte y estamos deseando ver sus soluciones.***

Nota: No esperamos que construya la solución o informe aquí.

Nuestro objetivo es:

 * Ver cómo se aborda un problema de este tipo
 * Obtener una idea de sus habilidades manejando información y su capacidad analitica.
 * Poner a prueba tu pensamiento racional en un caso de problema de este tipo.
 * Ver cómo puedes resumir y presentar los resultados.

***TEAM GROWTH***

Question? please contact whatsapp +57 315 611 75 59

References: https://github.com/chiper-inc/bi-challenge

Thanks: https://github.com/kikeex

CHIPER TEAM

