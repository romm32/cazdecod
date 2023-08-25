# Recepción 

Cada grupo de estudiantes de secundaria recibió los siguientes materiales para el desarrollo del taller.

1. **Kit de dongle RTL-SDR.** Cada equipo recibió un kit para la recepción de las imágenes. El mismo consiste de varias antenas y conectores para las mismas, junto al dongle SDR. Este dispositivo permite obtener muestras de señales analógicas recibidas por una antena, con una conexión USB a cualquier computadora.

2. **Computadora portátil de Plan Ceibal[^1].** Se le entregó a cada equipo una laptop, algunas de ellas con sistema operativo Linux (Ubuntu 20.04) y otras con Windows (Windows 11). Cada computadora tenía descargada la aplicación SDR++ para el procesamiento de las muestras recibidas a través del dongle SDR. Esta aplicación permite seleccionar distintos esquemas de (de)modulación, y definir parámetros como la frecuencia central de recepción, la frecuencia de muestreo a utilizar y la ganancia en recepción. 

[^1] Plan Ceibal es un centro de investigación del estado uruguayo que busca desarrollar tecnologías para mejorar la educación de niños, niñas y adolescentes. Las computadoras utilizadas para la actividad fueron provistas por este centro.

### Aspectos a tener en cuenta para la recepción.
Se describen a continuación algunas consideraciones para la preparación de los equipos de recepción.

- SDR++ puede descargarse de forma sencilla de [su sitio web](https://www.sdrpp.org/), tanto en el caso de computadoras con sistema operativo Windows, como para computadoras con sistema operativo basado en Linux. Para mayor referencia, se puede consultar también el [repositorio asociado al proyecto SDR++](https://github.com/AlexandreRouma/SDRPlusPlus).

- En Linux, la instalación de las dependencias indicadas en el [repositorio asociado al proyecto SDR++](https://github.com/AlexandreRouma/SDRPlusPlus) debería ser suficiente para que el dongle SDR sea correctamente detectado por la aplicación. En Windows, se recomienda bajar la aplicación [Zadig](https://zadig.akeo.ie/) para facilitar la instalación de los drivers necesarios.
