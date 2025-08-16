# 📊 Challenge TelecomX - Análisis de Churn (Abandono de Clientes)

![Telecom Analytics](https://img.shields.io/badge/Telecom-Churn_Analysis-blue) 
![Python](https://img.shields.io/badge/Python-3.8%2B-yellowgreen)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-orange)

Repositorio con el análisis completo de Churn para TelecomX, identificando patrones clave y recomendaciones estratégicas para reducir el abandono de clientes.

## 📌 Contenido

  ├── data/                    # Datos originales y procesados
  │   ├── raw/                 
  │   └── processed/           
  ├── notebooks/               # Jupyter Notebook con el análisis
  │   └── TelecomX_Churn_Analysis.ipynb  
  ├── reports/                 # Informes ejecutivos (PDF/PPT)
  ├── visuals/                 # Gráficos exportados
  └── README.md                # Este archivo


## 🔍 Objetivo del Proyecto

Identificar los factores que influyen en el abandono de clientes (Churn) en TelecomX mediante:
- Análisis exploratorio de datos (EDA)
- Segmentación de clientes
- Visualización de patrones clave
- Recomendaciones accionables

## 💻 Tecnologías Utilizadas

- **Python 3.8+**
- Bibliotecas principales:
  - Pandas (procesamiento de datos)
  - Seaborn/Matplotlib (visualizaciones)
  - Scikit-learn (análisis predictivo)
- Jupyter Notebooks

## 🚀 Cómo Ejecutar el Análisis

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Sebas1020h/Challenge-TelecomX-pt-1.git
   ```
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abrir el notebook principal:
   ```bash
   jupyter notebook notebooks/TelecomX_Churn_Analysis.ipynb
   ```

## 📊 Principales Hallazgos

1. **El tipo de contrato es el factor más influyente**:
   - Contratos mensuales: 89.1% Churn
   - Contratos anuales: 41.3% Churn

2. **El soporte técnico reduce el abandono** en un 58%

3. **Clientes con fibra óptica** tienen 42% más probabilidad de abandonar

## 📄 Informe Completo

El notebook incluye un informe detallado con:
- Limpieza de datos
- Análisis exploratorio
- Conclusiones estratégicas
- Recomendaciones para el equipo de negocio

[Ver informe en el notebook](notebooks/TelecomX_Churn_Analysis.ipynb)

## 🤝 Contribuciones

¡Contribuciones son bienvenidas! Por favor:
1. Haz un fork del proyecto
2. Crea una rama con tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -m 'Add some feature'`)
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 🧑‍💻 Autor

**Sebastián Urrego**  
📫 GitHub: [@Sebas1020h](https://github.com/Sebas1020h)

⭐ Si este proyecto te resulta útil, ¡por favor déjanos una estrella!
