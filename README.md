📊 Customer Churn Prediction Project 🚀
📝 Descripción del Proyecto
Este proyecto aborda una de las problemáticas más críticas en el sector de servicios: el abandono de clientes (Churn). Utilizando un dataset de telecomunicaciones, desarrollé un modelo de Inteligencia Artificial capaz de predecir qué usuarios tienen mayor probabilidad de cancelar su suscripción, permitiendo a la empresa tomar acciones preventivas.

🛠️ Tecnologías y Herramientas Utilizadas
Para este desarrollo, utilicé un stack enfocado en Data Science y Machine Learning:

Python 🐍: Lenguaje principal para la lógica y manipulación de datos.

Pandas & NumPy 🔢: Fundamentales para la limpieza de datos, manejo de valores nulos y transformación de variables.

Matplotlib & Seaborn 📉: Utilizados para el Análisis Exploratorio de Datos (EDA) y visualización de patrones críticos.

Scikit-Learn 🤖: Biblioteca clave para el modelado de IA, incluyendo preprocesamiento (LabelEncoder) y algoritmos de clasificación.

Google Colab ☁️: Entorno de desarrollo basado en la nube para garantizar la reproducibilidad.

⚙️ Proceso de Ingeniería
1. Limpieza y Curación de Datos 🧹
Identifiqué que la columna TotalCharges tenía datos erróneos (strings vacíos). Implementé una conversión forzada a numérico y eliminé los valores nulos para asegurar la integridad del modelo.

2. Feature Engineering (Encoding) 🔄
Como los algoritmos de IA solo entienden números, transformé variables categóricas:

Label Encoding: Para variables binarias (Sí/No, Género).

One-Hot Encoding (Get Dummies): Para variables con múltiples categorías como el tipo de servicio de internet.

3. Entrenamiento del Modelo 🧠
Utilicé el algoritmo Random Forest Classifier. Elegí este modelo por su capacidad para manejar relaciones no lineales y su resistencia al sobreajuste (overfitting). Dividí los datos en un 80% entrenamiento y 20% prueba.

📈 Resultados y Conclusiones
El modelo permite identificar patrones clave de abandono. Algunos hallazgos importantes:

Tipo de Contrato: Los clientes con contrato "Mes a mes" presentan el riesgo más alto.

Cargos Mensuales: Existe una correlación directa entre cargos altos y la probabilidad de salida.

🚀 Cómo ejecutarlo
Clona este repositorio.

Sube el dataset customer_churn.csv incluido.

Ejecuta el notebook en Google Colab o Jupyter Notebook.
