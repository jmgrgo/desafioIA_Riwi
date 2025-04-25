# desafioIA_Riwi
Entrega 1 - IA for developers.

1-. Introducción: 

A continuación se detallará el cómo el uso de Inteligencia Artifical puede beneficiar enormemente al proceso de entrega de productos a domicilio, dada la creciente demanda de este servicio debido al auge de internet, la globalización, y el surgimiento de plataformas como Amazon o Mercadolibre.


2-. Descripción del Proceso Tradicional

Normalmente, cálculo de ruta se hace en base a estimaciones en mapas planos, donde lo más probable es que se evalúe únicamente las diferentes distancias para los domicilios de entrega.

Este proceso de asignación destaca dos principales problemas:

- Se hace tedioso, pues no solo es cuestión de calcular una ruta, también se deben tener cuenta las propiedades únicas de cada producto, cuando este debe ser entregado, si debe ser transportado con una seguridad adicional, si tiene prioridad por sobre otros productos por alguna razón en particular, etc.

- Supone una dependencia directa entre quien realiza las entregas y quien calcula la ruta, dando lugar a una gran variedad de situaciones que pueden perjudicar la correcta ejecución de la tarea, además, si se dael caso de que quien realiza las entregas es la misma persona encargada de calcular la ruta, esto supone una carga de trabajo adicional.


3-. Propuesta de Solución con IA

Se implementará el uso de IA para el cálculo de rutas según las especificaciones de cada producto.

- Sistema para calcular inventario y ruta.
    - Se hace un diagnóstico de los productos en bodega para entregar, evaluando su lugar de destino, fecha de entrega, etc.
    - Los productos se identifican y se dividen en diferentes rutas.
    - Se calcula la ruta más óptima para la entrega de todos los productos.
    - Si se manifiesta algún inconveniente con la ruta ingresada, se calcula una nueva ruta.
    - Se utilizan los datos de entrega para usarlos como referencia en futuras operaciones.

¿Que beneficios se esperan de esta implementación?
    - Gestión de carga automática para cada camión.
    - Cálculo de ruta eficiente.
    - Ofrecer rutas alternativas en caso exista algún inconveniente repentino.
    - Estimar tiempos de llegada de cada paquete específico.


4-. Comparativa entre procesos.

| Aspecto                    | Proceso Tradicional              | Solución con IA                         |
|----------------------------|----------------------------------|-----------------------------------------|
| Gestión de carga           | Manual, posibles errores.        | Automático, eficiente.                  |
| Costo operativo            | Alto                             | Bajo, eficiente                         |
| Cálculo de ruta            | Variable                         | Instantáneo.                            |
| Adaptabilidad              | Limitada, casi nula.             | Avanzada, en tiempo real.               |

5-. Reflexión

La IA supone la mayor revolución de la tecnología desde la invención de internet, es una herramienta poderosa que hace el no uso de esta algo completamente inviable. En este ejercicio se aprecia el cómo su implementación puede dar un gran salto en cualquier proceso dentro de una empresa, pues nos evita incluir pasos adicionales que puedan alentar aún más el proceso, además de permitir ahorrar mano de obra en otras tareas, algunas de las cuales pueden llegar a ser bastante tediosas, suponiendo así otra serie de inconvenientes tanto para quien las realiza como para la empresa que debe velar por su realización.

