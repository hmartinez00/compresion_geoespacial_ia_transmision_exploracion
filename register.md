**Title**: Compresión Geoespacial Basada en Inteligencia Artificial para Reducción de Ancho de Banda en Transmisión de Datos de Exploración

**Description**: El creciente volumen de datos geoespaciales generados por misiones satelitales e instrumentos de exploración remota impone limitaciones críticas en el ancho de banda disponible para transmisión y almacenamiento. Este proyecto desarrolla un marco de compresión geoespacial basado en redes neuronales profundas que combina enfoques supervisados y self-supervised para lograr altas tasas de compresión manteniendo la fidelidad analítica de los datos. La arquitectura propuesta integra módulos específicos para imágenes multiespectrales e hiperespectrales, optimizando el trade-off rate-distortion. Se evalúa tanto con métricas objetivas (PSNR, MS-SSIM, BD-Rate) como mediante tareas downstream relevantes para exploración, tales como clasificación de cobertura terrestre y detección de anomalías. Los resultados demuestran reducciones de bitrate de hasta 60-90% respecto al estándar VTM, preservando características críticas para análisis posterior.

**General Objective**: Desarrollar e implementar un marco de compresión geoespacial basado en inteligencia artificial que reduzca significativamente el ancho de banda requerido en la transmisión de datos de exploración remota sin comprometer su utilidad analítica.

**Specific Objectives**: 
- Revisar el estado del arte en técnicas de compresión convencional y basada en IA aplicadas a datos geoespaciales.
- Diseñar e implementar una arquitectura neuronal híbrida optimizada para imágenes multiespectrales e hiperespectrales.
- Evaluar el rendimiento del modelo mediante métricas rate-distortion y su impacto en tareas downstream de exploración.
- Analizar las implicaciones prácticas para misiones satelitales y proponer mejoras para entornos de transmisión en tiempo real.

**Justification**: El explosivo aumento de datos generados por sensores remotos satelitales supera la capacidad de los enlaces de comunicación actuales, elevando costos operativos y limitando la transmisión en tiempo real. Una compresión eficiente basada en IA permite optimizar el uso del espectro radioeléctrico, reducir costos de almacenamiento y transmisión, y habilitar misiones de exploración más ambiciosas. Desde el punto de vista social y estratégico, facilita el monitoreo ambiental, la gestión de desastres y la soberanía de datos en regiones remotas, contribuyendo al desarrollo sostenible y a la eficiencia en operaciones espaciales.

**Methodology**: Enfoque experimental basado en deep learning para compresión de imágenes. Se emplea un pipeline de codificación neuronal con arquitecturas híbridas (CNN-Transformer), entrenamiento combinado supervisado y self-supervised, y optimización rate-distortion. Se utilizan datasets geoespaciales reales (Sentinel, Landsat, WorldView), métricas BD-Rate y evaluación en tareas downstream. La validación incluye comparación con estándares tradicionales (JPEG2000, VTM) y métodos aprendidos del estado del arte.

**Scope**: Desarrollo y validación de un modelo de compresión neuronal para datos multiespectrales con factor de reducción 60-90% y preservación de utilidad en tareas de exploración (78 caracteres).

**Activities**: 
1. Revisión del estado del arte y definición de requisitos técnicos.
2. Adquisición y preprocesamiento de conjuntos de datos geoespaciales.
3. Diseño, implementación y entrenamiento del modelo de compresión propuesto.
4. Experimentación, evaluación rate-distortion y en tareas downstream.
5. Análisis de resultados, discusión de limitaciones y documentación final.

**Resources**: 
- Datos: Imágenes Sentinel-2/3, Landsat, WorldView y datasets hiperespectrales públicos.
- Hardware: Servidores con GPU de alto rendimiento (NVIDIA A100/H100 o superior).
- Software: Python, PyTorch, bibliotecas de compresión (CompressAI), OpenCV y GDAL.
- Infraestructura: Plataformas de computación en la nube con soporte GPU.

**Limitations**: Alta demanda computacional durante el entrenamiento, posible degradación en escenarios con condiciones atmosféricas extremas o datos muy heterogéneos, dependencia de la disponibilidad de datasets de referencia de alta calidad, y desafíos de generalización entre diferentes sensores y misiones satelitales.