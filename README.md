# A/B Testing para Toma de Decisiones Estratégicas – Sprint 10 (Tripleten Bootcamp)

## Descripción del proyecto

Este proyecto simula un escenario de negocio en el que una empresa digital evalúa el impacto de nuevas funcionalidades mediante un experimento A/B. El objetivo es determinar, a través del análisis estadístico, si las mejoras propuestas generan un cambio significativo en el comportamiento de los usuarios y, por ende, apoyar decisiones de negocio basadas en datos.

## Objetivos

- Evaluar el impacto de nuevas funcionalidades de la página web.
- Aplicar pruebas estadísticas para validar hipótesis.
- Extraer insights accionables que respalden decisiones estratégicas.

## Metodología

1. **Priorización de hipótesis** con el marco ICE (Impacto, Confianza, Facilidad).
2. **Revisión del diseño experimental** para asegurar la validez del test A/B.
3. **Análisis estadístico** con prueba U de Mann-Whitney.
4. **Visualización de resultados** para comunicar hallazgos de manera efectiva.

## Herramientas y tecnologías

- Python: `pandas`, `numpy`, `scipy.stats`, `matplotlib`, `seaborn`
- Jupyter Notebook
- Visualización de embudos de conversión y comparativas por grupo

## Resultados clave

**Priorización de hipótesis con ICE y RICE**

Se utilizó la metodología ICE para evaluar hipótesis con base en impacto y facilidad de implementación. Posteriormente, se aplicó RICE, incorporando el factor alcance, lo que reestructuró significativamente las prioridades y favoreció iniciativas con mayor potencial de impacto en un gran volumen de usuarios.

🔹 **Recomendación:** Para una tienda online con alto tráfico, RICE es el enfoque más adecuado, ya que:
- Maximiza el impacto total considerando la escala de usuarios.
- Equilibra mejor el retorno de inversión.
- Prioriza hipótesis con mayor potencial de crecimiento absoluto.

📌 **Hipótesis prioritaria:** Add a subscription form to all the main pages.

**Resultados del experimento A/B**

Tras aplicar el filtrado de valores atípicos y analizar la conversión entre grupos, se tomaron las siguientes conclusiones:
- El grupo B mostró una conversión estadísticamente superior al grupo A, con una diferencia relativa del 17%, incluso después de eliminar valores extremos.
- El tamaño promedio de los pedidos en el grupo B resultó un 7% menor que en el grupo A, aunque esta diferencia no fue estadísticamente significativa.
- El incremento en conversiones del grupo B no estuvo impulsado por pedidos más grandes, sino por una mayor cantidad de pedidos, lo que indica que el aumento en ingresos dependerá del volumen de conversiones y no del tamaño de los pedidos.

📌 **Decisión final:** Se optó por parar la prueba y considerar al grupo B como el grupo ganador, validando su desempeño a través del análisis estadístico y visualizaciones.

## Sobre mí

Proyecto realizado por **Andrea Mézquita**, egresada de Ingeniería Industrial y estudiante de análisis de datos en **Tripleten Bootcamp**. Mi enfoque es combinar la mejora de procesos con análisis de datos para generar soluciones estratégicas con impacto real.

LinkedIn: https://www.linkedin.com/in/andrea-mézquita
