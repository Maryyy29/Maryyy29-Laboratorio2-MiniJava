# Laboratorio 2 – Analizador sintáctico MiniJava

Repositorio organizado para la entrega y ejecución del Laboratorio 2. Incluye el cuaderno de Google Colab y cuatro archivos de prueba en formato `.txt`.

## Estructura

```text
.
├── README.md
├── Programas_prueba_MiniJava.txt
├── notebooks/
│   └── ariasmedina-mariaalejandra-Laboratorio2.ipynb
└── pruebas/
    ├── 01_programa_valido_basico.txt
    ├── 02_programa_valido_completo.txt
    ├── 03_programa_con_errores.txt
    └── 04_programa_errores_completos.txt
```

## Requisitos

- Python 3
- Pyparsing (`pip install pyparsing`)
- Google Colab o Jupyter Notebook

## Ejecución en Google Colab

1. Abrir `notebooks/ariasmedina-mariaalejandra-Laboratorio2.ipynb` en Google Colab.
2. Ejecutar las celdas en orden.
3. Cuando el cuaderno solicite un archivo, cargar uno de los `.txt` ubicados en `pruebas/`.
4. Revisar el estado sintáctico, los errores reportados y el árbol de análisis.

## Archivos de prueba

- `01_programa_valido_basico.txt`: programa válido con declaraciones y estructuras básicas.
- `02_programa_valido_completo.txt`: programa válido con condicionales, ciclos, `switch` y expresiones.
- `03_programa_con_errores.txt`: casos de errores en condición, encabezado `for` y punto y coma.
- `04_programa_errores_completos.txt`: conjunto amplio de errores para evaluar recuperación.
- `Programas_prueba_MiniJava.txt`: los cuatro programas reunidos en un único archivo.

## Datos académicos

- Estudiante: Maria Alejandra Arias Medina
- NRC: 2439

## Nota

Los archivos de prueba sirven para comprobar el comportamiento del analizador. Antes de entregar, ejecutar cada caso y contrastar la salida con los requisitos y ejemplos de la rúbrica. La presencia de los archivos en GitHub no sustituye la validación funcional del notebook.
