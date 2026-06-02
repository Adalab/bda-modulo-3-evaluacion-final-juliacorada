# ✈️ ¿Vuelan más los doctores que los que dejaron el instituto?

Spoiler: no. Pero hay muchas otras cosas interesantes que descubrir.

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Adalab/bda-modulo-3-evaluacion-final-juliacorada.git
   ```
2. Abre el notebook `evaluacion_modulo3_juliacorada.ipynb` en Jupyter
3. Asegúrate de tener los dos CSV en la misma carpeta que el notebook
4. Ejecuta las celdas en orden de arriba a abajo

---

## ¿De qué va esto?

Este proyecto analiza el programa de lealtad de una aerolínea canadiense a partir de dos datasets:
el perfil de sus clientes (educación, salario, estado civil, tipo de tarjeta...) y su actividad de vuelo
mes a mes (vuelos reservados, distancia, puntos acumulados y canjeados).

El objetivo es explorar los datos, limpiarlos, analizarlos estadísticamente y visualizarlos
para extraer conclusiones reales sobre el comportamiento de los clientes.

---

## ¿Qué encontrarás aquí?

El análisis completo está en un único notebook dividido en cuatro fases:

### 🔍 Fase 1 – Exploración y Limpieza
Antes de analizar nada, hay que entender qué tenemos entre manos.
Se unen los dos datasets, se detectan nulos, se eliminan salarios imposibles (sí, había negativos)
y se aseguran los tipos de datos correctos.

### 📊 Fase 2 – Análisis Estadístico
Medias, medianas, modas, outliers y correlaciones.
¿Sabías que la mayoría de clientes acumula puntos pero casi nadie los canjea?
¿O que la distancia y los puntos tienen una correlación del 0.99?

### 📈 Fase 3 – Visualización
Seis preguntas, seis gráficas. Desde la estacionalidad de los vuelos hasta
la proporción de tarjetas de fidelidad, pasando por el salario según nivel educativo.

### 🎯 Fase 4 – ¿Influye el nivel educativo en los vuelos reservados?
Análisis descriptivo por grupo educativo para responder una pregunta concreta.
La respuesta es sorprendentemente aburrida — y eso también es un resultado válido.

---

## Estructura del proyecto

```
📁 proyecto
├── Customer_Flight_Activity.csv
├── Customer_Loyalty_History.csv
├── evaluacion_modulo3_juliacorada.ipynb
└── README.md
```

---

## Tecnologías usadas

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

*Proyecto realizado como evaluación final del Módulo 3 de Data Analytics en Adalab.*
