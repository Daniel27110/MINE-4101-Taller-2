# MINE-4101-Taller-2

## Autores
- **Daniel Felipe Vargas Ulloa**
- **Andrés Francisco Borda Rincón**

## Descripción del Proyecto
Este proyecto se desarrolla en el contexto de un supermercado inteligente, donde se busca implementar un sistema de automatización que permita a los clientes tomar productos y salir sin necesidad de pasar por caja, mientras que cámaras y sensores registran automáticamente los artículos seleccionados. Se utilizarán modelos de Machine Learning y técnicas de preparación de datos para identificar productos y generar valor al supermercado a partir de la utilización de modelos.

## Contexto del Negocio
El concepto de supermercado inteligente está revolucionando la forma en que interactuamos con el retail, integrando inteligencia artificial, automatización y ciencia de datos para ofrecer una experiencia de compra más eficiente y personalizada. En este proyecto, el objetivo es aprovechar los datos generados diariamente para tomar decisiones más informadas, optimizar la gestión de inventarios y apoyar diferentes procesos de este tipo de supermercados inteligentes.

## Entregables

El proyecto cuenta con una carpeta denominada **`Entregables`**, en la cual se encuentran organizadas las cinco secciones del entregable del taller. Cada sección corresponde a una etapa clave del proyecto, organizada de la siguiente manera:

1. **Entendimiento y preparación de los datos**  
   Incluye notebooks y documentos relacionados con la exploración inicial, limpieza y preparación del dataset.

2. **Entrenamiento del modelo de Machine Learning**  
   Contiene el código y los cálculos necesarios para construir y entrenar el modelo.

3. **Análisis de resultados del modelo**  
   En esta sección se presentan los notebooks y reportes que evalúan el rendimiento del modelo y sus resultados.

4. **Generación de valor**  
   Reporte y calculos de cómo los resultados del modelo pueden ser aplicados para optimizar las operaciones del supermercado inteligente.

5. **Insights**  
   Proporciona un resumen de los hallazgos clave y recomendaciones obtenidas a lo largo del proyecto.

Cada una de estas carpetas contiene tanto los notebooks con el código correspondiente a cada etapa como reportes y cálculos complementarios. Esta estructura fue diseñada para facilitar la comprensión de qué entregable corresponde a cada parte del taller. 

Se debe ejecutar cada etapa en el **orden listado**, ya que las fases están interrelacionadas y dependen del progreso secuencial para asegurar resultados consistentes, con la excepción de los notebooks de las sección 4, que corresponde a los cálculos y reportes de generación de valor.

## Fuentes de Datos

Para este proyecto, se utilizó el dataset público disponible en [GroceryStoreDataset](https://github.com/marcusklasson/GroceryStoreDataset), que contiene imágenes de productos de supermercado con etiquetas para su identificación. 

El conjunto de datos **no está incluido** directamente en el repositorio para mantener una estructura sencilla y ligera. Sin embargo, **no es necesario descargarlo manualmente**, ya que el dataset se descargará automáticamente al ejecutar el notebook correspondiente a la sección **Entendimiento y preparación de los datos**.

## Requisitos de Software
- **Git**: Para clonar el repositorio del proyecto.
- **Python**: Se recomienda la versión 3.12 para garantizar la compatibilidad de las librerías.

## Requisitos de Hardware
- **Procesador**: 2 núcleos o más.
- **Memoria RAM**: 16 GB o más (se recomienda 32 GB para un mejor rendimiento, especialmente en la etapa de entrenamiento del modelo).
- **Almacenamiento**: 2 GB de espacio libre en disco.

En caso de no cumplir con los requisitos de hardware, se recomienda utilizar servicios en la nube como Google Colab, que ofrece recursos computacionales gratuitos para ejecutar notebooks de Jupyter. Recuerde usar el mismo ambiente de ejecución, en el orden secuencial de las secciones, para garantizar la correcta ejecución del proyecto.

## Librerías de Python
Todas las librerías necesarias están listadas en el archivo `requirements.txt`, que incluye:
- `pandas`
- `numpy<2.0.0`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imgaug`
- `statsmodels`

Estas librerías se pueden instalar ejecutando el siguiente comando:
```bash
pip install -r requirements.txt
```

## Estructura del Proyecto
El proyecto tiene la siguiente estructura de carpetas y archivos:

```plaintext
MINE-4101-Taller-2/
├── docs/                  # Documentación adicional del proyecto
├── notebooks/             # Notebooks de Jupyter para el desarrollo del modelo
├── .gitignore             # Archivo para ignorar archivos y carpetas no deseados
├── README.md              # Descripción y guía del proyecto
└── requirements.txt       # Archivo con las dependencias de Python
```

## Guía de Instalación
1. Clona el repositorio del proyecto:
   ```bash
   git clone https://github.com/tu-usuario/MINE-4101-Taller-2.git
   ```
2. Entra en el directorio del proyecto:
   ```bash
   cd MINE-4101-Taller-2
   ```
3. Instala las dependencias de Python:
   ```bash
   pip install -r requirements.txt
   ```

## Importación de Datos y Librerías
La importación de datos y librerías necesarias se realiza dentro de los notebooks correspondientes, por lo que no es necesario preocuparse por ello al ejecutar el proyecto. Asegúrate de ejecutar los notebooks en el orden sugerido por el enunciado para una correcta implementación del sistema de identificación de productos.

## Uso del Proyecto
1. Asegúrate de tener las dependencias instaladas siguiendo la Guía de Instalación.
2. Ejecuta los notebooks en el orden indicado para completar el flujo de trabajo de análisis de datos y construcción del modelo de Machine Learning.
3. Los resultados generados ofrecerán recomendaciones y análisis del valor potencial de esta implementación para el supermercado inteligente.

## Contribuciones
Este proyecto fue desarrollado por Daniel Felipe Vargas Ulloa y Andrés Francisco Borda Rincón para el curso de Ciencia de Datos Aplicada de la Maestría en Ingeniería de Información (MINE).
