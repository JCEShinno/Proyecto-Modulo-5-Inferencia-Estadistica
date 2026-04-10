# Proyecto Módulo 5 - Inferencia Estadística

## Descripción
Proyecto de inferencia estadística aplicado al análisis de hábitos saludables en jóvenes universitarios. El trabajo desarrolla una investigación cuantitativa completa, incluyendo formulación del problema, hipótesis, simulación de datos, diseño muestral, distribuciones de probabilidad, Teorema del Límite Central, intervalos de confianza y pruebas de hipótesis.

## Objetivo
Analizar estadísticamente factores relacionados con el sueño, la alimentación, la actividad física y el bienestar percibido en estudiantes universitarios, con el fin de generar conclusiones e insumos útiles para futuras políticas de bienestar estudiantil.

## Tecnologías utilizadas
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib

## Estructura del proyecto
- `data/raw/`: población simulada, muestra simulada y diccionario de variables
- `data/interim/`: tablas intermedias con probabilidades, TLC, intervalos de confianza y pruebas de hipótesis
- `notebooks/`: notebook principal del proyecto
- `outputs/`: gráficos exportados del análisis
- `docs/`: informe final del proyecto
- `README.md`: descripción general del repositorio

## Desarrollo del proyecto
El notebook principal se organiza en seis etapas:

1. Método científico y diseño preliminar del estudio  
2. Probabilidad y estadística  
3. Distribución de probabilidad  
4. Distribución muestral y Teorema del Límite Central  
5. Intervalos de confianza para la media  
6. Test de significancia  

## Principales hallazgos
- La proporción de estudiantes con sueño insuficiente fue superior al 50%.
- Se encontró una diferencia estadísticamente significativa en las horas de sueño promedio entre estudiantes con actividad física suficiente e insuficiente.
- La media de las medias muestrales se aproximó a la media poblacional al aumentar el tamaño de muestra, verificando empíricamente el Teorema del Límite Central.
- A mayor tamaño muestral, menor ancho del intervalo de confianza.
- A mayor nivel de confianza, mayor amplitud del intervalo.

## Archivos principales
- `notebooks/proyecto_modulo_5_inferencia.ipynb`
- `data/raw/diccionario_variables.csv`
- `data/raw/poblacion_universitaria_simulada.csv`
- `data/raw/muestra_habitos_universitarios.csv`
- `data/interim/probabilidades_eventos.csv`
- `data/interim/resumen_distribuciones.csv`
- `data/interim/resumen_tlc.csv`
- `data/interim/intervalos_confianza_medias.csv`
- `data/interim/resultados_test_hipotesis.csv`
- `outputs/arbol_probabilidad_sueno_actividad.png`
- `outputs/distribuciones_probabilidad_modulo5.png`
- `outputs/tlc_distribuciones_muestrales.png`
- `outputs/tlc_dispersion_medias.png`
- `outputs/ancho_intervalo_confianza.png`

## Resultados
El proyecto permitió aplicar de forma completa la lógica de la inferencia estadística a un problema de salud universitaria, integrando método científico, muestreo, estimación y pruebas de hipótesis para obtener conclusiones con base metodológica clara.

## Autor
Juan Carlos Castro Encina
