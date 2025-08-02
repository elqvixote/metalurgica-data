# 🧪 Dataset Sintético – Espectrometría de Aleaciones Aluminio 6065

Este dataset simula el análisis espectrométrico de 50 coladas de aleación de aluminio 6065 realizadas en una planta con dos hornos basculantes. Cada colada es muestreada en tres momentos del proceso (inicio, mitad y final), generando 150 registros en total. Los datos incluyen información de turno, horno, etapa de muestreo y composición elemental.

---

## 🎯 Objetivo

Permitir análisis como:
- Evaluación de homogeneidad composicional a lo largo de la colada
- Comparación de desempeño por turno u horno
- Validación de cumplimiento con especificaciones de la norma
- Visualización de la variabilidad por elemento

---

## 📊 Diccionario de Variables

| Variable         | Tipo       | Unidad | Descripción |
|------------------|------------|--------|-------------|
| id_colada        | Texto      | -      | Código de la colada |
| fecha_muestra    | FechaHora  | -      | Fecha y hora de toma de muestra |
| turno            | Categórica | -      | Turno asignado (A, B o C) |
| horno            | Categórica | -      | Horno utilizado (1 o 2) |
| etapa_muestreo   | Categórica | -      | Etapa de toma de muestra (Inicio, Mitad, Final) |
| %Si              | Numérico   | %peso  | Porcentaje de silicio |
| %Fe              | Numérico   | %peso  | Porcentaje de hierro |
| %Cu              | Numérico   | %peso  | Porcentaje de cobre |
| %Mn              | Numérico   | %peso  | Porcentaje de manganeso |
| %Mg              | Numérico   | %peso  | Porcentaje de magnesio |
| %Cr              | Numérico   | %peso  | Porcentaje de cromo |
| %Zn              | Numérico   | %peso  | Porcentaje de zinc |
| %Ti              | Numérico   | %peso  | Porcentaje de titanio |
| %Al              | Numérico   | %peso  | Porcentaje restante de aluminio |

---

## 🧪 Rango de composición típica de aleación 6065 (según norma)

| Elemento | Rango típico (% en peso)     |
|----------|------------------------------|
| Si       | 0.60 – 0.90                  |
| Fe       | ≤ 0.35                       |
| Cu       | ≤ 0.10                       |
| Mn       | 0.50 – 0.80                  |
| Mg       | 0.80 – 1.2                   |
| Cr       | ≤ 0.05                       |
| Zn       | ≤ 0.15                       |
| Ti       | ≤ 0.10                       |
| Al       | Resto (balance)              |

---

## 🧬 Generación de Datos

Los valores se generaron a partir de medias y desviaciones compatibles con los rangos aceptados para la aleación 6065, simulando variabilidad esperada en procesos reales de fundición.

---

## 📜 Licencia

Este dataset está disponible bajo licencia **Creative Commons Attribution 4.0 (CC BY 4.0)**.

Puedes usarlo, modificarlo y compartirlo citando la fuente:

> Metalúrgica Data – elqvixote, 2025
