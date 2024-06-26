# Ciclo-P

Ciclo-P es una herramienta de predicción de viajes orientada al ciclismo urbano, basada en modelos de demanda de viajes ampliamente utilizados para la planificación de transporte. Permite simular los efectos de un cambio en la población, la superficie construída para distintos usos y las ciclovías en el número de viajes en bicicleta.

[sitio web](http://www.ciclo-p.cl)

## Estructura del proyecto Ciclo-P

El proyecto se estructura en base a repositorios especializados que cumplen un rol específico dentro del proyecto. Actualmente son los siguientes:

1. `frontend` El frontend de la aplicación.
2. `backend` El backend de simulación.
3. `paquete` El paquete ciclop con funciones utilizadas en el backend de simulación y los cuadernos.
4. `api` Los endpoint en la función lambda.
5. `web` La página de presentación (landing) de la aplicación.
6. `cuadernos` Cuadernos de jupyter notebook donde se realizan pruebas y hay ejemplos de la simulación.
7. `docs` La documentación del proyecto.
