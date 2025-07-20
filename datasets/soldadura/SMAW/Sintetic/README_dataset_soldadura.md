# 🔧 Dataset Sintético – Soldadura Naval (SMAW)

Este dataset simula 300 registros de soldaduras en estructuras navales, bajo el proceso SMAW (Shielded Metal Arc Welding), incluyendo parámetros de proceso, defectos y propiedades mecánicas básicas. Fue generado para fines educativos y de análisis de datos aplicados a la ingeniería metalúrgica.

---

## 🎯 Objetivo

Permitir análisis como:
- Clasificación de defectos por tipo de unión o posición
- Correlación entre variables de proceso y calidad (dureza, defectos)
- Visualización de distribución de defectos y desempeño por operador
- Entrenamiento de modelos de machine learning sobre calidad de soldadura

---

## 📊 Diccionario de Variables

| Variable                   | Tipo       | Unidad   | Descripción |
|----------------------------|------------|----------|-------------|
| id_soldadura              | Texto      | -        | Código único de la junta soldada |
| espesor_chapa_mm          | Numérico   | mm       | Espesor del material base |
| corriente_A               | Numérico   | A        | Corriente utilizada en el arco |
| voltaje_V                 | Numérico   | V        | Voltaje del proceso |
| velocidad_avance_mm_s     | Numérico   | mm/s     | Velocidad de avance de la soldadura |
| tipo_union                | Categórica | -        | Tipo de unión: Bisel, Solape o Tope |
| posicion_soldadura        | Categórica | -        | Posición de ejecución: Plana, Horizontal o Vertical |
| operador                  | Texto      | -        | Identificación del operador (alias) |
| tipo_defecto              | Categórica | -        | Tipo de defecto detectado: Porosidad, Fisura, etc. |
| dureza_zac_HRB            | Numérico   | HRB      | Dureza en la Zona Afectada por el Calor (ZAC) |

---

## 🧬 Generación de Datos

Los datos fueron generados de forma sintética, utilizando distribuciones realistas para cada variable, con una probabilidad predominante de soldaduras sin defectos. La dureza fue simulada con una distribución normal centrada en HRB 85.

---

## 📜 Licencia

Este dataset está disponible bajo licencia **Creative Commons Attribution 4.0 (CC BY 4.0)**.

Puedes usar, modificar y distribuir el contenido citando la fuente:

> Metalúrgica Data – Beto, 2025
