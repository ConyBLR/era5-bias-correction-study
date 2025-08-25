# Análisis ERA5 - Trabajo Final

**Curso:** Una herramienta para la administración y análisis de grandes cantidades de datos (UNSa)  
**Estudiante:** Constanza B. Lopez Ruiz
**Fecha:** Agosto 2025

## Descripción
Análisis de datos climáticos ERA5 y su adaptación mediante modelos SARIMAX y MLP usando datos medidos in-situ.

## Archivos incluidos

| Archivo | Descripción |
|---------|-------------|
| `01_descaga_ERA5.ipynb` | Descarga de datos ERA5 desde la API |
| `02_extraer_t2m_.ipynb` | Preprocesamiento y extracción de temperatura |
| `sarimax_diff.ipynb` | Modelo SARIMAX con diferenciación |
| `train_test_mlp_diff.ipynb` | Modelo MLP con diferenciación |
| `LICENSE` | Licencia MIT |
| `README.md` | Este archivo |


## Nota sobre el módulo de métricas

Los notebooks `sarimax_diff.ipynb` y `train_test_mlp_diff.ipynb` utilizan un módulo personalizado `Metrics.py` para el cálculo de métricas y visualizaciones.

**Para reproducir el análisis:**
- Debes proporcionar tu propio módulo de métricas o
- Adaptar el código para usar las funciones de métricas estándar de scikit-learn.

## Consultas
constanza.lopezruiz@conicet.gov.ar
