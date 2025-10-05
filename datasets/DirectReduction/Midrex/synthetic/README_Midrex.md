# 🧱 Dataset: Operación del Reactor Midrex-Alpha

## 📘 Descripción general
Este conjunto de datos contiene **registros horarios durante dos semanas** de operación simulada de un reactor de **reducción directa tipo Midrex**, utilizado para producir **Hierro de Reducción Directa (DRI)** a partir de pellas de mineral de hierro.

El proceso **Midrex** utiliza **gas natural reformado** rico en monóxido de carbono (CO) e hidrógeno (H₂) como agente reductor.  
El gas caliente fluye **en contracorriente** con respecto a las pellas, que descienden gradualmente a través del reactor.  
Durante el proceso, el oxígeno del óxido de hierro es eliminado, formando hierro metálico sólido sin alcanzar su punto de fusión.  

Este dataset representa datos sintéticos de la planta ficticia **MIDREX-Alpha**, diseñados con fines de investigación, docencia y análisis de datos industriales.

---

## 🧩 Estructura de datos

| Columna | Descripción | Unidad / Rango típico |
|----------|--------------|-----------------------|
| `FechaHora` | Marca temporal de registro | cada hora |
| `Temperatura_Gas_Base` | Temperatura del gas reductor a la entrada inferior del reactor | 850–950 °C |
| `Temperatura_Gas_Tope` | Temperatura del gas a la salida superior | 300–400 °C |
| `Presion_Reactor` | Presión interna de operación | 1.5–2.0 atm |
| `Flujo_Gas_Reduc` | Flujo volumétrico de gas reductor | 18 000–22 000 Nm³/h |
| `CO_Base` | Porcentaje de CO en el gas de entrada | 35–45 % |
| `H2_Base` | Porcentaje de H₂ en el gas de entrada | 50–60 % |
| `CO2_Base` | Porcentaje de CO₂ en el gas de entrada | 2–5 % |
| `CH4_Base` | Porcentaje de CH₄ residual en el gas de entrada | 1–3 % |
| `CO_Tope` | Porcentaje de CO en el gas de salida | 5–10 % |
| `H2_Tope` | Porcentaje de H₂ en el gas de salida | 15–25 % |
| `CO2_Tope` | Porcentaje de CO₂ en el gas de salida | 20–30 % |
| `H2O_Tope` | Porcentaje de H₂O (vapor) en el gas de salida | 5–10 % |
| `Grado_Metalizacion_Entrada` | Porcentaje de hierro metálico en las pellas de alimentación | 0–5 % |
| `Grado_Metalizacion_Salida` | Porcentaje de hierro metálico en las pellas al salir del reactor | 90–96 % |
| `Temperatura_Pellas_Tope` | Temperatura de pellas a la entrada | 25–100 °C |
| `Temperatura_Pellas_Salida` | Temperatura de pellas al descargarse | 600–700 °C |
| `Consumo_Gas_Especifico` | Consumo de gas por tonelada de DRI producido | 400–450 Nm³/t |
| `Produccion_DRI` | Tasa de producción de DRI | 100–120 t/h |
| `Eficiencia_Reduccion` | Eficiencia teórica del uso de CO y H₂, calculada como (1 – (CO_tope + H₂_tope) / (CO_base + H₂_base)) × 100 | % |

---

## ⚙️ Aplicaciones recomendadas
- Análisis de correlaciones entre la composición del gas y el grado de metalización.  
- Simulación del control de proceso y eficiencia térmica.  
- Entrenamiento de modelos predictivos de rendimiento en reducción directa.  
- Visualización de estabilidad operacional (temperatura, presión, flujo, etc.).

---

## 📄 Archivo incluido
- `MIDREX-Alpha_operacion.csv` → 336 registros horarios (14 días de operación).

---

## 🧠 Referencias
- Midrex Technologies, Inc. — *The World’s Leading Direct Reduction Technology.*
- Instituto Latinoamericano del Fierro y el Acero (ILAFA) — *Procesos de Reducción Directa.*
- Datos generados de manera sintética por el proyecto **[Metalúrgica Data](https://github.com/elqvixote/metalurgica-data)** bajo licencia **CC BY 4.0**.

---

## 🪪 Licencia
**Creative Commons Attribution 4.0 International (CC BY 4.0)**  
Puedes copiar, modificar, distribuir y utilizar el dataset, incluso con fines comerciales, siem
