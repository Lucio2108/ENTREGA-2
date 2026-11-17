entrega_2.ipynb
# Pre-entrega: Adquisición y Normalización con Pandas

Pipeline de adquisición, limpieza, integración (`merge`) y normalización de datos en Python utilizando `pandas`, integrando fuentes en formato CSV y Excel para exportar un dataset consolidado en formato Parquet.

## Estructura del Repositorio
* `Cars Datasets 2025 (1).csv`: Dataset automotriz base.
* `catalogo_productos.xlsx`: Maestro de productos con `id_producto`, `nombre_producto` y `precio_unitario`.
* `transacciones.csv`: Registro de ventas con `id_transaccion`, `id_producto`, `cantidad` y `fecha`.
* `entrega_2.ipynb`: Notebook de Google Colab con el código completo de adquisición, limpieza de nulos, conversión de tipos (`datetime`), `merge`, cálculo de `total_venta` y exportación.
* `ventas_consolidadas.parquet`: Archivo resultante limpio y optimizado.

## Librerías Necesarias
Para ejecutar el código se requieren las siguientes librerías:
```bash
pip install pandas numpy openpyxl pyarrow
