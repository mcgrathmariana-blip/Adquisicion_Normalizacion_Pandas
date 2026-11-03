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
1. Adquisición de datos desde CSV y Excel.
2. Limpieza y normalización.
3. Conversión de tipos de datos.
4. Integración mediante merge.
5. Cálculo de total_venta.
6. Exportación a formato Parquet.
7. Verificación del archivo final.

## Fórmula
total_venta = cantidad * precio_unitario

## Estructura del proyecto
- datos/: archivos originales CSV y Excel.
- salida/: dataset final en formato Parquet.
- notebooks/: notebook con el desarrollo del proyecto.

## Instalación
pip install -r requirements.txt

## Ejecución
Abrir el notebook en Google Colab y ejecutar las celdas en orden.
