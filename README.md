######
Programadores:

Fernando Nateras  
Rodrigo López Farías
######

# Implementación de una red neuronal profunda para la generación del mapa de idoneidad para la simulación de uso de suelo urbano con datos reales proporcionados por el IMPLAN Morelia.

La cubierta del suelo es la cobertura bio-física observada en la superficie de la tierra. El uso del suelo es un término utilizado para describir el uso de la tierra y representar las actividades económicas y culturales que se llevan a cabo en determinado lugar. El cambio de uso de suelo se puede definir como un proceso mediante el cual las actividades humanas transforman el paisaje natural, refiriéndose a cómo se ha utilizado la tierra, generalmente enfatizando el papel funcional de la tierra para las actividades económicas . El proceso de urbanización implica la aparición y crecimiento de las ciudades, hace referencia al cambio en el tamaño, densidad y heterogeneidad de estas. El panorama urbano se encuentra en constante cambio, como consecuencia del acelerado crecimiento de las ciudades. Uno de los factores que generalmente acompaña a este crecimiento es el aumento del número de habitantes, así como, la migración de personas de zonas rurales u otros asentamientos urbanos hacia estas urbes.

En este ejemplo se implementa una red neuronal profunda con datos procesados de los mapas de cobertura que compartió el IMPLAN Morelia. 



La libreta ```MODEL_COMP_NEW.ipynb''' implementa un modelo computacional capaz de modelar las características propias del espacio geográfico la Ciudad de Morelia. Con este proyecto se planea identificar y modelar las características que inducen al crecimiento o en dado caso a la transformación de las dimensiones de la mancha urbana a través del tiempo. El modelo propuesto será puesto a prueba para posteriormente generar  un mapa de idoneidad.  También se plantea la realización de una comparativa de desempeño con un modelo estadístico basado en regresión logística, ya que al ser distintas técnicas presentan diferencia en precisión espacio-temporal. Se pondrán a prueba los resultados obtenidos de ambos modelos con la finalidad de evaluar el desempeño de estos y observar cual se estos se apega más a la mancha urbana real de la ciudad de Morelia.

Se prueba la efectividad de este modelo comparándola a una regresión logística, la cual es utilizada en la generación de mapas de idoneidad. Se comparan los dos modelos utilizando una ROC, para verificar que modelo nos da la mejor respuesta dado un umbral de selección.

Para poder hacer funcionar el ejemplo es necesario descargar, descomprimir y colocar los .csv contenidos en ```mapas vectorizados uso de suelo del municipio de morelia.zip```  en la misma carpeta donde se encuentra la libreta ```MODEL_COMP_NEW.ipynb```:

La liga al .zip es: 
https://drive.google.com/open?id=1fFp29HoNrN8jMc-kim8C-Vwmz_BzDhup&authuser=rlopez%40centrogeo.edu.mx&usp=drive_fs

En caso de tener problemas con el link, favor de mandar un correo a rdglpz@gmail.com

-Rodrigo