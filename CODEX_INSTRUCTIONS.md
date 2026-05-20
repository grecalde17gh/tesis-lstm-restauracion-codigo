# CODEX_INSTRUCTIONS.md

## Contexto del proyecto

Este repositorio contiene el código de una tesis/proyecto de maestría sobre optimización de portafolios de inversión usando inteligencia artificial, redes LSTM y procesamiento de lenguaje natural.

El archivo principal del proyecto es:

`Portafolio_de_inversiones_vf.ipynb`

El objetivo actual es restaurar la ejecución técnica del notebook para que vuelva a correr correctamente.

## Objetivo principal

Hacer que el notebook `Portafolio_de_inversiones_vf.ipynb` pueda ejecutarse correctamente de principio a fin, preservando la lógica original del proyecto.

## Restricciones estrictas

Codex NO debe:

- Actualizar los datos.
- Cambiar el período de análisis.
- Cambiar los tickers originales.
- Cambiar la metodología.
- Cambiar el modelo LSTM.
- Reemplazar el enfoque por otros modelos.
- Cambiar hiperparámetros salvo que sea estrictamente necesario para corregir un error técnico.
- Optimizar resultados.
- Reescribir conclusiones.
- Modificar el enfoque científico.
- Reestructurar completamente el repositorio.
- Eliminar celdas del notebook sin justificación.
- Descargar nuevos datos si los datos originales ya están disponibles o si el flujo original no lo requiere.

## Cambios permitidos

Codex SÍ puede:

- Corregir imports.
- Corregir rutas de archivos.
- Corregir errores por cambios de versiones de librerías.
- Crear un archivo `requirements.txt`.
- Crear un archivo `environment.yml` si es necesario.
- Crear un archivo `CHANGELOG_CODEX.md`.
- Agregar comentarios técnicos mínimos.
- Ajustar llamadas obsoletas de librerías como pandas, numpy, torch, pytorch-lightning, sklearn, matplotlib, yfinance, transformers, asyncpraw, nltk o similares.
- Separar credenciales en variables de entorno si encuentra tokens o claves embebidas.
- Proponer cambios antes de aplicarlos cuando puedan afectar resultados.

## Regla de mínima intervención

Todo cambio debe ser el mínimo necesario para que el código vuelva a ejecutarse.

Antes de modificar una celda importante, Codex debe explicar:

1. Qué error detectó.
2. Por qué ocurre.
3. Qué cambio mínimo propone.
4. Si el cambio puede afectar resultados.

## Documentación obligatoria

Cada cambio debe registrarse en `CHANGELOG_CODEX.md` con este formato:

```text
Archivo modificado:
Error encontrado:
Cambio realizado:
Razón técnica:
Impacto esperado:
Riesgo:
