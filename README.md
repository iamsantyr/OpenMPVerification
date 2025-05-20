# OpenMPVerification

Este repositorio contiene herramientas y ejemplos para verificar programas que utilizan OpenMP. El objetivo es proporcionar recursos que ayuden a los desarrolladores a asegurar la corrección de sus aplicaciones paralelas.

## Contenido

- **Ejemplos de código**: Programas que ilustran el uso correcto e incorrecto de directivas OpenMP.
- **Herramientas de verificación**: Scripts y utilidades para analizar y verificar el comportamiento de programas OpenMP.
- **Documentación**: Guías y referencias sobre prácticas recomendadas y técnicas de verificación.

## Uso

1. Clona el repositorio:
   git clone https://github.com/iamsantyr/OpenMPVerification.git
2. Navega al directorio del proyecto:
    cd OpenMPVerification
3. Compila y ejecuta los ejemplos según las instrucciones proporcionadas en cada subdirectorio.


## Conclusiones
La implementación con OpenMP permite paralelizar eficientemente la multiplicación de matrices mediante directivas clave como #pragma omp parallel (para crear el equipo de hilos) y #pragma omp for (para distribuir automáticamente las iteraciones del bucle entre los hilos disponibles). Estas directrices, junto con omp_set_num_threads(TH) para controlar el número de hilos, simplifican radicalmente la programación paralela al manejar automáticamente la creación, asignación de carga y sincronización de hilos.OpenMP se consolida así como la solución ideal para problemas de computación científica que requieren máximo rendimiento en CPUs multicore, siempre que se equilibre adecuadamente la escala del problema con los recursos disponibles.
