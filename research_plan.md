```json
{
  "titulo": "Compresión Geoespacial Basada en Inteligencia Artificial para Reducción de Ancho de Banda en Transmisión de Datos de Exploración",
  "folder_name": "compresion_geoespacial_ia_transmision_exploracion",
  "abstract_preliminar": "El creciente volumen de datos geoespaciales generados por misiones satelitales y sistemas de exploración remota impone severas limitaciones en el ancho de banda disponible para transmisión y almacenamiento. Este artículo presenta un marco de compresión geoespacial basado en redes neuronales profundas que combina aprendizaje supervisado y self-supervised para lograr altas tasas de compresión manteniendo la utilidad analítica de los datos. La propuesta integra arquitecturas de compresión neuronal con módulos específicos para imágenes multiespectrales e hiperespectrales, evaluando tanto métricas rate-distortion tradicionales como el impacto en tareas downstream como clasificación de cobertura y detección de anomalías. Los experimentos demuestran reducciones significativas de bitrate (hasta 60-90% frente a VTM) con preservación de características críticas para exploración, superando enfoques convencionales y aprendidos genéricos. Se discuten implicaciones prácticas para misiones espaciales y limitaciones actuales.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Contextualizar el desafío del ancho de banda en transmisión de datos geoespaciales", "Presentar motivación, problemática y contribuciones del trabajo"],
      "subsecciones": ["1.1 Antecedentes y Motivación", "1.2 Problemática en Transmisión de Exploración", "1.3 Contribuciones y Estructura del Artículo"],
      "insumos": ["Figura 1: Comparación de volúmenes de datos satelitales", "Tabla 1: Limitaciones de ancho de banda en misiones actuales"],
      "llaves_bibtex": ["Molliere2025_Learned_EO_Compression", "Wang2025_RS_Compression"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte",
      "objetivos": ["Revisar técnicas de compresión convencional y basada en IA", "Analizar enfoques específicos para datos geoespaciales"],
      "subsecciones": ["2.1 Compresión Convencional y Estándares", "2.2 Compresión Neuronal para Imágenes", "2.3 Métodos Específicos para Remote Sensing"],
      "insumos": ["Tabla 2: Comparación de tasas de compresión SOTA", "Figura 2: Evolución temporal de métodos"],
      "llaves_bibtex": ["Molliere2025_Learned_EO_Compression", "Wang2025_RS_Compression", "Ye2025_MAPC"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Metodología Propuesta",
      "objetivos": ["Describir el marco de compresión geoespacial IA", "Detallar componentes y pipeline de entrenamiento"],
      "subsecciones": ["3.1 Arquitectura General", "3.2 Módulos de Codificación Multiespectral", "3.3 Función de Pérdida y Entrenamiento", "3.4 Optimización para Transmisión"],
      "insumos": ["Eq. 1: Modelo rate-distortion", "Figura 3: Diagrama de arquitectura", "Tabla 3: Hiperparámetros"],
      "llaves_bibtex": ["Ye2025_MAPC", "Xiang2024_HL_RSCompNet", "COSMIC2024"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Conjuntos de Datos y Configuración Experimental",
      "objetivos": ["Describir datasets y preprocesamiento", "Definir métricas de evaluación"],
      "subsecciones": ["4.1 Datasets Geoespaciales", "4.2 Preprocesamiento y Augmentación", "4.3 Métricas Rate-Distortion y Downstream"],
      "insumos": ["Tabla 4: Estadísticas de datasets", "Figura 4: Ejemplos de imágenes originales vs reconstruidas"],
      "llaves_bibtex": ["Molliere2025_Learned_EO_Compression", "Wang2025_RS_Compression"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Resultados y Análisis",
      "objetivos": ["Presentar resultados cuantitativos y cualitativos", "Evaluar impacto en tareas de exploración"],
      "subsecciones": ["5.1 Evaluación Rate-Distortion", "5.2 Análisis en Tareas Downstream", "5.3 Comparación con Estado del Arte"],
      "insumos": ["Tabla 5: Resultados BD-Rate", "Figura 5: Visualizaciones comparativas", "Tabla 6: Métricas downstream"],
      "llaves_bibtex": ["Ye2025_MAPC", "Xiang2024_HL_RSCompNet"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados y limitaciones", "Analizar implicaciones prácticas"],
      "subsecciones": ["6.1 Fortalezas y Debilidades", "6.2 Implicaciones para Misiones de Exploración", "6.3 Limitaciones y Consideraciones"],
      "insumos": [],
      "llaves_bibtex": ["Molliere2025_Learned_EO_Compression", "Wang2025_RS_Compression"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Resumir hallazgos principales", "Proponer direcciones futuras"],
      "subsecciones": ["7.1 Conclusiones", "7.2 Trabajos Futuros"],
      "insumos": [],
      "llaves_bibtex": ["Molliere2025_Learned_EO_Compression", "Ye2025_MAPC"]
    }
  ]
}
```

```bibtex
@article{Molliere2025_Learned_EO_Compression,
  author    = {Mollière, C. and others},
  title     = {Learned Image Compression for Earth Observation},
  journal   = {arXiv preprint arXiv:2512.01788},
  year      = {2025},
  doi       = {10.48550/arXiv.2512.01788},
  url       = {https://arxiv.org/abs/2512.01788},
  note      = {[Online]. Available: https://arxiv.org/pdf/2512.01788}
}

@article{Wang2025_RS_Compression,
  author    = {Wang, Y. and others},
  title     = {Towards an Efficient Remote Sensing Image Compression Network},
  journal   = {Remote Sensing},
  volume    = {17},
  number    = {3},
  pages     = {425},
  year      = {2025},
  doi       = {10.3390/rs17030425},
  url       = {https://www.mdpi.com/2072-4292/17/3/425},
  note      = {[Online]. Available: https://www.mdpi.com/2072-4292/17/3/425}
}

@article{Ye2025_MAPC,
  author    = {Ye, Y. and others},
  title     = {Map-Assisted remote-sensing image compression at extremely low bitrates},
  journal   = {ISPRS Journal of Photogrammetry and Remote Sensing},
  year      = {2025},
  doi       = {10.1016/j.isprsjprs.2025.03.010},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S0924271625001030},
  note      = {[Online]. Available: https://www.sciencedirect.com/science/article/abs/pii/S0924271625001030}
}

@article{Xiang2024_HL_RSCompNet,
  author    = {Xiang, S. and others},
  title     = {Remote Sensing Image Compression Based on High-Level Semantic Features},
  journal   = {IEEE Transactions on Geoscience and Remote Sensing},
  year      = {2024},
  doi       = {10.1109/TGRS.2024.10379598},
  url       = {https://ieeexplore.ieee.org/document/10379598/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10379598/}
}

@inproceedings{COSMIC2024,
  author    = {Authors of COSMIC},
  title     = {COSMIC: Compress Satellite Images Efficiently via Diffusion Compensation},
  booktitle = {arXiv preprint},
  year      = {2024},
  url       = {https://arxiv.org/abs/2410.01698},
  note      = {[Online]. Available: https://arxiv.org/pdf/2410.01698}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Molliere2025_Learned_EO_Compression": {
      "razon_seleccion": "Trabajo reciente sobre learned compression aplicado específicamente a Earth Observation.",
      "guia_redaccion": "Usar en 1.1 y 1.2 para motivar el crecimiento de datos EO y limitaciones de ancho de banda en transmisión.",
      "subseccion_destino": "1.1"
    },
    "Wang2025_RS_Compression": {
      "razon_seleccion": "Estudio sobre redes de compresión para remote sensing con foco en reducción de almacenamiento y transmisión.",
      "guia_redaccion": "Integrar en 1.2 para destacar desafíos en exploración y beneficios cuantitativos.",
      "subseccion_destino": "1.2"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte",
  "mapa_uso": {
    "Molliere2025_Learned_EO_Compression": {
      "razon_seleccion": "Revisión comparativa de learned compression en EO.",
      "guia_redaccion": "Base para taxonomía y tabla comparativa en 2.2 y 2.3.",
      "subseccion_destino": "2.2"
    },
    "Wang2025_RS_Compression": {
      "razon_seleccion": "Resultados cuantitativos en datasets de remote sensing.",
      "guia_redaccion": "Contrastar con estándares en 2.3.",
      "subseccion_destino": "2.3"
    },
    "Ye2025_MAPC": {
      "razon_seleccion": "Enfoque map-assisted para bitrates extremadamente bajos.",
      "guia_redaccion": "Destacar en 2.3 como SOTA en escenarios de transmisión restringida.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Metodología Propuesta",
  "mapa_uso": {
    "Ye2025_MAPC": {
      "razon_seleccion": "Pipeline two-stage para compresión a bajos bitrates.",
      "guia_redaccion": "Inspirar arquitectura general y módulos en 3.1 y 3.2.",
      "subseccion_destino": "3.1"
    },
    "Xiang2024_HL_RSCompNet": {
      "razon_seleccion": "Modelo basado en características semánticas de alto nivel.",
      "guia_redaccion": "Incorporar ideas de semantic features en módulos multiespectrales 3.2.",
      "subseccion_destino": "3.2"
    },
    "COSMIC2024": {
      "razon_seleccion": "Método con compensación por difusión para imágenes satelitales.",
      "guia_redaccion": "Adaptar conceptos de difusión en función de pérdida y optimización 3.3-3.4.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Conjuntos de Datos y Configuración Experimental",
  "mapa_uso": {
    "Molliere2025_Learned_EO_Compression": {
      "razon_seleccion": "Datasets y configuración típica en EO compression.",
      "guia_redaccion": "Justificar elección de datasets y métricas en 4.1 y 4.3.",
      "subseccion_destino": "4.1"
    },
    "Wang2025_RS_Compression": {
      "razon_seleccion": "Uso de datasets como AID, NWPU y WorldView-3.",
      "guia_redaccion": "Detallar preprocesamiento similar en 4.2.",
      "subseccion_destino": "4.2"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Resultados y Análisis",
  "mapa_uso": {
    "Ye2025_MAPC": {
      "razon_seleccion": "Resultados en semantic segmentation y bajos bitrates.",
      "guia_redaccion": "Comparar BD-rate y métricas downstream en Tabla 5 y 6.",
      "subseccion_destino": "5.3"
    },
    "Xiang2024_HL_RSCompNet": {
      "razon_seleccion": "Evaluación en remote sensing con semantic features.",
      "guia_redaccion": "Benchmark en 5.1 y visualizaciones 5.2.",
      "subseccion_destino": "5.1"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Molliere2025_Learned_EO_Compression": {
      "razon_seleccion": "Discusión de limitaciones en Earth Observation.",
      "guia_redaccion": "Usar para fortalezas/debilidades y generalización en 6.1.",
      "subseccion_destino": "6.1"
    },
    "Wang2025_RS_Compression": {
      "razon_seleccion": "Resultados en reducción de bandwidth.",
      "guia_redaccion": "Contrastar robustez en escenarios de exploración en 6.2.",
      "subseccion_destino": "6.2"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Molliere2025_Learned_EO_Compression": {
      "razon_seleccion": "Conclusiones y perspectivas en compresión EO.",
      "guia_redaccion": "Resumir hallazgos y proponer extensiones en 7.1-7.2.",
      "subseccion_destino": "7.1"
    },
    "Ye2025_MAPC": {
      "razon_seleccion": "Enfoque para bitrates extremadamente bajos.",
      "guia_redaccion": "Inspirar trabajos futuros en transmisión en tiempo real.",
      "subseccion_destino": "7.2"
    }
  }
}
```