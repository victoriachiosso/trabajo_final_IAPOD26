# Trabajo Práctico Integrador  2026
## Introducción al análisis de datos con Python y GitHub

Este práctico está pensado como una primera experiencia de análisis de datos.  
No vamos a importar archivos externos. Los datos estarán cargados directamente en el código.

La idea es trabajar con datos de estudiantes y responder preguntas simples usando Python, pandas y gráficos.

## Objetivo del trabajo

Desarrollar un pequeño análisis de datos educativos que permita observar:

- cantidad de estudiantes;
- promedio de edad;
- promedio de notas;
- estudiantes aprobados y desaprobados;
- relación entre trabajo y rendimiento;
- uso de IA;
- horas de estudio y nota final.

Al final, el trabajo debe subirse a GitHub.

## Datos del trabajo
Vamos a usar una lista de diccionarios. Pueden utilizar la que se presenta a continuación o crear una propia.
Cada diccionario representa a un estudiante.

estudiantes = [
    {"nombre": "Ana", "edad": 22, "trabaja": "Sí", "horas_estudio": 5, "nota": 8, "usa_ia": "Sí"},
    {"nombre": "Juan", "edad": 28, "trabaja": "Sí", "horas_estudio": 2, "nota": 5, "usa_ia": "No"},
    {"nombre": "Sofía", "edad": 20, "trabaja": "No", "horas_estudio": 6, "nota": 9, "usa_ia": "Sí"},
    {"nombre": "Pedro", "edad": 24, "trabaja": "No", "horas_estudio": 3, "nota": 6, "usa_ia": "No"},
    {"nombre": "Lucía", "edad": 31, "trabaja": "Sí", "horas_estudio": 4, "nota": 7, "usa_ia": "Sí"},
    {"nombre": "Martín", "edad": 19, "trabaja": "No", "horas_estudio": 2, "nota": 4, "usa_ia": "No"},
    {"nombre": "Carla", "edad": 26, "trabaja": "Sí", "horas_estudio": 7, "nota": 9, "usa_ia": "Sí"},
    {"nombre": "Diego", "edad": 23, "trabaja": "No", "horas_estudio": 4, "nota": 7, "usa_ia": "Sí"},
]
