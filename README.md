# Taller-colaborativo
Nuestro primer proyecto en equipo 
# Ulises Caicedo Espinosa
# Jose Luis Charria Cifuentes
# Predicción temprana del uso problemático de Internet en niños y adolescentes a partir de variables de actividad física y condición física
# Autor(es):
Ulises Caicedo Espinosa – Grupo 6
# Programa: Maestría en Inteligencia Artificial Aplicada – Universidad ICESI
# Correo(s): ulcaicedo31@gmail.com - Jose616@live.com
# 1. Análisis del problema
  1.1 Contexto
El uso problemático de Internet (UPI) en población infantil y adolescente se asocia con riesgos en salud mental (ansiedad, depresión), desempeño académico y habilidades socioemocionales. La disponibilidad masiva de dispositivos y conectividad ha incrementado la exposición y la variabilidad de patrones de uso, dificultando la identificación temprana de conductas de riesgo.
1.2 Problema central
Las instituciones educativas y de salud carecen de herramientas objetivas, escalables y tempranas para identificar niveles de UPI, especialmente en etapas previas a la manifestación clínica.
1.3 Formulación analítica
Se plantea construir un modelo predictivo supervisado, con variable objetivo ordinal (niveles de UPI), a partir de variables de actividad física y condición física, que permita estimar el nivel de riesgo individual.
1.4 Supuestos
•	Existe señal predictiva entre actividad/condición física y UPI.
•	Los datos disponibles son representativos y medibles de forma consistente.
•	La métrica de evaluación debe reflejar la naturaleza ordinal del problema.
1.5 Riesgos
•	Sesgos de muestreo y medición.
•	Correlación espuria (no causalidad).
•	Sobreajuste por alta dimensionalidad o bajo tamaño efectivo.
# 2. Árbol de problemas
Problema central: Dificultad para identificar tempranamente el uso problemático de Internet en niños y adolescentes.
Causas (raíces):
•	Falta de indicadores tempranos cuantificables.
•	Escasa integración de datos físicos y conductuales.
•	Limitaciones en herramientas analíticas en entornos educativos.
Causas intermedias:
•	Baja actividad física / hábitos sedentarios.
•	Ausencia de monitoreo sistemático.
•	Heterogeneidad en comportamientos digitales.
Efectos (ramas):
•	Deterioro en salud mental.
•	Bajo rendimiento académico.
•	Problemas de socialización.
•	Intervenciones tardías y menos efectivas.
# 3. Objetivos
  3.1 Objetivo general
Desarrollar un modelo predictivo basado en aprendizaje automático que estime el nivel de uso problemático de Internet en niños y adolescentes a partir de variables de actividad física y condición física.
3.2 Objetivos específicos
1.	Realizar análisis exploratorio para caracterizar la relación entre variables físicas y niveles de UPI.
2.	Diseñar e implementar un pipeline de preparación de datos (limpieza, imputación, codificación y escalamiento).
3.	Comparar múltiples modelos supervisados con enfoque ordinal.
4.	Evaluar el desempeño mediante quadratic weighted kappa (QWK).
5.	Analizar la importancia de variables y la interpretabilidad del modelo.
6.	Identificar limitaciones y proponer mejoras para implementación real.
# 4. Estado del arte
  4.1 UPI y salud digital
  La literatura reporta que el UPI está asociado con factores conductuales y fisiológicos. Estudios recientes sugieren que         patrones de actividad física y sedentarismo pueden correlacionarse con conductas digitales de riesgo.
  4.2 Modelos predictivos en salud
  El uso de aprendizaje automático en salud ha permitido la detección temprana de condiciones a partir de variables indirectas.    Modelos de ensamble (Random Forest, Gradient Boosting) han mostrado alto desempeño en problemas no lineales y con                interacciones complejas.
  4.3 Clasificación ordinal
  Problemas donde la variable objetivo tiene orden requieren métricas y enfoques específicos. La métrica quadratic weighted        kappa es ampliamente utilizada para evaluar concordancia en escalas ordinales.
  4.4 Interpretabilidad
  En dominios sensibles, la interpretabilidad es crítica. Técnicas como SHAP permiten explicar la contribución de variables a      nivel global y local, aumentando la confianza en el modelo.
  4.5 Brecha identificada
  Existe una oportunidad en integrar variables de actividad física como proxy para detectar UPI, con modelos que respeten la       naturaleza ordinal y sean interpretables.
# 5. Planeación y tareas
  5.1 Fases del proyecto
  Fase 1: Comprensión del problema
  •	Definición del objetivo
  •	Análisis del contexto
  Fase 2: Datos
  •	Carga y exploración (EDA)
  •	Análisis de calidad
  Fase 3: Preparación
  •	Limpieza
  •	Imputación
  •	Transformaciones
  Fase 4: Modelado
  •	Selección de modelos
  •	Entrenamiento
  •	Validación cruzada
  Fase 5: Evaluación
  •	Métrica QWK
  •	Comparación de modelos
  Fase 6: Interpretación
  •	Importancia de variables
  •	SHAP
  Fase 7: Documentación
  •	Informe técnico
  •	Presentación
  5.2 Cronograma (semanas)
  Semana	Actividad
  1	Análisis del problema
  2	EDA y calidad de datos
  3	Preparación de datos
  4	Modelado inicial
  5	Optimización y evaluación
  6	Interpretación
  7	Documentación


