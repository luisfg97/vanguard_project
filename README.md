# 📊 Vanguard A/B Test — Proyecto 2
**Autores:** David Barrero · Elías Chafih · Luis Fernández  
**Bootcamp:** Data Analytics — Ironhack  

## 📝 Descripción
Proyecto de análisis de un experimento A/B realizado por Vanguard para evaluar si una nueva interfaz web mejora la experiencia del usuario.

Incluye limpieza de datos, EDA, KPIs, pruebas de hipótesis y dashboard final en Power BI.

## 📁 Estructura del repositorio
```
├── data/                     
│   ├── df_final_demo.txt
│   ├── df_final_experiments.txt
│   ├── df_final_web_data_pt_1.txt
│   └── df_final_web_data_pt_2.txt
│
├── data Power BI/            
│   ├── demo_data.csv
│   └── web_data.csv
│
├── Presentacion.pbix         
├── vanguard_notebook.ipynb   
└── README.md
```

## 🔍 Qué hicimos
- Limpieza de datos y unificación de datasets.
- Análisis exploratorio (perfil del cliente y comportamiento digital).
- Cálculo de KPIs:
  - Tasa de finalización  
  - Tasa de error  
  - Duración por paso  
- Pruebas de hipótesis (Z-test de proporciones).
- Dashboard final en Power BI.

## 📈 Conclusiones principales
- La nueva interfaz (Test) aumenta la finalización del 49,85% al 58,52%.
- La mejora es estadísticamente significativa y supera el +5%.
- El Test genera más errores y un paso final más lento.

## 🛠️ Tecnologías
Python · Pandas · NumPy · SciPy · Matplotlib · Power BI · Jupyter Notebook
