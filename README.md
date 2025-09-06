Proyecto: Simulador de Energía Solar Fotovoltaica
Este proyecto es una herramienta de simulación en Python para el diseño y optimización de sistemas de energía solar fotovoltaica. Permite modelar la trayectoria del sol y estimar la producción de energía de un panel solar en cualquier lugar del mundo, basándose en parámetros de entrada como la ubicación, la fecha y la orientación del panel.

Descripción del Programa
El script (nombre_del_archivo.py) calcula la posición del sol (ángulo de altitud y acimut) a lo largo de un día específico. Luego, utiliza un modelo simplificado de irradiancia solar para estimar la cantidad de luz que incide sobre un panel, considerando su inclinación y orientación. Finalmente, calcula la potencia y la energía que el panel puede generar, presentando los resultados en forma de tablas y gráficos.

Instrucciones de Uso
Sigue estos pasos para ejecutar el programa en tu entorno local.

1. Requisitos del Sistema
Asegúrate de tener Python 3.x instalado en tu sistema.

2. Instalación de Dependencias
El script utiliza las siguientes librerías de Python,( numpy, pandas ,matplotlib)  debes instalarlas 

3. Ejecución del Programa
Guarda el código, abre la terminal, y ejecuta el codigo

4. Interacción con el Programa
Una vez que ejecutes el script, la consola te pedirá que ingreses varios parámetros para la simulación:

Latitud y Longitud: Las coordenadas de la ubicación de tu interés.

Fecha (YYYY-MM-DD): El día para el cual deseas realizar la simulación.

Zona Horaria: La diferencia horaria en horas respecto a UTC (por ejemplo, -5 para Colombia).

Ángulo de Inclinación del Panel: El ángulo del panel respecto al suelo (0° es horizontal, 90° es vertical).

Orientación del Panel: El acimut del panel (0° para el Norte, 180° para el Sur, etc.).

Área del Panel: El área total del panel en metros cuadrados.

Eficiencia del Panel: La eficiencia de conversión del panel (por ejemplo, 0.20 para 20%).

Después de ingresar todos los datos, el programa imprimirá una tabla de resultados en la terminal y generará dos gráficos: uno que muestra la posición del sol a lo largo del día y otro que muestra la potencia generada por el panel.

Autor
Andrés David Palomeque Ruiz 
