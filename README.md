# 📊 Análisis de la estructura tributaria de Venezuela (2008–2017)

Este documento resume el análisis exploratorio de los ingresos tributarios de Venezuela entre 2008 y 2017, utilizando datos de la OECD. El objetivo es ofrecer a los stakeholders una visión clara, modular y accionable sobre la evolución del sistema fiscal.

---

## 🎯 Objetivo del análisis
- Comprender cómo han evolucionado los ingresos tributarios totales.
- Identificar qué tipos de impuestos han sido más relevantes cada año.
- Detectar cambios estructurales en la composición tributaria.

---

## 🧭 Flujo de análisis

### 1. Carga y limpieza de datos
- Se seleccionaron las columnas clave: TIME_PERIOD, STANDARD_REVENUE, OBS_VALUE.
- Se eliminaron valores nulos para asegurar consistencia.

### 2. Evolución de ingresos totales
- Se agruparon los ingresos por año (TIME_PERIOD) y se sumaron.
- **Resultado**: gráfico de líneas que muestra el crecimiento abrupto hacia 2016–2017.
- **Interpretación**: este aumento puede reflejar inflación, cambios contables o reformas fiscales.

### 3. Top 5 impuestos por año
- Para cada año, se identificaron las cinco categorías de impuestos con mayores ingresos.
- **Resultado**: gráfico de barras que muestra qué impuestos dominaron en cada periodo.
- **Ejemplo**: en 2008, T_1000 (impuestos sobre la renta) fue dominante; en 2017, T_6000 y T_6200 (otros impuestos) tomaron protagonismo.

### 4. Estructura tributaria por año
- Se calculó la proporción de cada impuesto respecto al total anual.
- **Resultado**: gráfico de barras apiladas que muestra cómo se distribuyen los ingresos por tipo de impuesto cada año.
- **Insight**: la estructura tributaria se volvió más concentrada en categorías residuales hacia el final del periodo.

---

## 🔍 Principales hallazgos
- **Diversificación inicial**: en los primeros años, los ingresos estaban distribuidos entre varios tipos de impuestos.
- **Concentración final**: hacia 2016–2017, los ingresos se concentran en pocas categorías, especialmente T_6000 y T_6200.
- **Posibles causas**: inflación, reclasificación contable, cambios en la política fiscal.

---

## 🗣️ Recomendaciones para stakeholders
- **Validar calidad de datos**: revisar si los aumentos reflejan ingresos reales o efectos contables.
- **Monitorear dependencia fiscal**: evitar que el sistema dependa excesivamente de categorías no recurrentes.
- **Comparar con otros países**: evaluar si la estructura tributaria venezolana sigue patrones regionales o se desvía significativamente.

---

## 📌 Conclusión
Este análisis ofrece una base sólida para entender la evolución fiscal de Venezuela. Los gráficos y proporciones permiten visualizar cambios estructurales y tomar decisiones informadas sobre política tributaria, planificación financiera y evaluación de riesgos.

---

**Fuente de datos**: OECD.CTP.TPS, DSD_REV_LAC@DF_REVVEN
