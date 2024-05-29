# HenryP2

Siniestros Viales CABA - 


Se realizó un análisis sobre los siniestros viales ocurridos en la Ciudad Autónoma de Buenos Aires (CABA) con datos registrados desde el año 2016 hasta el año 2021.

Se tuvieron encuenta diferentes variables que fueron analizadas en profundidad en el EDA y quedan plasmadas en un Dashboard realizado en Power BI. 

EDA

La base de datos analizada contemplaba dos archivos: "hechos" y "victimas".
Estos archivos estaban relacionados mediante un ID en común, el cual registra el accidente con un identificador único.

El archivo correspondiente a "hechos" tenía información de la fecha del accidente, el número de víctimas, la comuna, la dirección del accidente, el detalle del tipo de calle, las coordenadas, la victima,  y el acusado.

Por otro lado, el archivo correspondiente a las "víctimas" contiene información de las víctimas como su edad, sexo, fecha de fallecimiento, y rol en el accidente.


Observaciones: 
>  El término de "VICTIMA" hace referencia a información de si era MOTO/PEATON/AUTO/BICICLETA/CARGAS/PASAJEROS/etc.

> El término de "ACUSADO" hace referencia a si el causante del siniestro era ACUSADO
AUTO/PASAJEROSCARGAS/MOTO/TREN etc.

> El término de "ROL" hace referencia a CONDUCTOR/PEATON/ACOMPAÑANTE/etc.

En el EDA se realizó un análisis profundo sobre las diferentes variables utilizando diferentes gráficos y evaluando correlaciones entre variables.



DASHBOARD

Se realizó un Dashboard en PowerBI, el cual contiene visualizaciones gráficas que explican los siniestros a lo largo del tiempo.

El mismo contiene los KPIs solicitados.

Para poder responder al KPI de la tasa de homicidios, se buscó información del INDEC que contiene la población de ARG. A estos datos, se le aplicó el porcentaje de población del país que vive en CABA, obtenido el mismo del Instituto Geográfico Nacional (IGN).
Se consideró que un 7,2% del total de la población Argentina se encuentra en Capital Federal.

Fuente Población Total ARG:	https://www.indec.gob.ar/indec/web/Nivel4-Tema-2-24-84
Fuente Población en CABA:	https://www.ign.gob.ar/NuestrasActividades/Geografia/DatosArgentina/Poblacion2



CONCLUSIONES
Se puede concluir que los accidentes en el último semestre de 2021 sí lograron el objetivo propuesto de reducir en un 10% respecto al semestre anterior. La tendencia de la cantidad de victimas en siniestros es decreciente, con lo cual pareciera ser que año a año mejora la situación.

La gran mayoría de las víctimas son motociclistas o peatones, lo que indica la importancia de tener precauciones especiales con este tipo de vehículos y cuidado especial para los peatones en la ciudad.

Las victimas son de sexo masculino en su gran mayoría. Esto podría deberse a varios factores que implican diferentes cuestiones como por ejemplo, el hecho de que haya mayor cantidad de varones en la población, o, el hecho de que haya mayor cantidad de conductores de sexo masculino. Estos serían puntos a revisar para continuar un análisis exhaustivo en el que se entienda por qué se da esta característica.

Es de vital importancia tener especial cuidado en las comunas con mayor cantidad de accidentes. Esto puede deberse a mayor tránsito en las zonas correspondientes, o a falta de señalización correcta en las calles por ejemplo. Es un punto clave tener en cuenta esto a la hora de realizar acciones que lleven a mejorar el tránsito en la ciudad y por ende, la calidad de vida de las personas. Las comunas 1,4,8,9 son las que tienen mayor volumen de hechos.

También es importante recalcar que la gran mayoría de los accidentes se dan en avenidas, con lo cual demuestra que es fundamental revisar este tipo de calles para evitar siniestros y lograr disminuir la cantidad de los mismos.



