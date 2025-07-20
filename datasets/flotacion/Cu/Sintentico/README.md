# 🧪 Dataset Sintético – Flotación de Cobre

Este dataset simula 500 registros de un proceso de flotación de cobre en una planta industrial. Los datos fueron generados con valores técnicos realistas y aleatoriedad controlada, para fines educativos, de visualización y práctica en ciencia de datos aplicada a la metalurgia.

---

## 🎯 Objetivo

Permitir a estudiantes, ingenieros y analistas practicar:
- Visualización de datos de proceso
- Análisis de tendencias por turno o variable
- Modelos de regresión o clasificación
- Identificación de outliers o condiciones subóptimas

---

## 📊 Diccionario de Variables

| Variable                      | Tipo      | Unidad   | Descripción |
|-------------------------------|-----------|----------|-------------|
| fecha_operacion              | Fecha     | -        | Fecha de ejecución de la corrida |
| turno                        | Categórica| -        | Grupo de trabajo en rotación (A, B, C, D) |
| %Cu_feed                     | Numérico  | %        | Ley de cobre en la alimentación |
| pH                           | Numérico  | -        | pH de la pulpa en celdas de flotación |
| densidad_pulpa_g_cm3         | Numérico  | g/cm³    | Densidad de pulpa procesada |
| colector_dosificado_g_t      | Numérico  | g/t      | Dosis de colector (ej. xantato) |
| espumante_dosificado_g_t     | Numérico  | g/t      | Dosis de espumante (ej. MIBC) |
| velocidad_agitacion_rpm      | Numérico  | rpm      | Velocidad de agitación del sistema |
| %Cu_concentrado              | Numérico  | %        | Ley de cobre en el concentrado |
| %Cu_relave                   | Numérico  | %        | Ley de cobre en el relave |
| recuperacion_cu_%            | Numérico  | %        | Recuperación metalúrgica aproximada |

---

## 🧬 Generación de Datos

Este dataset fue generado de forma sintética utilizando distribuciones normales y relaciones técnicas entre variables. La fórmula de recuperación es aproximada y no representa resultados reales de planta.

---

## 📜 Licencia

Este archivo está disponible bajo la licencia **Creative Commons Attribution 4.0 (CC BY 4.0)**.

Puedes usar, modificar y compartir el contenido citando la fuente:

> Metalúrgica Data – elqvixote, 2025
