- Universidad de Costa Rica 
- GF-0618 FOTOGRAMETRÍA Y TELEDETECCIÓN
- MSc.María José Molina Montero
- Estudiante Steven Guillén Rivera
![](landsat.jpg)
> *Fue renombrado oficialmente a Landsat 8 el 30 de mayo de 2013. El satélite más nuevo de la serie Landsat ofrece a los científicos una visión más clara con una mejor resolución espacial que la mayoría de los instrumentos de detección oceánica y una mayor sensibilidad al brillo y al color que los Landsat anteriores. Lo más significativo es que puede observar la Tierra en longitudes de onda que permiten a los científicos ajustar las distorsiones especialmente causadas por la atmósfera cerca de la costa*

(Acharya y Yang, 2015, p.04)
## Objetivos
Familiarícese con los datos satelitales multiespectrales **Landsat 8**  

Examinar diferentes combinaciones de **colores y bandas espectrales** para comprender y extraer la tierra
### Instrucciones : Desarrolle un código en GEE que cumpla con las siguientes características
1.	Seleccione una ‘cuenca’ del shapefile de cuencas
2.	Filtre imágenes [Landsat 8 TOA](https://explorer.earthengine.google.com/#detail/LANDSAT%2FLC08%2FC01%2FT1_TOA), de tal manera que seleccione para el año 2019, la imagen con menor nubosidad
3.	Realice combinaciones de bandas usando las imágenes Landsat 8
#### Elección de cuenca 

![](Bebedero.png)

#### Combinación de bandas

[Código GEE](https://code.earthengine.google.com/e4d50d0954cac6e04bc3e50cef0b661e)

![](Natural.png)
![](Infra.png)
![](agri.png)
![](urb.png)
![](agua.png)

Analice los resultados
- Color Natural **B4,B3,B2**. En este caso se aprecia la superficie que combina tres bandas del espectro visible; rojo, verde y azul respectivamente.Se obtiene con ello una superficie tal como la percibe el ojo humano.
- Infrarrojo **B5,B4,B3**. Áreas de bosque con abundante vegetación poseen alta reflectancia con color rojo, en zonas con menor vegetación la intensidad del rojo disminuye e incluso llegando a ser nula.Se pueden distinguir cuerpos de agua en una tonalidad oscura.
- Agrícola **B6,B5,B2** Las zonas de agricultura reflejan un verde claro , se aprecian suelos descubiertos y un color amarillo para la vegetación.
- Urbano **B7,B6,B4** En este caso es fundamental identificar zonas de reflectancia con colores grises o morados en referencia a lo urbano.De igual forma permite apreciar cuerpos de agua.
- Uso de suelo/cuerpos de agua **B5,B6,B4** Se pueden distinguir fácilmente los cuerpos de agua con un azul oscuro, zonas con alta vegetación amarillo y suelos descubiertos preparados para la siembra.


##### Conteste las siguientes preguntas
1	¿Cuáles son las ventajas de las características multiespectrales de los datos de teledetección digital?

> 
*Estos sistemas tienen la capacidad de detectar y cuantificar las señales, por ejemplo, de reflectancia que se presenta en la superficie terrestre. Jensen (como se citó en Weng ,2012) señala que existirá un mayor éxito en la recopilación de datos cuando se contemplen a detalle aspectos como la resolución espacial, espectral, radiométrica y temporal.Los sensores satelitales poseen la ventaja de registrar y detectar una gama mucho más amplia de radiación electromagnética. Con base en la longitud de onda se puede determinar una clase de respuesta espectral de cada objeto en la superficie. Generando la posibilidad de distinguir cuerpos de agua, vegetación, uso de suelo, cobertura o materiales con respecto al rango del espectro electromagnético detectado. Un sistema de teledetección digital tiene gran flexibilidad ya que puede detectar radiación electromagnética en las regiones IR visible y cercana, o extenderse a las regiones IR media y térmica*
(Weng ,2012). Con lo anterior, un programa como Landsat 8 gracias a sus características multiespectrales tiene la capacidad de detectar cambios naturales o antrópicos en la superfiecie y dar un seguimiento a lo largo del tiempo.

2	¿Qué fecha tiene la imagen que corresponde a la que menor nubosidad?
> Se probaron los meses de enero-febrero del 2019, con ello se logra visualizar la zona de interés con muy poca nubosidad, la fecha específica es 2019-01-07 
 
3	¿Qué combinaciones espectrales de bandas y colores considera útil para comprender las características del paisaje de su interés?
> Esto dependerá de la cobertura que se desea analizar o darle mayor énfasis y así obtener mayor reflexión de los elementos, por ejemplo, en este caso la Cuenca Bebedero presenta zonas con gran cantidad de pastizales por su importancia en la actividad ganadera de la región, de igual manera sobresalen bandas para corroborar la cantidad de vegetación sana o suelo descubierto pues en la cuenca tambieén se realiza actividad agrícola. Las bandas para identificar lo urbano en este caso se deben de apreciar con gran detenimiento pues al tratarse de zonas mayormente rurales se dificulta un poco percibir los paisajes con mayor cantidad de infraestructura y densidad. Fundamental la combinación para apreciar los cuerpos de agua con mayor detalle tomando en cuenta que estas fuentes hídricas son determinantes en las dinámicas económicas, ambientales y sociales de la región. 
##### Referencias
Acharya, T. D., & Yang, I. (2015). Exploring landsat 8. International Journal of IT, Engineering and Applied Sciences Research (IJIEASR), 4(4), 4-10.
Weng, Q. (2012). *An introduction to contemporary remote sensing*. McGraw-Hill Education.

