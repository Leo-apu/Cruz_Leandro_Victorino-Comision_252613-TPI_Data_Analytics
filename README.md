# 📊 Pre-Entrega de Proyecto y Entrega-Final – Data Analytics

### 💼 SynthData Internship Challenge

Este repositorio contiene la **pre-entrega del Trabajo Práctico Integrador de Data Analytics**, correspondiente a las **etapas 1 y 2 del proyecto** de pasantía en *SynthData*.  
El objetivo es demostrar habilidades en **recopilación, preparación, limpieza y análisis de datos** utilizando **Python y Pandas**.
Además, se incorpora la **Entrega Final**, donde se desarrollan las etapas 3 y 4, enfocadas en análisis estadístico, visualización avanzada y comunicación de resultados.
---

## 🧩 Objetivos del Proyecto

El trabajo se divide en dos grandes etapas:

### 🔹 Etapa 1 – Recopilación y Preparación de Datos
- Cargar los **sets de datos** como DataFrames.
- Calcular **ventas mensuales** mediante variables y operadores.
- Implementar **estructuras de datos** (listas o diccionarios) para almacenar ventas (producto, precio, cantidad).
- Realizar un **análisis exploratorio inicial** con Pandas.
- Identificar **valores nulos y duplicados** y documentar el estado inicial.

### 🔹 Etapa 2 – Limpieza y Transformación de Datos
- **Limpiar** los datos: eliminar duplicados, caracteres no deseados, y normalizar formatos.
- **Transformar** los datos mediante filtros y cálculos derivados.
- **Agregar** información: ventas por categoría y análisis de ingresos.
- **Integrar** los datasets de ventas, clientes y marketing para un análisis completo.

### 🔹 Etapa 3 – Análisis Estadístico y Exploratorio
En esta etapa se profundizó en el estudio del dataset ya limpio, con el objetivo de comprender el comportamiento general de las ventas y detectar patrones relevantes.

Tareas realizadas:

- Cálculo de estadísticas descriptivas (promedios, medianas, máximos, mínimos y dispersión).
- Revisión de distribuciones de precio, cantidad y valor de venta.
- Identificación de tendencias y comportamientos por mes, categoría y producto.
- Separación y comparación de ventas con campaña y sin campaña.
- Evaluación del impacto del marketing mediante métricas y análisis temporal.
- Construcción de un mapa de correlación para evaluar relaciones entre variables numéricas.

Resultados de esta etapa:

- Se observaron patrones definidos en la evolución mensual, incluyendo un incremento notable posterior al inicio de la campaña.
- La correlación entre precio y cantidad es débil, mientras que la relación entre cantidad y valor de venta es más fuerte.
- La mayoría de los productos presentan mejores resultados dentro del período de campaña.


### 🔹 Etapa 4 – Visualización y Comunicación de Resultados
La última etapa se centró en representar visualmente los hallazgos identificados durante el análisis, utilizando gráficos claros y comparativos.

Tareas realizadas:

- Creación de histogramas, boxplots y series temporales para explorar distribuciones y tendencias.
- Gráficos de barras para analizar ventas por categoría, producto y mes.
- Comparaciones visuales entre ventas con campaña y sin campaña.
- Desarrollo de un dashboard interactivo con Plotly para explorar los datos dinámicamente.

Resultados visuales:

- Los gráficos permitieron confirmar patrones detectados previamente: crecimiento de ventas después del mes 4, temporalidad marcada y mayor desempeño durante campaña.
- Las visualizaciones facilitaron la interpretación de diferencias por categoría y producto.
- El dashboard permitió interactuar con la información y observar variaciones de manera más flexible.


---

## 🗂️ Estructura del Repositorio

```
📦 ENTREGA-FINAL
├── 📄 Entrega_Final.ipynb       # Notebook final del proyecto
📦 PRE-ENTREGA
├── 📄 Pre_entrega.ipynb           # Notebook principal del proyecto
├── 📁 DataSets/
│   ├── ventas.csv
│   ├── clientes.csv
│   └── marketing.csv
📄 README.md                   # Documentación del proyecto
```

---

## 🧠 Datasets Utilizados

1. **ventas.csv** → Datos de ventas de productos (precio, cantidad, fecha).  
   🔹 Uso: análisis de ventas, limpieza y estadísticas descriptivas.

2. **clientes.csv** → Información sobre los clientes.  
   🔹 Uso: unión con ventas para analizar características de clientes.

3. **marketing.csv** → Datos de campañas de marketing.  
   🔹 Uso: análisis de efectividad y correlación con ventas.

📂 Acceso a los datasets:
- [ventas.csv](https://drive.google.com/file/d/1jlo-TjeDEkIeHrbcdSVXO8pqzTTfyE6N/view?usp=sharing)  
- [clientes.csv](https://drive.google.com/file/d/11-FPOE9X1AvxGE6AUXTCspVQJzrLT_2f/view?usp=drive_link)  
- [marketing.csv](https://drive.google.com/file/d/1ZSfAcNDyo2eiioc7za_h57lvlm2RtScu/view?usp=drive_link)

---

## 🧾 Evaluación

La evaluación se basa en la siguiente rúbrica:

| Criterio | Descripción |
|----------|--------------|
| **Recopilación y Preparación de Datos** | Estructura y documentación de los datos |
| **Limpieza y Transformación** | Aplicación de técnicas adecuadas |
| **Análisis Estadístico y Exploratorio** | Interpretación de resultados |
| **Visualización y Comunicación de Resultados** | Presentación de visualizaciones y resultados |
| **Presentación Final** | Claridad, estructura y comunicación de resultados |
| **Documentación y Código** | Organización, comentarios y convenciones de estilo |

---

## ⚙️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** para manipulación de datos  
- **NumPy** para operaciones numéricas  
- **Matplotlib / Seaborn** para visualizaciones  
- **Google Colab** como entorno de trabajo  

---

## 🧩 Ejecución del Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Leo-apu/Cruz_Leandro_Victorino-Comision_252613-TPI_Data_Analytics
   cd Cruz_Leandro_Victorino-Comision_252613-TPI_Data_Analytics
   ```

2. Instalar dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Abrir el notebook:
   ```bash
   jupyter notebook Pre_entrega.ipynb
   ```
   o ejecutarlo directamente en **Google Colab**.

---

## 🧠 Autor

**Nombre y Apellido:** Leandro Victorino Cruz 
**Materia:** Data Analytics – SynthData Internship  
**Fecha:** Octubre 2025  
