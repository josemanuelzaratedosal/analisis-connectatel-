# 📊 Proyecto 6: Análisis de Datos de Clientes - ConnectaTel

## 📝 Descripción del Proyecto
Este proyecto se enfoca en el análisis de una base de datos de telecomunicaciones para la empresa **ConnectaTel**. El trabajo consistió en procesar datos de consumo mensual y perfiles demográficos para transformar datos crudos en información estratégica que ayude a la toma de decisiones comerciales.

---

## 🎯 Objetivos del Proyecto
* **Procesamiento de Datos:** Limpieza de valores nulos y corrección de tipos de datos.
* **Análisis de Consumo:** Evaluación de patrones en llamadas, minutos y mensajes.
* **Segmentación:** Creación de perfiles de usuario basados en edad y volumen de actividad.
* **Visualización:** Generación de gráficos para identificar tendencias y comportamientos de los clientes.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Librerías principales:** `Pandas`, `NumPy`, `Seaborn` y `Matplotlib`.
* **Herramienta de desarrollo:** Google Colab.

---

## 📈 Etapas Realizadas

### 1. Preparación de los Datos
* Se manejaron valores faltantes en las columnas de actividad, asegurando que los usuarios sin consumo fueran contabilizados correctamente con un valor de 0.
* Se validó la consistencia de los IDs de usuario y las categorías de los planes (Básico vs. Premium).

### 2. Segmentación de Usuarios
* **Segmentación por Edad:** Dividida en Joven, Adulto y Adulto Mayor.
* **Segmentación por Uso:** Clasificación de clientes según su intensidad de consumo (Bajo, Medio y Alto uso).

### 3. Insights Clave
* **Potencial de Conversión:** Se detectó que muchos usuarios con "Alto uso" de servicios aún están en el Plan Básico, lo que representa una oportunidad directa para ofrecerles el Plan Premium.
* **Perfil de Usuario:** Los clientes adultos (30-60 años) son el segmento con mayor volumen de actividad y estabilidad en la plataforma.

---

## 🚀 Recomendaciones Estratégicas
1. **Campañas de Up-selling:** Dirigir promociones del Plan Premium a los usuarios identificados en el segmento de "Alto uso".
2. **Nuevos Productos:** Considerar un plan intermedio para capturar a los usuarios que superan el plan básico pero no llegan al nivel de uso del premium.
3. **Retención:** Monitorear a los usuarios de "Bajo uso" para prevenir la cancelación del servicio (churn).

---

## ⚙️ Instrucciones de Uso
1. Descarga el archivo `.ipynb` de este repositorio.
2. Cárgalo en tu entorno de **Google Colab**.
3. Ejecuta las celdas para visualizar los resultados y las gráficas del análisis.
