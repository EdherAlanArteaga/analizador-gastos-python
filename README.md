Analizador de Gastos Personales

Herramienta de análisis de gastos personales construida en Python puro,
sin librerías externas de análisis de datos.

Problema que resuelve
Muchas personas no saben en qué gastan su dinero ni qué categorías 
consumen más su presupuesto. Este programa lee un CSV de gastos y 
genera un reporte completo automáticamente.

Funcionalidades
- Carga y valida gastos desde archivo CSV
- Agregar nuevos gastos con validación de datos
- Reporte por categoría con porcentajes y barras visuales
- Reporte por mes
- Detección del gasto más alto y más bajo
- Cálculo de promedio por transacción

Tecnologías
- Python 3.10+
- Programación Orientada a Objetos (POO)
- Manejo de errores y validaciones
- Módulos: `csv`, `os`, `datetime`

Estructura del proyecto
analizador-gastos-python/
│
├── analizador_gastos.ipynb   # Notebook principal
├── gastos.csv                # Dataset de ejemplo
└── README.md

Cómo usarlo
1. Abre el notebook en Google Colab
2. Ejecuta todas las celdas en orden
3. Modifica `gastos.csv` con tus propios datos

Lo que aprendí
- Diseño de clases con responsabilidad única
- Herencia y encapsulación en Python
- Validación robusta de datos de entrada
- Lectura y escritura de archivos CSV sin Pandas
- Control de versiones con Git y GitHub

Autor
Edher Arteaga Marroquin 
