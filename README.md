# Layouts para carga masiva / Bulk Upload Layouts

Plantillas (layouts) listas para cargar información contable de forma masiva.

## Layouts

- [NetSuite — Asientos contables (Journal Entries)](layouts/layout-asientos-netsuite.csv): CSV para importar asientos contables con Import CSV Records (Accounting → Journal Entry). Una fila por línea del asiento; las líneas del mismo asiento llevan el mismo External ID.

## Cómo usar

1. Descarga el layout y llénalo con tus datos, sin cambiar los encabezados.
2. Reemplaza los valores de ejemplo (subsidiaria, moneda, cuentas) por los de tu empresa.
3. Verifica que cada asiento cuadre: débitos = créditos.
4. Importa con la herramienta de carga masiva de tu sistema y revisa el log de errores.

## Nota

Los valores del ejemplo son ilustrativos. Revisa los catálogos (cuentas, subsidiarias, departamentos) de tu empresa antes de cargar.
