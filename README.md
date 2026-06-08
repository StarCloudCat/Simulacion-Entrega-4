# S30 - Módulo 4. Actividad didáctica 2
## Descripción General
Este script simula el flujo de vehículos en las salidas del centro comercial Supercentro durante una jornada de 8 horas. El sistema modela 3 cajeros independientes trabajando en paralelo. Los conductores tienen 4 perfiles diferentes (desde rápidos hasta muy lentos), lo que genera una mezcla de tiempos de servicio. El script ejecuta 100 réplicas de esta jornada y utiliza una semilla fija (2026) para que los resultados sean siempre los mismos en cada ejecución.

## Requisitos e Instalación
Para hacer funcionar el simulador, necesitas tener instalado Python 3.7 o superior. Además, requiere dos librerías del entorno científico de Python: NumPy (para las funciones matemáticas y aleatorias) y Matplotlib (para generar los gráficos). Puedes instalar ambas abriendo tu terminal y ejecutando el comando: pip install numpy matplotlib.

## Paso a Paso para la Ejecución
* Guardar el archivo: Coloca el script modulo_4_actividad_didactica_2.py en una carpeta de tu computadora.

* Abrir la terminal: Viaja desde la consola hasta la carpeta donde guardaste el archivo.

* Ejecutar el comando: Escribe python modulo_4_actividad_didactica_2.py y presiona Enter.

* Cerrar ventanas emergentes: El script mostrará tres gráficos en pantalla uno por uno; debes ir cerrando cada ventana para que el programa continúe y finalice correctamente.

## Resultados y Gráficos Generados
Al terminar, la consola mostrará un reporte con los tiempos promedio de espera y los cuellos de botella del sistema. Además, se guardarán automáticamente tres imágenes de alta calidad en tu carpeta:

* estado_estable.png: Muestra cómo se estabilizan los tiempos tras eliminar las primeras 15 réplicas de "calentamiento" (fase transitoria).

* antes_despues.png: Compara visualmente el comportamiento del Cajero 1 antes y después de limpiar los datos iniciales.

* validacion_modelo.png: Compara los resultados de la simulación con las fórmulas teóricas de colas (M/M/1 vs M/G/1), demostrando que el modelo simulado se ajusta con precisión a la realidad matemática de una cola M/G/1.
