# Leicester City 2015/16 – Project Context

## Objetivo

Proyecto de portfolio para Data Analyst Jr.

Pregunta principal:

¿Cómo logró Leicester City ganar la Premier League 2015/16?

El objetivo es analizar los datos de la temporada para identificar los factores que explican su campeonato.

## Dataset

- Fuente: resultados y estadísticas históricas de la Premier League.
- División analizada: E0.
- Temporada: 2015/16.
- Registros: 380 partidos.
- Equipos: 20.
- Columnas renombradas: division, home_team, away_team, entre otras.

## Análisis contemplados

- Rendimiento general de Leicester.
- Comparación con sus principales competidores.
- Rendimiento como local y visitante.
- Eficiencia ofensiva y estadísticas de disparos.
- Expectativas de las casas de apuestas.
- Comparación entre resultados esperados y obtenidos.

## Validaciones realizadas

- 380 registros correspondientes a la temporada.
- 20 equipos.
- No se detectaron duplicados.
- No se detectaron inconsistencias ni goles negativos.
- Se identificaron tres valores nulos en BWH, BWD y BWA, correspondientes al partido Tottenham-Newcastle.
- Esos valores deben conservarse y considerarse al analizar las apuestas.

## Decisiones importantes

- No modificar los tipos de datos existentes sin una justificación y autorización previa.
- En particular, conservar match_date como string por ahora.
- No eliminar registros o valores nulos sin evaluar previamente su impacto.
- Mantener la estructura y el enfoque del proyecto original.
- Verificar todas las métricas antes de incorporarlas al README.

## Estado del proyecto

El notebook ya contempla análisis de resultados y tabla de posiciones, rendimiento local/visitante, eficiencia de disparos y favoritos de Bet365.

El README contiene resultados preliminares que deben verificarse contra el código y el dataset.

## Próximas prioridades

1. Auditar el notebook y verificar los resultados existentes.
2. Identificar oportunidades de mejora analítica.
3. Mejorar la calidad y eficiencia del código.
4. Incorporar análisis adicionales que aporten valor.
5. Diseñar visualizaciones profesionales.
6. Mejorar las conclusiones.
7. Actualizar el README y presentar el proyecto en GitHub.

## Criterio de calidad

El proyecto debe ser reproducible, técnicamente correcto, visualmente claro y defendible en una entrevista laboral.