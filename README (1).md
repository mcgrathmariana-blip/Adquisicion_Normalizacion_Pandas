
# Adquisición y Normalización de Datos con Pandas

## Descripción
Proyecto de integración de datos de ventas provenientes de dos fuentes:
un archivo CSV con transacciones y un archivo Excel con productos.

## Tecnologías utilizadas
- Python
- Pandas
- NumPy
- OpenPyXL
- PyArrow
- Google Colab

## Proceso realizado
1. Creación y adquisición de datos desde CSV y Excel.
2. Limpieza y normalización de datos.
3. Conversión de tipos de datos.
4. Integración de fuentes mediante merge.
5. Cálculo de total_venta.
6. Exportación del resultado a formato Parquet.
7. Verificación del archivo final.

## Fórmula
total_venta = cantidad * precio_unitario

## Estructura
- datos/transacciones.csv
- datos/productos.xlsx
- salida/ventas_finales.parquet
- notebooks/Adquisicion_Normalizacion_Pandas_Final.ipynb

## Instalación
Ejecutar:

pip install -r requirements.txt

## Ejecución
Abrir el notebook en Google Colab y ejecutar las celdas
en orden, desde el principio.
