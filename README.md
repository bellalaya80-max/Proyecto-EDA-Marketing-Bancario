# Proyecto-EDA-Marketing-Bancario
# 🏦 Análisis Exploratorio de Datos (EDA) sobre campañas de marketing bancario utilizando Python y Pandas.

## 📖 Descripción del Proyecto
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre las campañas de marketing telefónico de una institución bancaria. El objetivo principal es identificar qué factores demográficos, laborales y macroeconómicos influyen en que un cliente acepte un depósito a plazo fijo. Mediante la limpieza de datos y visualizaciones avanzadas, se busca aportar recomendaciones de negocio que optimicen el esfuerzo de los comerciales y aumenten la tasa de conversión.

Para resolver este problema, se aplicó un enfoque de análisis progresivo:
Limpieza y Curación: Integración de fuentes Excel/CSV y tratamiento estadístico de nulos.
Análisis Univariado: Exploración de distribuciones demográficas.
Análisis Bivariado y Multivariado: Identificación de correlaciones macroeconómicas y factores críticos de éxito operativo.

## 🗂️ Estructura del Proyecto
El proyecto está organizado de la siguiente manera para facilitar la reproducibilidad:

```text
├── Notebooks/         # Notebooks de Jupyter con el análisis detallado
├── data/              # Datos originales (en bruto) y transformados (limpios)
├── README.md          # Informe y descripción del proyecto
```

## 🛠️ Instalación y Requisitos
El análisis fue desarrollado utilizando Python 3.x. Para ejecutar el cuaderno correctamente, se requieren las siguientes bibliotecas de análisis y visualización:

- pandas
- numpy
- matplotlib
- seaborn
- openpyxl (para la carga de archivos Excel)
  
*Nota: Se recomienda ejecutar el proyecto utilizando un entorno como Jupyter Notebook o Visual Studio Code.*

## 📊 Resultados y Conclusiones
Tras realizar análisis univariados, bivariados y multivariados, los hallazgos más críticos para el negocio son:

- **La Regla de los 3 Minutos:** La duración de la llamada es el factor determinante. Los clientes que rechazan la oferta cuelgan rápidamente (mediana < 200s), mientras que las ventas exitosas requieren mantener la atención del cliente durante más tiempo (mediana ~ 450s).
- **Eficiencia por Segmento:** Aunque los perfiles "admin." y "blue-collar" concentran el volumen de llamadas, requieren un esfuerzo altísimo (>700 segundos por venta). Por el contrario, estudiantes y jubilados aceptan la oferta en casi la mitad de tiempo, representando nichos altamente rentables.
- **Impacto Macroeconómico:** Existe una fuerte correlación entre los indicadores externos (Euríbor a 3 meses y Tasa de Variación del Empleo). El éxito de la campaña fluctúa con el ciclo económico, demostrando que factores ajenos al comercial también dictan la dificultad de la venta.

## 🔄 Próximos Pasos
Para escalar este análisis y aportar aún más valor al banco, se proponen las siguientes fases:
- Desarrollar un modelo predictivo de Machine Learning para predecir la probabilidad de que un cliente diga "Sí" antes de realizar la llamada.
- Integrar datos de campañas de años anteriores para un análisis de series temporales.
- Realizar un análisis de sentimientos si se dispusiera de las transcripciones de las llamadas.

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el análisis, aplicar nuevos modelos o refinar las visualizaciones, por favor abre un *pull request* o una *issue* en este repositorio.

## ✒️ Autores y Agradecimientos
- **Bella Laya** - *Data Analyst* - [@bellalaya80-max](https://github.com/bellalaya80-max).
