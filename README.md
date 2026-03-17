# 📊 Data Visualization with Power BI | Análisis de Datos con Power BI

Proyecto de análisis de datos enfocado en la exploración, limpieza y transformación de un dataset de marketing para su posterior visualización en Power BI.  
Se aplicaron técnicas de análisis exploratorio y preprocesamiento en Python para mejorar la calidad de los datos y generar insights relevantes sobre el comportamiento de los clientes.

---

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es explorar, limpiar y preparar un dataset de marketing para su análisis y visualización, permitiendo comprender el perfil del cliente, su comportamiento de compra y su respuesta a campañas.

Este análisis busca:

- Evaluar la calidad y estructura del dataset.
- Identificar problemas como duplicados, valores erróneos y tipos de datos incorrectos.
- Transformar variables para mejorar su interpretación.
- Preparar los datos para su uso en herramientas de visualización.
- Generar indicadores clave (KPIs) para el análisis de negocio.

---

## 🛠️ Herramientas utilizadas

- Python  
- Google Colab  
- Pandas  
- Power BI  

---

## 🔎 Proceso de análisis

El análisis se desarrolló en varias etapas principales.

### 1. Exploración inicial del dataset

Se analizó la estructura general del dataset, identificando dimensiones, tipos de datos y coherencia de la información.

Durante esta etapa se detectaron:

- Columnas adicionales no contempladas inicialmente  
- Variables con formato incorrecto (valores numéricos como texto)  
- Columnas con símbolos que impedían su correcto análisis  

---

### 2. Limpieza y preprocesamiento de datos

Se aplicaron diferentes técnicas para mejorar la calidad del dataset:

- Eliminación de 184 registros duplicados  
- Corrección de tipos de datos en variables numéricas  
- Eliminación de símbolos en columnas monetarias  
- Eliminación de columnas sin variabilidad (sin valor analítico)  
- Tratamiento de valores negativos en variables específicas  

Estas acciones permitieron asegurar la consistencia y confiabilidad de los datos.

---

### 3. Transformación de variables

Se realizaron transformaciones clave para facilitar el análisis:

- Creación de la variable **Marital_Status** a partir de variables binarias  
- Creación de la variable **Education** a partir de niveles educativos  
- Eliminación de columnas redundantes utilizadas en la transformación  

Estas transformaciones permitieron simplificar el análisis y mejorar la interpretación de los datos.

---

### 4. Análisis y definición de KPIs

Se definieron indicadores clave para responder preguntas de negocio relacionadas con el comportamiento del cliente.

Se analizaron aspectos como:

- Nivel de gasto según características del cliente  
- Influencia de variables demográficas en el consumo  
- Preferencias de compra según canal  
- Impacto del nivel educativo en el consumo de productos premium  
- Uso de descuentos según edad  

---

## 📊 Resultados obtenidos

A partir del análisis se identificaron varios insights relevantes:

- El estado civil influye en el nivel de gasto, destacando ciertos segmentos con mayor valor para el negocio.  
- Los clientes sin hijos presentan un mayor gasto promedio en comparación con aquellos con responsabilidades familiares.  
- Los clientes con mayores ingresos muestran preferencia por canales de compra específicos.  
- El nivel educativo influye en el consumo de productos premium.  
- El uso de descuentos aumenta con la edad, evidenciando mayor sensibilidad al precio en ciertos segmentos.  
