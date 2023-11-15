# Mapa de ataques de tiburon por país: [Ir a mapa](https://carlossanchezarg.github.io/tiburones_atack/)
Distribución de ataques/accidentes causados por tiburones según los datos recopilados por el sitio:   https://www.sharkattackfile.net/  

El dataset en formato .xls que se obtiene de esta página tiene las siguientes características:

| Columna   |      Desc.  |
|----------|:-------------:|
| Case #  |  ID del ataque |
| Country  | Fecha en que ocurrió el ataque   |
| Area  | Provincia/Estado/Zona donde ocurrió el ataque |
|Location |Ciudad/localidad más cercana|
|Activity|Actividad que estaba haciendo la víctima|
|Name |Nombre de la víctima|
|Sex|Sexo de la víctima|
|Age| Edad de la víctima|
|Injury|Tipo de daños que sufrió la víctima|
|Time| Momento del día en que ocurrió el ataque|
|Species| Especie/s de tiburón involucrados|
|Investigator or Source| Investigador que reporto el ataque o fuente de donde se conocen los datos del ataque|

Los colores de las celdas son un código de colores que indica las siguientes características sobre el ataque:  
• Unprovoked Incidents = Tan
• Provoked Incidents = Orange
• Incidents Involving Watercrafts = Green
• Air / Sea Disasters = Yellow
• Questionable Incidents = Blue  

```
Esto repo recoge el trabajo realizado en la materia Calidad de Datos(FCEN-UBA) 2do bimestre 2023.
Tecnologias utilizadas: Python(Matplotlib, Pandas) y Folium para generar el mapa en una web.
```
