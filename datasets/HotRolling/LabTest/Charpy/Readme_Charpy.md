📄 Dataset: Ensayos Charpy en Bobinas de Acero Laminado (9 meses)
1. Descripción General
Este dataset contiene los resultados de ensayos Charpy realizados a muestras de bobinas de acero laminado, simulando 9 meses de producción continua.
Incluye datos de producción, composición química, características de la muestra y resultados del ensayo, lo que permite análisis estadísticos, control de calidad y estudios de comportamiento de tenacidad a distintas temperaturas.

El modelo de muestreo es:

20 bobinas/día

2 muestras por bobina (inicio y final)

≈ 10,960 registros en total.

2. Estructura del CSV
Archivo: charpy_9meses.csv
Codificación: UTF-8
Separador: , (coma)
Formato: una fila por ensayo.

Columna	Descripción	Ejemplo	Unidad / Valores posibles
Fecha_Producción	Fecha de laminación de la bobina	2024-01-02	AAAA-MM-DD
ID_Bobina	Identificador único de la bobina	20240102-01	texto
Heat_No	Número de colada (heat number)	HN3456	texto
Grado_Acero	Designación del acero	S355MC	S235JR, S355MC, DC01, DC06_IF, DP600
Espesor_mm	Espesor nominal final	3.00	mm
Ancho_mm	Ancho nominal	1250	mm
Peso_kg	Peso aproximado de la bobina	23000	kg
Posición_Muestra	Ubicación en la bobina	Inicio / Final	texto
Orientación	Dirección de la probeta respecto al laminado	L / T	L = Longitudinal, T = Transversal
Tamaño_Probeta	Dimensiones de la probeta Charpy	10x10x55	mm
Tipo_Entalla	Forma de la entalla	V / U	texto
Temp_Ensayo_C	Temperatura de ensayo	-20	°C
Energía_J	Energía absorbida	120.0	Joules
Tipo_Fractura	Clasificación de fractura	Dúctil / Frágil / Mixta	texto
%Shear	% estimado de zona dúctil	65	%
Operador	Nombre del operador del ensayo	Juan	texto
Máquina	ID de máquina de ensayo	MCH-02	texto
Fecha_Calibración	Última calibración de la máquina	2024-04-15	AAAA-MM-DD
Norma	Norma aplicada	ASTM E23	ASTM E23 / ISO 148-1
C_%	% de Carbono	0.08	% peso
Mn_%	% de Manganeso	1.20	% peso
Si_%	% de Silicio	0.25	% peso
P_%	% de Fósforo	0.015	% peso
S_%	% de Azufre	0.010	% peso

3. Notas sobre la simulación
Los valores de composición química están dentro de rangos típicos por grado de acero.

La energía absorbida se calculó considerando:

Grado de acero.

Temperatura de ensayo.

Variabilidad aleatoria simulando dispersión real de resultados.

El %Shear y el tipo de fractura se asignaron de forma coherente con la energía absorbida y la temperatura.

Las fechas de calibración se generaron dentro de los 300 días previos a la fecha de ensayo.

4. Aplicaciones recomendadas
Control estadístico de procesos (SPC) para monitorear la tenacidad.

Análisis de transición dúctil-frágil según temperatura.

Comparación por grado de acero y espesor.

Entrenamiento en análisis de datos en Power BI o Python.

Simulación de informes metalúrgicos y de calidad.

5. Licencia y Uso
Este dataset es ficticio y generado con fines educativos y de demostración.
Puede ser utilizado libremente para análisis, pruebas de software y presentaciones técnicas.

