# 11000_Medicamentos
Análisis exploratorio y visualización de datos de 11,000 medicamentos, incluyendo su composición, usos, fabricantes y reseñas de usuarios. Proyecto enfocado en obtener patrones clave en la industria farmacéutica.

1. ¿Cuáles son las enfermedades para las que existen más medicamentos y cuáles tienen menos opciones de tratamiento?

Objetivo: Identificar las enfermedades con mayor y menor cantidad de medicamentos disponibles, lo que puede ser útil para análisis de mercado y para entender dónde hay más o menos desarrollo farmacéutico. 
<br>Análisis sugerido: Agrupar los medicamentos por la columna Uses (que indica la enfermedad tratada) y contar cuántos medicamentos hay por categoría.

2. ¿Qué componentes son más comunes en la composición de los medicamentos?

Objetivo: Estudiar los componentes (sales) más utilizados en la formulación de los medicamentos para entender cuáles son los más comunes en la industria.
<br>Análisis sugerido: Agrupar por la columna Salt Composition y contar las frecuencias de cada componente.

3. ¿Qué relación hay entre los componentes de los medicamentos y las enfermedades que tratan?

Objetivo: Identificar si ciertos componentes (sales) se utilizan predominantemente para ciertas enfermedades. Esto puede ser útil para investigaciones de desarrollo farmacéutico y para analizar si hay componentes "clave" en determinadas áreas terapéuticas.
<br>Análisis sugerido: Crear una tabla cruzada (cross-tabulation) o un gráfico que muestre qué componentes están asociados con qué enfermedades.

4. ¿Cuáles son los fabricantes con mayor presencia en el mercado?

Objetivo: Identificar qué fabricantes producen más medicamentos y, por lo tanto, tienen una mayor participación en el mercado.
<br>Análisis sugerido: Contar cuántos medicamentos tiene cada fabricante y mostrar los más grandes.

5. ¿Cuál es la distribución de reseñas excelentes, promedio y malas, y cuáles son los medicamentos y fabricantes mejor y peor valorados?

Objetivo: Resumir en un solo punto el análisis de las reseñas, identificando tanto las distribuciones generales como los mejores y peores medicamentos y fabricantes en términos de satisfacción del cliente.
<br>Análisis sugerido: Calcular la distribución de reseñas y luego identificar los medicamentos y fabricantes con la mayor proporción de reseñas excelentes y malas.

6. ¿Cómo se agrupan los medicamentos según las enfermedades graves y leves que tratan?

Objetivo: Realizar una clusterización de los medicamentos según la gravedad de las enfermedades que tratan, para identificar patrones en su composición, fabricante o reseñas.