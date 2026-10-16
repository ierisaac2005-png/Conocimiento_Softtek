# Actividad 1 · Flujo del conocimiento en Softtek

[![Ejecutar en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ierisaac2005-png/Conocimiento_Softtek/blob/main/Actividad_1_Conocimiento_Softtek.ipynb)

**Autor:** Isaac Esquivel Ruiz  
**Materia:** Sistemas y tecnologías de administración del conocimiento

En esta actividad analizo cómo se genera, organiza, comparte y utiliza el conocimiento en un caso basado en Softtek. La idea es seguir el recorrido de una solución: desde que un equipo identifica una falla hasta que otros compañeros pueden consultar lo aprendido y reutilizarlo.

Softtek es la compañía de referencia. Los incidentes, documentos y procesos del ejercicio son simulados; no representan información interna de la empresa. Esta actividad está relacionada con el proyecto de gestión del conocimiento, pero es un trabajo separado.

## Qué incluye

- El prompt de la actividad y la respuesta de ChatGPT como evidencia de la consulta.
- El análisis de las cinco fases del ciclo del conocimiento.
- Ejemplos de conocimiento tácito y explícito en cada fase.
- Propuestas de apoyo de IA para documentar, clasificar, buscar información y detectar patrones.
- Un ejemplo con 12 tickets simulados y su gráfica.
- Un diagrama que muestra las etapas, el flujo entre áreas y los puntos de apoyo de IA.
- Interpretaciones de seis líneas por resultado, que sustituyen el video en esta versión.

## Ejecutarlo en Google Colab

1. Pulsa **Ejecutar en Colab** al inicio de este README.
2. Se abrirá `Actividad_1_Conocimiento_Softtek.ipynb` desde este repositorio.
3. Selecciona **Entorno de ejecución → Ejecutar todas**.

El enlace apunta al notebook en la raíz de la rama `main`. El archivo debe estar subido con ese nombre. Si cambias la rama o la ubicación, actualiza también el enlace del botón.

No se necesita GPU, conexión a Drive, archivos de datos adicionales ni claves de API. Los ejemplos están dentro del notebook y las bibliotecas utilizadas están normalmente disponibles en Colab. El archivo también incluye resultados guardados para consultarlos antes de ejecutar.

## Archivos del repositorio

| Archivo | Para qué sirve |
| --- | --- |
| [Actividad_1_Conocimiento_Softtek.ipynb](Actividad_1_Conocimiento_Softtek.ipynb) | Actividad completa, código, resultados e interpretaciones. |
| [requirements.txt](requirements.txt) | Versiones de las bibliotecas usadas en la prueba local. |
| [.gitignore](.gitignore) | Evita subir archivos temporales y entornos locales. |
| [resultados_actividad_softtek/diagrama_ciclo_softtek.png](resultados_actividad_softtek/diagrama_ciclo_softtek.png) | Diagrama de las cinco etapas del ciclo. |
| [resultados_actividad_softtek/tickets_simulados.png](resultados_actividad_softtek/tickets_simulados.png) | Gráfica de los incidentes del ejemplo. |

El notebook vuelve a generar las imágenes en `resultados_actividad_softtek` al ejecutarse. No necesita leer las imágenes existentes para funcionar.

## Ciclo del conocimiento

1. **Creación o captura:** reunir síntomas, registros y experiencia para entender un problema.
2. **Almacenamiento u organización:** documentar la solución, conservar su versión y clasificarla.
3. **Intercambio o transferencia:** compartir guías y experiencia entre los equipos.
4. **Aplicación:** usar lo aprendido y verificar si corresponde al caso.
5. **Actualización o retroalimentación:** revisar resultados, corregir documentos y detectar problemas recurrentes.

![Ciclo del conocimiento en el caso basado en Softtek](resultados_actividad_softtek/diagrama_ciclo_softtek.png)

## Ejemplo de análisis

Los 12 tickets simulados se distribuyen así:

| Problema | Cantidad |
| --- | ---: |
| Acceso a la cuenta | 6 |
| Respaldos | 3 |
| Error de aplicación | 2 |
| Permisos | 1 |

Los problemas de acceso representan la mitad de los tickets del ejemplo. Esto permite discutir qué guía o proceso convendría revisar, considerando también el impacto y el riesgo, no solo la frecuencia.

![Distribución de tickets simulados](resultados_actividad_softtek/tickets_simulados.png)

## Alcance de esta actividad

El código genera tablas, realiza un conteo sencillo y dibuja las gráficas. Los apoyos de IA se explican de manera conceptual: aquí no se entrena un clasificador ni se ejecuta un modelo generativo o un buscador semántico. Esas funciones pertenecen al desarrollo posterior del proyecto.

Las interpretaciones están escritas en Markdown y corresponden a los ejemplos incluidos. Si se modifican los datos, también deben revisarse las interpretaciones.

## Ejecutarlo en una computadora

La ejecución local se comprobó con Python 3.12. Desde la carpeta del repositorio:

```bash
python -m pip install -r requirements.txt
python -m pip install notebook
python -m notebook
```

Abre `Actividad_1_Conocimiento_Softtek.ipynb` y ejecuta todas las celdas en orden. La instalación de Jupyter es opcional si se utiliza Colab o ya se cuenta con un editor compatible con notebooks.
