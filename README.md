# Segmentación de Personalidad de Clientes mediante K-Means

Este proyecto aplica técnicas de aprendizaje no supervisado para segmentar la base de clientes de una empresa líder en retail, basándose en sus perfiles demográficos y comportamientos de compra.

# Autor
Florencia Nebot
Elena Salomon
Martina Ibarra

# Contexto de Negocio

En un entorno minorista altamente competitivo, comprender la personalidad y el comportamiento del cliente es fundamental para mejorar la satisfacción y aumentar los ingresos. La empresa busca superar las estrategias genéricas y adoptar enfoques personalizados que permitan optimizar las campañas de marketing y fortalecer la lealtad a largo plazo.

# Objetivo

El objetivo principal es identificar segmentos de clientes distintos para:
- Desarrollar campañas de marketing personalizadas que aumenten las tasas de conversión.
- Crear estrategias de retención efectivas para grupos de alto valor.
- Optimizar la asignación de recursos, tales como la gestión de inventarios y estrategias de precios.

# Estructura de los Datos

El conjunto de datos incluye información histórica dividida en:

- Información del Cliente: Edad, educación, estado civil, ingresos, presencia de niños/adolescentes en el hogar y fecha de inscripción.
- Comportamiento de Gasto: Montos gastados en vinos, frutas, carnes, pescados, dulces y productos de lujo (oro) en los últimos 2 años.
- Interacción con Campañas: Respuesta a diversas campañas promocionales y uso de descuentos.
- Canales de Compra: Número de compras realizadas vía web, catálogo o directamente en tiendas.

# Metodología

El proyecto sigue un flujo de trabajo estándar de Ciencia de Datos:

1- Análisis Exploratorio de Datos (EDA): Limpieza de datos y visualización de distribuciones.
2- Preprocesamiento: Escalado de variables utilizando StandardScaler de Scikit-Learn.
3- Modelado: Aplicación del algoritmo K-Means Clustering.
4- Determinación del número óptimo de clusters mediante el Método del Codo (Elbow Method) y el Coeficiente de Silueta.
5- Perfilado de Segmentos: Análisis detallado de las características de cada grupo identificado.

# Tecnologías Utilizadas
- Python (pandas, numpy).
- Matplotlib y Seaborn para visualización.
- Scikit-Learn y Yellowbrick para modelado y validación de clusters.
