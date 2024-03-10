# API de Conversión de Unidades

Esta API proporciona endpoints para convertir diferentes tipos de unidades, como longitud, peso, temperatura, volumen y velocidad.

## Endpoints

-   Longitud:

    -   `/convert/length/{value}/{unit}`: Convierte entre metros y pies.

-   Peso:

    -   `/convert/weight/{value}/{unit}`: Convierte entre kilogramos y libras.

-   Temperatura:

    -   `/convert/temperature/{value}/{unit}`: Convierte entre Celsius y Fahrenheit.

-   Volumen:

    -   `/convert/volume/{value}/{unit}`: Convierte entre litros y galones americanos.

-   Velocidad:
    -   `/convert/speed/{value}/{unit}`: Convierte entre kilómetros por hora y millas por hora.

## Uso

Cada endpoint espera recibir un valor numérico y la unidad de origen como parte de la URL. Por ejemplo:

GET /convert/length/10/meters

Esto devolverá la conversión de 10 metros a pies en formato JSON.
