# Repositorio de Proyectos - Alan L. Pérez

¡Bienvenidos a mi repositorio! Aquí encontrarás una selección de proyectos y dashboards que he desarrollado a lo largo de mi carrera. Aunque mi trabajo profesional es confidencial, he incluido una serie de proyectos representativos que realicé como pilotos, plantillas y durante diversos cursos. Estos proyectos ilustran mis habilidades en análisis y procesamiento de datos, automatización, modelos de Machine Learning, así como en la creación de tableros y visualización de datos.

## Tabla de Contenidos

1. [Predicción de Vencimiento de Facturas - Modelo de Machine Learning](#predicción-de-vencimiento-de-facturas---modelo-de-machine-learning)
2. [Segmentación de Clientes - Dashboard](#segmentación-de-clientes---dashboard)
3. [Netflix Titles - Dashboard](#netflix-titles---dashboard)
4. [Presupuesto Personal - Dashboard](#presupuesto-personal---dashboard)
5. [Dizteku - Dashboard](#Dizteku---dashboard)

---

## Predicción de Vencimiento de Facturas - Machine Learning.
Este proyecto se centra en predecir el vencimiento de facturas para optimizar la gestión de cobros.

### Etapas del Proyecto

1. **Origen de Datos:** Utilizamos datos históricos de facturación, que incluyen fechas de vencimiento y fechas de pago (clear date) para cada factura.

2. **Limpieza:** Se eliminaron valores nulos y se normalizaron las fechas, convirtiéndolas en formato día, mes y año. Además, se realizó la conversión numérica de las columnas categóricas para su adecuada integración en el modelo.

3. **Análisis:** Identificamos los valores que tenían mayor impacto en la variable dependiente, evaluando la influencia de diferentes características en los vencimientos de las facturas.

4. **Entrenamiento:** Evaluamos varios modelos, incluyendo Regresión Lineal, Support Vector Regression (SVR), Árboles de Decisión, Random Forest y XGB Regressor, para encontrar el mejor ajuste para la predicción de vencimientos.


### Resultados de Modelos

| Algoritmo                  | MSE Scores          | R² Score (%) |
|----------------------------|---------------------|--------------|
| LinearRegression           | 3.195110e+11        | 32.41%       |
| Support Vector Regression  | 4.767176e+11        | -0.84%       |
| Decision Tree Regression   | 1.970601e+11        | 58.31%       |
| Random Forest Regression   | 1.214346e+11        | 74.31%       |
| XGB Regressor              | 1.472704e+11        | 68.85%       |

El modelo Random Forest mostró el mejor rendimiento.

Este es el modelo inicial, desarrollado como piloto, que utilizó un conjunto de datos similar al caso de uso real, por lo que puedo compartirlo. Este modelo logró clasificar con mucha precisión las facturas. Posteriormente, en colaboración con científicos de datos, perfeccionamos el modelo para mejorar aún más su precisión y aplicabilidad en escenarios reales. Podrán ver la totalidad del proyecto piloto en los archivos de este repertorio.

## Estrategia de Segmentación
Con base en los resultados, se pueden aplicar las siguientes estrategias:

Segmentación por Riesgo: Clasificar las facturas en categorías de riesgo (bajo, medio, alto) para priorizar la gestión.
Perfilado de Clientes: Identificar características comunes en clientes con alto riesgo para ajustar estrategias de cobro.
Optimización de Cobranza: Implementar tácticas personalizadas según el riesgo de vencimiento, mejorando la eficiencia en la recuperación de pagos.
Actualmente, estoy trabajando en un dashboard operativo que permtia aplicar estas estrategias con una actualización diaria de las facturas/Clientes.

---

## Netflix Titles - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/20bd6be0-4695-4f47-a722-c1ceafe34b0b" alt="Netflix Titles Dashboard 3" width="775"/></td>
    <td><img src="https://github.com/user-attachments/assets/26edfaed-a5ca-4ae4-a2c0-04c12d5786b4" alt="Netflix Titles Dashboard 2" width="775"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/4d037cb5-eea3-43e3-8d72-a5e714e71a4d" alt="Netflix Titles Dashboard 1" width="775"/></td>
    <td><img src="https://github.com/user-attachments/assets/091c174a-54bc-47b6-a730-f968084ef058" alt="Netflix Titles Dashboard 4" width="775"/></td>
  </tr>
</table>

**Descripción:**
El dashboard de Netflix Titles proporciona una exploración detallada del dataset, destacando información relevante a través de gráficos diversos como mapas y WordClouds. Es una herramienta útil para entender patrones y tendencias en los datos de películas y series.

---

## Segmentación de Clientes - Dashboard


<table>
  <tr>
<td><img src="https://github.com/user-attachments/assets/5e41fe42-880c-44df-ac9b-daa093a67e1a" alt="Custom_seg" width="1550"/></td>
  </tr>
</table>

**Descripción:**
Este dashboard de Segmentación de Clientes permite analizar y clasificar a los clientes en diferentes segmentos basados en clasificación RFM. Aplica filtros simples y funciona como una versión piloto para desarrollos futuros.


## Presupuesto Personal - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/aaac25a6-4a4b-4bba-8963-d9d6a237be68" alt="Presupuesto Personal Dashboard" width="1550" height="auto"/></td>
  </tr>
</table>

**Descripción:**
Este dashboard de Presupuesto Personal es una plantilla de Excel diseñada para el seguimiento y gestión de gastos personales. Ofrece una visión clara de las finanzas personales y ayuda en la planificación del presupuesto.

---

## Dizteku - Dashboard

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/36933584-7ea5-4108-9a2d-c42b063cdfb9" alt="Netzuk Dashboard" width="1550"/></td>
  </tr>
</table>

**Descripción:**
El dashboard Dizteku incluye una visión integral de los ingresos, gastos, márgenes y beneficios. Fue creado como un proyecto de curso para demostrar habilidades en la creación de dashboards funcionales. Aplica filtros simples y funciona como una versión piloto para desarrollos futuros.

---
