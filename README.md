# 🐧 Clustering de Pingüinos

Este proyecto tiene como objetivo agrupar diferentes especies de pingüinos utilizando técnicas de aprendizaje no supervisado como Clustering Jerárquico (Aglomerativo) y K-Means. Utiliza mediciones físicas como longitud del pico, profundidad del pico, longitud de aletas y masa corporal.

📁 Dataset: `penguins_size (1).csv`

---

## 📌 Objetivos del Proyecto

1. Importación y limpieza de datos
2. Análisis de valores faltantes y eliminación de filas incompletas
3. Visualización mediante dendogramas para clustering jerárquico
4. Clustering aglomerativo con representación de características físicas
5. Uso del método del codo para determinar el número óptimo de clusters con K-Means
6. Comparación de representaciones gráficas entre distintos atributos

---

## 📊 Visualizaciones

- Dendograma (para análisis jerárquico)
- Dispersión por:
  - Longitud y profundidad del pico
  - Longitud de aletas y masa corporal
- Método del codo para K-Means
- Clusters finales en ambas representaciones

---

## ⚙️ Requisitos

```bash
git clone https://github.com/tuusuario/clustering-pinguinos.git
cd clustering-pinguinos
python -m venv venv
source venv/bin/activate      # En Windows: venv\Scripts\activate
pip install -r requirements.txt
````

## 🔧 Tecnologías Utilizadas
  . Python 3

  . pandas

  . matplotlib

  . scipy

  . scikit-learn

## 📁 Estructura esperada

├── penguins_size (1).csv

├── clustering_penguins.ipynb

├── requirements.txt

├── .gitignore

└── README.md

## 📝 Licencia
Este proyecto es de uso educativo y libre, siempre que se cite la fuente original del dataset.
