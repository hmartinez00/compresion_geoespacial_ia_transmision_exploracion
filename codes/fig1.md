Procedo a aplicar el protocolo de validación técnica integrando la directriz de **texto incrustado explícito**.

---

### **FASE 1: Mapeo de Entidades (Análisis)**

* **Dominio:** Arquitectura de Comunicaciones Aeroespaciales / Compresión de Datos de Observación de la Tierra (EO).
* **Componentes clave del LaTeX:** Representación de la brecha tecnológica y operativa entre el volumen de datos generados por sensores satelitales (misiones hiperespectrales y multiespectrales como Sentinel-2 y Landsat Next que exceden los 5-10 TB diarios) y la capacidad real de los enlaces de bajada (*Downlink*) que actúan como cuello de botella (100-300 Mbps). El periodo analizado abarca de 2015 a 2025.
* **Nivel de Abstracción:** Gráfico Estadístico-Analítico de Tendencias (*Comparative Trend Chart*).

---

### **FASE 2: Auditoría y Reporte de Hallazgos Críticos**

1. **Contraste de Coherencia:** El prompt base define el gráfico de líneas y la brecha correctamente. Siguiendo la regla de texto incrustado, las leyendas conceptuales y ejes vacíos deben sustituirse por variables, unidades y nombres de misión explícitos para alinearse con los datos de la *Tabla 1*.
2. **LISTA DE DISCREPANCIAS (Explícita):**
* **Inclusión de Etiquetas de Eje Explícitas:** El eje horizontal debe rotularse con el texto **"YEAR"** y marcas temporales continuas. El eje vertical izquierdo debe rotularse como **"DATA VOLUME / BANDWIDTH"**.
* **Inclusión de Nombres de Misión y Leyendas:** Para reflejar los datos del manuscrito, la línea superior de volumen de datos debe incluir anotaciones de texto explícitas para **"SENTINEL-2"**, **"LANDSAT NEXT"** e **"HYPERSPECTRAL MISSIONS"** en sus respectivos puntos de la curva.
* **Rotulación de Curvas y Brecha:** Las curvas deben llevar etiquetas integradas: **"GENERATED DATA (TB/day)"** en la curva ascendente azul cobalto, y **"DOWNLINK CAPACITY"** en la línea plana gris. El área intermedia debe etiquetarse explícitamente como **"TRANSMISSION GAP"**.


3. **Control de Estilo:** Estándar IEEE. Gráfico en 2D plano, sin degradados tridimensionales. Uso estricto de Azul Cobalto (`#0047AB`) para la curva de generación de datos (volumen crítico a resolver) y Gris Técnico (`#4A4A4A`) para la capacidad física de transmisión. Tipografía limpia Sans-Serif.

---

### **FASE 3: Explicación y Justificación de Pre-ejecución**

#### 1. Disposición Espacial y Sentido de los Flujos

La figura se estructurará como un gráfico de coordenadas cartesianas bidimensional en formato horizontal (*Landscape*):

* **Ejes:** Eje X horizontal graduado de izquierda a derecha con las marcas numéricas **"2015"**, **"2018"**, **"2022"**, y **"2025"**. Eje Y vertical a la izquierda con marcas indicativas de volumen.
* **Curva Superior (Azul Cobalto):** Comienza moderada en 2015 y asciende de forma exponencial hacia el extremo superior derecho. A lo largo de su trayectoria se sitúan las etiquetas de los satélites en orden de volumen. Al final de la curva se lee **"GENERATED DATA (TB/day)"**.
* **Curva Inferior (Gris Técnico):** Una línea recta con una pendiente de crecimiento muy baja o casi plana que corre por la parte inferior del gráfico, rotulada al final como **"DOWNLINK CAPACITY"**.
* **Área Intermedia:** Un entramado de líneas finas o patrón geométrico plano une ambas líneas, rotulado en el centro con el texto **"TRANSMISSION GAP"**.

#### 2. Justificación Técnico-Aeroespacial

Esta composición representa fielmente la problemática del artículo. Permite correlacionar visualmente el estancamiento de la infraestructura de telecomunicaciones frente al crecimiento exponencial de los sensores remotos de las misiones espaciales. Justifica cuantitativamente la necesidad de implementar el marco de compresión con IA propuesto para cerrar la brecha de transmisión sin pérdida de fidelidad analítica.

#### 3. ADVERTENCIAS PARA EL USUARIO

* **Renderizado de Unidades y Siglas:** Al incluir múltiples términos técnicos y acrónimos ("TB/day", "GAP"), el motor de IA requiere instrucciones de aislamiento para evitar caracteres erróneos. He optimizado las cadenas en inglés para asegurar una tipografía compacta y limpia bajo norma de publicación.

---

### **FASE 4: Ejecución Silenciosa**

Tengo definida la estructura analítica y las marcas de texto para `fig1.png`. Por favor, facilítame tu confirmación para proceder con la entrega de los prompts optimizados.


```text
Gráfico analítico bidimensional de líneas en orientación landscape, diagrama de tendencias técnicas para publicación científica. Diseño plano, minimalista, fondo blanco puro, paleta de colores estricta en azul cobalto (#0047AB) para los datos de misiones y gris técnico (#4A4A4A) para la capacidad física, con líneas finas en negro neutro. Sin sombras, sin gradientes, sin relieve tridimensional. Toda la composición incluye texto impreso de forma nítida y perfectamente legible en tipografía Sans-Serif limpia. El eje horizontal está rotulado como "YEAR" con marcas para "2015", "2018", "2022" y "2025". El eje vertical izquierdo está rotulado como "DATA VOLUME / BANDWIDTH". Una línea azul cobalto (#0047AB) asciende pronunciadamente de izquierda a derecha representando el crecimiento de datos, con marcas y etiquetas que indican "SENTINEL-2", "LANDSAT NEXT" e "HYPERSPECTRAL MISSIONS" en sus puntos respectivos, finalizando con el texto "GENERATED DATA (TB/day)". Una segunda línea en gris técnico (#4A4A4A) corre casi plana por la parte inferior, rotulada al final como "DOWNLINK CAPACITY". El espacio entre ambas líneas está cubierto por un patrón plano de líneas finas y lleva escrito en el centro el texto "TRANSMISSION GAP". Estilo riguroso de la norma IEEE, alta precisión técnica.

```

```text
2D analytical line graph in landscape orientation, technical trend schematic for scientific publication. Flat design, minimalist, pure white background, strict color palette of cobalt blue (#0047AB) for mission data and technical gray (#4A4A4A) for physical capacity, with crisp neutral black fine lines. No shadows, no gradients, no 3D reflections. The entire composition features sharp, perfectly legible printed text in a clean Sans-Serif typography. The horizontal axis is labeled "YEAR" with tick marks for "2015", "2018", "2022", and "2025". The left vertical axis is labeled "DATA VOLUME / BANDWIDTH". A steep cobalt blue (#0047AB) line curves sharply upward from left to right representing data growth, with text labels reading "SENTINEL-2", "LANDSAT NEXT", and "HYPERSPECTRAL MISSIONS" positioned at their respective points, ending with the text "GENERATED DATA (TB/day)". A second line in technical gray (#4A4A4A) runs nearly flat along the bottom, labeled at its end as "DOWNLINK CAPACITY". The space between both lines is filled with a flat fine-line pattern and clearly displays the text "TRANSMISSION GAP" in the center. Pristine IEEE publication style, high technical accuracy.

```