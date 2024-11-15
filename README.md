# MINE-4101-Taller-2

## Autores
- **Daniel Felipe Vargas Ulloa**
- **Andrés Francisco Borda Rincón**

## Descripción del Proyecto
Este proyecto se desarrolla en el contexto de un supermercado inteligente, donde se busca implementar un sistema de automatización que permita a los clientes tomar productos y salir sin necesidad de pasar por caja, mientras que cámaras y sensores registran automáticamente los artículos seleccionados. Se utilizarán modelos de Machine Learning y técnicas de preparación de datos para identificar productos y generar valor al supermercado a partir de los datos recogidos.

## Contexto del Negocio
El concepto de supermercado inteligente está revolucionando la forma en que interactuamos con el retail, integrando inteligencia artificial, automatización y ciencia de datos para ofrecer una experiencia de compra más eficiente y personalizada. En este proyecto, el objetivo es aprovechar los datos generados diariamente para tomar decisiones más informadas, optimizar la gestión de inventarios y analizar el comportamiento de los clientes.

## Requisitos de Software
- **Git**: Para clonar el repositorio del proyecto.
- **Python**: Se recomienda la versión 3.12 para garantizar la compatibilidad de las librerías.

## Librerías de Python
Todas las librerías necesarias están listadas en el archivo `requirements.txt`, que incluye:
- `pandas`
- `numpy<2.0.0`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `imgaug`

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
Este proyecto fue desarrollado por Daniel Felipe Vargas Ulloa y Andrés Francisco Borda Rincón para el curso MINE-4101.
