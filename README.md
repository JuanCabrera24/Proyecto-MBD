
# Predicciones de Ventas y Tendencias de Mercado en PyMES

Este repositorio contiene el trabajo final de grado presentado en la **Universidad de las Américas**, dentro de la **Maestría en Inteligencia de Negocios y Ciencia de Datos**. El proyecto utiliza análisis de series temporales para predecir ingresos y detectar tendencias de mercado en pequeñas y medianas empresas (PyMES).

---

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Tecnologías y Herramientas](#tecnologías-y-herramientas)
3. [Estructura del Repositorio](#estructura-del-repositorio)
4. [Resultados Principales](#resultados-principales)
5. [Instrucciones de Uso](#instrucciones-de-uso)
6. [Contribuciones](#contribuciones)
7. [Licencia](#licencia)

---

## Descripción del Proyecto

El objetivo del proyecto es analizar los datos de facturación de la empresa **Distribuidora Cabrera** para:

- Generar predicciones de ventas mensuales utilizando el modelo **SARIMA**.
- Detectar patrones estacionales y tendencias de mercado.
- Proponer estrategias basadas en datos que mejoren la competitividad y sostenibilidad de las PyMES.

### Palabras clave

- **Modelos Predictivos**
- **Series Temporales**
- **SARIMA**
- **Inteligencia de Negocios**

---

## Tecnologías y Herramientas

- **Python**: Lenguaje de programación utilizado.
- **Librerías**:
  - `pandas`: Para manejo de datos.
  - `matplotlib`: Para visualización de gráficos.
  - `statsmodels`: Para implementación de modelos estadísticos.
- **Microsoft Excel**: Para la consolidación de datos.
- **Modelo SARIMA**: Para análisis y predicción de ingresos.

---

## Estructura del Repositorio

```plaintext
📂 Proyecto_Final
├── 📂 data
│   └── ventasmensuales.xlsx  # Datos de ingresos mensuales (formato Excel).
├── 📂 notebooks
│   └── analisis_series_temporales.ipynb  # Código Python para el análisis.
├── 📂 outputs
│   └── graficos/  # Visualizaciones generadas.
├── README.md       # Descripción general del repositorio.
└── informe_final.pdf  # Documento del trabajo final.
```

---

## Resultados Principales

- Implementación exitosa del modelo SARIMA (1,1,0)x(1,1,0,12), capturando estacionalidad y tendencias.
- Predicción de ingresos para los próximos 24 meses con métricas de error moderadas:
  - **Error Absoluto Medio (MAE)**: 10,845 USD.
  - **Error Cuadrático Medio (RMSE)**: 15,014 USD.
- Propuesta de estrategias organizacionales basadas en los resultados obtenidos.

---

## Instrucciones de Uso

### 1. Requisitos previos

- Python 3.x instalado.
- Dependencias: Instala las librerías necesarias ejecutando:
  ```bash
  pip install pandas matplotlib statsmodels openpyxl
  ```

### 2. Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/predicciones-pymes.git
   cd predicciones-pymes
   ```
2. Abre el archivo `notebooks/analisis_series_temporales.ipynb` en Jupyter Notebook.
3. Ejecuta las celdas para realizar el análisis y generar las visualizaciones.

---

## Contribuciones

- **Autor**: Juan José Cabrera Becerra
- **Director del Proyecto**: Ph.D. Manuel Eugenio Morocho Cayamcela

---

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).
