![](landsat.jpg)
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

Analice los resultados
- Color Natural **B4,B3,B2**. En este caso se aprecia la superficie que combina tres bandas del espectro visible; rojo, verde y azul respectivamente.Se obtiene con ello una superficie tal como la percibe el ojo humano.
- Infrarrojo **B5,B4,B3**
- Agrícola **B6,B5,B2**
- Urbano **B7,B6,B4**
- Uso de suelo/cuerpos de agua **B5,B6,B4**

Describa sitios de cultivos, bosque, zonas urbana, pastizales, cuerpos de agua. 
Debe hacer un mínimo de 5 combinaciones de bandas

##### Conteste las siguientes preguntas
1	¿Cuáles son las ventajas de las características multiespectrales de los datos de teledetección digital?
	
2	¿Qué fecha tiene la imagen que corresponde a la que menor nubosidad?
	
3	¿Qué combinaciones espectrales de bandas y colores considera útil para comprender las características del paisaje de su interés?
	
	Compartir en este documento el link con el código que realizó.
