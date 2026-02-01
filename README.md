# DataMiningIA_Cristiam-Morales

# Proyecto de Minería de Datos con IA

## Objetivo y Pregunta Central
El objetivo de este proyecto es aplicar técnicas de minería de datos, con apoyo de inteligencia artificial, para analizar datos de clientes de seguros y predecir si un cliente renovará su póliza.

**Pregunta central:**  
¿Qué variables influyen en la renovación de una póliza de seguros?

---

## Fuente de los Datos y Proceso de Limpieza
El dataset fue creado de forma sintética utilizando Python con apoyo de inteligencia artificial.  
Contiene 500 registros de clientes de seguros.

Durante la preparación de los datos se realizaron las siguientes tareas:
- Generación de datos sin valores faltantes.
- Revisión de duplicados.
- Codificación de variables categóricas.
- Almacenamiento del dataset limpio en formato CSV.

---

## Técnicas de Minería de Datos Aplicadas
Se utilizó la técnica de **clasificación**, aplicando un **Árbol de Decisión** mediante la librería `scikit-learn`.

El modelo fue entrenado con variables como edad, tipo de póliza, número de siniestros, prima anual y años como cliente.

---

## Resultados y Conclusiones
El modelo permite identificar patrones claros en la renovación de pólizas.  
Se observa que los clientes con mayor antigüedad y menor número de siniestros presentan mayor probabilidad de renovar.

La visualización del árbol de decisión facilita la interpretación de los resultados.

---

## Limitaciones y Recomendaciones Futuras
**Limitaciones:**
- El dataset es sintético.
- No se evaluaron métricas de desempeño del modelo.

**Recomendaciones:**
- Utilizar datos reales.
- Probar otros modelos de clasificación.
- Evaluar el modelo con métricas como accuracy o matriz de confusión.
