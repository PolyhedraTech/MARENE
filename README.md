# MARENE
El proyecto MARENE ha contribuido al avance del conocimiento y aplicación de los sistemas de validación y de cuantificación de la incertidumbre inherente en las simulaciones energéticas de edificios. Se han creado curvas de distribución probabilística de los distintos parámetros analizados en función de la geometría y el clima en el que se sitúe el edificio. Esto permite analizar el comportamiento energético de los edificios (existentes, pero también de obra nueva), conociendo el grado de fiabilidad de los resultados que las herramientas de simulación arrojan, lo que ofrece una mayor información a los técnicos en la toma de decisiones sobre las medidas de proyecto o de rehabilitación a tomar.

Para seguir avanzando en este aspecto, la metodología MARENE puede aplicarse a otros parámetros no analizados, como los referentes al régimen de uso de los edificios. El proyecto ha contribuido a facilitar el análisis y caracterización del parque construido. La metodología de segmentación desarrollada, en la que las características geométricas de los edificios se definen como variables, permite trabajar con modelos que no representan un conjunto limitado de tipologías de edificios, sino que pueden representar cualquier edificio existente. Esto significa que, si bien este proyecto se focaliza en el ámbito español, sus resultados pueden ser aplicados directamente a otros contextos dentro del ámbito europeo e internacional.

Además, MARENE revoluciona la forma en que se realizan las simulaciones al integrar y automatizar el proceso directamente desde bases de datos. Esto no solo elimina tareas manuales propensas a errores, sino que democratiza el acceso a análisis complejos, haciéndolos más rápidos y escalables. Complementando esta automatización, se ha desarrollado una visualización gráfica de la metodología, que formaliza el conocimiento operativo y facilita la transferencia de conocimiento y la capacitación de nuevos usuarios.

Un pilar innovador de MARENE es la creación de una base de datos exhaustiva con distribuciones de probabilidad asociadas a diferentes soluciones constructivas, lo que permite cuantificar la incertidumbre en las predicciones. MARENE incorpora árboles de decisión que permiten a los técnicos identificar de forma sencilla y rápida las variables más relevantes y cuantificar la variabilidad final, transformando datos complejos en información útil para la toma de decisiones ágil y la gestión de riesgos. La mejora continua de esta base de datos asegura que sea un recurso vivo y cada vez más preciso.

La contribución de MARENE a la transición ecológica es muy relevante, ya que facilita herramientas de diagnóstico para la rehabilitación a gran escala del parque edificatorio. Esto puede contribuir a aumentar la resiliencia climática de los edificios, protegiendo la salud y el bienestar de los ocupantes frente a eventos extremos. Además, proporciona a las administraciones públicas herramientas esenciales para formular políticas verdes basadas en datos y gestionar eficientemente los fondos de sostenibilidad.

En el ámbito de la transición digital, MARENE impulsa la digitalización del sector de la construcción al promover la automatización de simulaciones y la toma de decisiones basada en datos. La aplicación NECADA es un ejemplo de cómo MARENE impulsa el desarrollo de nuevas plataformas y servicios digitales en la gestión energética de edificios.

Contenido del Repositorio
Histogramas: Gráficos que representan un histograma para cada combinación de factores analizados, facilitando la visualización de la distribución de probabilidad de las variables.
Tablas: Conjuntos de datos que contienen los valores obtenidos a partir de los análisis realizados, permitiendo un examen detallado de los resultados. El formato es el que se ha de utilizar para poder integrarse con el sistema de simulación implementado en NECADA.

MARENE/
│
├── Histogramas/
│   ├── histograma_combinacion_1.png
│   ├── histograma_combinacion_2.png
│   └── ...
│
└── Tablas/
    ├── tabla_resultados_1.csv
    ├── tabla_resultados_2.csv
    └── ...
