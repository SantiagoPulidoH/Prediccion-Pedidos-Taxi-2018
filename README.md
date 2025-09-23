# Predicción de Pedidos de Taxi (2018)

Proyecto de series temporales para **Sweet Lift Taxi**: predecir el número de pedidos de taxi para la **próxima hora** a partir de datos históricos por hora.

**Métrica objetivo:** RMSE ≤ 48 en test.

## Descripción
- Remuestreo a 1H y creación de *features* de calendario (hora, día de semana, etc.), lags y medias móviles.
- Comparación de modelos: Regresión Lineal, Random Forest y LightGBM.
- Evaluación con RMSE en *holdout* (10% final del período).

## Resultados (resumen)
- **LightGBM**: RMSE test ≈ **39.63** (mejor).  
- **Random Forest**: RMSE test ≈ 42.86.  
- **Linear Regression**: RMSE test ≈ 45.83.  
Cumple el objetivo del proyecto (RMSE ≤ 48).  
> Ver notebook en `notebooks/proyecto_taxis_2018.ipynb`. :contentReference[oaicite:1]{index=1}

## Estructura
- `notebooks/`: notebook principal con análisis y gráficas (outputs incluidos).
- `data/`: no incluye los datos originales; ver instrucciones en `data/README.md`.
- `requirements.txt`: dependencias mínimas para reproducir.

## Reproducir (opcional)
1) Crear entorno e instalar:
```bash
python -m venv .venv
.venv\Scripts\activate   # Windows
pip install -r requirements.txt
