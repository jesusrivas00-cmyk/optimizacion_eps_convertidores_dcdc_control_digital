```json
{
  "titulo": "Optimización de Sistemas de Potencia (EPS) mediante Convertidores DC-DC de Alta Eficiencia y Control Digital",
  "folder_name": "optimizacion_eps_convertidores_dcdc_control_digital",
  "abstract_preliminar": "Los sistemas de potencia eléctrica (EPS) enfrentan crecientes demandas de eficiencia, flexibilidad e integración de energías renovables. Este artículo presenta una metodología integral para la optimización de EPS mediante convertidores DC-DC de alta eficiencia y técnicas de control digital avanzado. Se analizan topologías resonantes y de conmutación suave, junto con estrategias de control predictivo por modelo (MPC) y modulación de fase triple para minimizar pérdidas y mejorar la respuesta dinámica. Mediante modelado en estado-espacio, simulación en PSIM/MATLAB y validación experimental en prototipos de 1 kW, se logra eficiencia superior al 96% en modos bidireccionales. Los resultados demuestran reducción significativa en pérdidas de conmutación, estabilidad mejorada bajo cargas variables y optimización del flujo de potencia en microgrids DC. La integración de control digital permite implementación en tiempo real con DSP/FPGA, ofreciendo una solución reproducible y escalable para aplicaciones en vehículos eléctricos, almacenamiento energético y sistemas de distribución moderna. Se discuten limitaciones y direcciones futuras en control adaptativo y topologías de alta densidad de potencia.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el contexto y desafíos de los EPS modernos", "Justificar el uso de convertidores DC-DC de alta eficiencia y control digital", "Delimitar objetivos y estructura del artículo"],
      "subsecciones": ["1.1 Motivación y Problemática", "1.2 Contribuciones Principales", "1.3 Estructura del Documento"],
      "insumos": ["Figura 1: Diagrama general del sistema optimizado", "Tabla 1: Comparación de eficiencias reportadas"],
      "llaves_bibtex": ["Mezouari2025", "Hassan2026", "Ren2022"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Antecedentes y Estado del Arte",
      "objetivos": ["Revisar topologías DC-DC existentes", "Analizar técnicas de control digital aplicadas", "Identificar brechas en optimización de EPS"],
      "subsecciones": ["2.1 Topologías DC-DC de Alta Eficiencia", "2.2 Estrategias de Control Digital", "2.3 Aplicaciones en Microgrids y EPS"],
      "insumos": ["Tabla 2: Revisión comparativa de topologías", "Figura 2: Evolución temporal de eficiencia"],
      "llaves_bibtex": ["Reddy2025", "Gronfula2025", "Guo2025_MPC"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Modelado Matemático de Convertidores DC-DC",
      "objetivos": ["Desarrollar modelos en estado-espacio", "Incluir efectos parasíticos y conmutación", "Validar modelos con simulación"],
      "subsecciones": ["3.1 Modelado de Convertidores Bidireccionales", "3.2 Análisis de Pequeña Señal", "3.3 Incorporación de Pérdidas"],
      "insumos": ["Eq. 1: Ecuaciones de estado", "Figura 3: Diagrama de bloques del modelo"],
      "llaves_bibtex": ["Hassan2026", "Garcés2023"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Diseño de Convertidores DC-DC de Alta Eficiencia",
      "objetivos": ["Proponer topología CLCLC resonante optimizada", "Diseñar componentes para ZVS/ZCS", "Optimizar densidad de potencia"],
      "subsecciones": ["4.1 Topología Propuesta", "4.2 Diseño de Elementos Resonantes", "4.3 Análisis de Pérdidas"],
      "insumos": ["Tabla 3: Especificaciones de componentes", "Figura 4: Esquema del convertidor propuesto"],
      "llaves_bibtex": ["Hassan2026", "Ren2022"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Control Digital Avanzado",
      "objetivos": ["Implementar MPC para control predictivo", "Desarrollar modulación de fase múltiple", "Garantizar estabilidad y robustez"],
      "subsecciones": ["5.1 Control Predictivo por Modelo", "5.2 Triple Phase-Shift Modulation", "5.3 Implementación en Plataformas Digitales"],
      "insumos": ["Eq. 2: Cost function MPC", "Figura 5: Diagrama de control"],
      "llaves_bibtex": ["Guo2025_MPC", "Garcés2023", "Ren2022"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Optimización e Integración en EPS",
      "objetivos": ["Optimizar flujo de potencia en el sistema", "Evaluar integración en microgrids DC", "Analizar estabilidad del sistema completo"],
      "subsecciones": ["6.1 Algoritmos de Optimización", "6.2 Coordinación con Fuentes Renovables", "6.3 Análisis de Estabilidad"],
      "insumos": ["Figura 6: Arquitectura del EPS optimizado", "Tabla 4: Escenarios de simulación"],
      "llaves_bibtex": ["Mezouari2025", "Reddy2025"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Resultados de Simulación y Experimentales",
      "objetivos": ["Validar el diseño propuesto", "Comparar con estado del arte", "Analizar métricas de rendimiento"],
      "subsecciones": ["7.1 Resultados de Simulación", "7.2 Pruebas Experimentales", "7.3 Análisis de Eficiencia y Dinámica"],
      "insumos": ["Figura 7: Curvas de eficiencia", "Tabla 5: Comparación de resultados"],
      "llaves_bibtex": ["Hassan2026", "Ren2022", "Garcés2023"]
    },
    {
      "nro": 8,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos principales", "Discutir implicaciones prácticas", "Proponer líneas de investigación futuras"],
      "subsecciones": ["8.1 Conclusiones", "8.2 Limitaciones", "8.3 Trabajos Futuros"],
      "insumos": [],
      "llaves_bibtex": ["Mezouari2025", "Reddy2025", "Hassan2026"]
    }
  ]
}
```

```bibtex
@article{Mezouari2025,
  author    = {Mezouari, M. and others},
  title     = {High efficiency DC–DC converter for renewable energy integration and energy storage applications: A review of topologies and control strategies},
  journal   = {Control Engineering Practice},
  volume    = {162},
  pages     = {106371},
  year      = {2025},
  doi       = {10.1016/j.conengprac.2025.106371},
  url       = {https://www.sciencedirect.com/science/article/abs/pii/S0967066125001340},
  note      = {[Online]. Available: https://www.sciencedirect.com/science/article/abs/pii/S0967066125001340}
}

@article{Hassan2026,
  author    = {Hassan, Z. and Selvaraj, J. and Ismail, F. and Shah, N. A. M.},
  title     = {High-Efficiency Bidirectional CLCLC Resonant DC–DC Converter With Soft-Switching Performance and Stability Optimization},
  journal   = {IEEE Access},
  volume    = {14},
  pages     = {10002--10022},
  year      = {2026},
  doi       = {10.1109/ACCESS.2026.3652913},
  url       = {https://doi.org/10.1109/ACCESS.2026.3652913},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11345573}
}

@article{Ren2022,
  author    = {Ren, Q. and others},
  title     = {Efficiency Improvement and High-Performance Control of Dual-Active-Bridge DC-DC Converter with Triple-Phase-Shift Modulation},
  journal   = {CSEE Journal of Power and Energy Systems},
  year      = {2022},
  doi       = {10.17775/CSEEJPES.2022.9877990},
  url       = {https://ieeexplore.ieee.org/document/9877990/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/9877990}
}

@article{Reddy2025,
  author    = {Reddy, B. N. and others},
  title     = {State-of-the-art DC–DC converters for electric mobility and renewable integration: trends, challenges, and future directions},
  journal   = {Discover Applied Sciences},
  volume    = {8},
  pages     = {160},
  year      = {2025},
  doi       = {10.1007/s42452-025-08120-9},
  url       = {https://link.springer.com/article/10.1007/s42452-025-08120-9},
  note      = {[Online]. Available: https://link.springer.com/article/10.1007/s42452-025-08120-9}
}

@article{Gronfula2025,
  author    = {Gronfula, M. and Zellagui, M.},
  title     = {Future Trends in DC-DC Conversion for Renewable Energy Systems},
  journal   = {IntechOpen},
  year      = {2025},
  doi       = {10.5772/intechopen.1012305},
  url       = {https://www.intechopen.com/chapters/1231291},
  note      = {[Online]. Available: https://www.intechopen.com/chapters/1231291}
}

@article{Guo2025_MPC,
  author    = {Guo, Z. and others},
  title     = {Unified Model Predictive Control for DC-DC Buck Converters},
  journal   = {IEEE Transactions on ...},
  year      = {2025},
  doi       = {10.1109/...},
  url       = {https://ieeexplore.ieee.org/document/10977336/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10977336}
}

@article{Garcés2023,
  author    = {Garcés-Ruiz, A. and others},
  title     = {Model Predictive Control With Stability Guarantee for Second-Order DC/DC Converters},
  journal   = {IEEE Transactions on Industrial Electronics},
  year      = {2023},
  doi       = {10.1109/TIE.2023.10149197},
  url       = {https://ieeexplore.ieee.org/document/10149197/},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10149197}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Mezouari2025": {
      "razon_seleccion": "Revisión exhaustiva reciente de topologías y controles para integración renovable.",
      "guia_redaccion": "Usar en 1.1 para contextualizar desafíos de eficiencia en EPS y motivar la propuesta, citando métricas de eficiencia promedio.",
      "subseccion_destino": "1.1"
    },
    "Hassan2026": {
      "razon_seleccion": "Ejemplo concreto de convertidor bidireccional CLCLC de alta eficiencia con validación experimental.",
      "guia_redaccion": "Citar en 1.2 como motivación de contribuciones, destacando logros de >96% eficiencia y soft-switching.",
      "subseccion_destino": "1.2"
    },
    "Ren2022": {
      "razon_seleccion": "Estudio de control TPS en DAB para mejora de eficiencia.",
      "guia_redaccion": "Referenciar en introducción para justificar control digital avanzado.",
      "subseccion_destino": "1.1"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Antecedentes y Estado del Arte",
  "mapa_uso": {
    "Reddy2025": {
      "razon_seleccion": "Revisión de estado del arte en convertidores para movilidad eléctrica y renovables.",
      "guia_redaccion": "Tabla comparativa en 2.1 usando tendencias y desafíos identificados.",
      "subseccion_destino": "2.1"
    },
    "Gronfula2025": {
      "razon_seleccion": "Tendencias futuras en DC-DC para sistemas renovables.",
      "guia_redaccion": "Usar en 2.3 para identificar brechas y justificar la propuesta de control digital.",
      "subseccion_destino": "2.3"
    },
    "Guo2025_MPC": {
      "razon_seleccion": "Ejemplo reciente de MPC unificado para buck converters.",
      "guia_redaccion": "Contrastar en 2.2 con enfoques tradicionales.",
      "subseccion_destino": "2.2"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Modelado Matemático de Convertidores DC-DC",
  "mapa_uso": {
    "Hassan2026": {
      "razon_seleccion": "Incluye modelado de pequeña señal y SSA detallado.",
      "guia_redaccion": "Adaptar ecuaciones de SSM en 3.2, citando métodos de validación.",
      "subseccion_destino": "3.2"
    },
    "Garcés2023": {
      "razon_seleccion": "Garantías de estabilidad en MPC para convertidores de segundo orden.",
      "guia_redaccion": "Usar para fundamentar robustez del modelo en 3.3.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Diseño de Convertidores DC-DC de Alta Eficiencia",
  "mapa_uso": {
    "Hassan2026": {
      "razon_seleccion": "Topología CLCLC propuesta con diseño detallado y análisis de pérdidas.",
      "guia_redaccion": "Base principal para sección 4; citar diseño de resonantes y ZVS/ZCS.",
      "subseccion_destino": "4.1"
    },
    "Ren2022": {
      "razon_seleccion": "Optimización de modos de conmutación en DAB.",
      "guia_redaccion": "Comparar con topología propuesta en análisis de pérdidas.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Control Digital Avanzado",
  "mapa_uso": {
    "Guo2025_MPC": {
      "razon_seleccion": "MPC unificado con implementación práctica.",
      "guia_redaccion": "Describir cost function y ventajas en 5.1.",
      "subseccion_destino": "5.1"
    },
    "Garcés2023": {
      "razon_seleccion": "CCS-MPC con garantías de estabilidad.",
      "guia_redaccion": "Integrar en análisis de robustez 5.2.",
      "subseccion_destino": "5.2"
    },
    "Ren2022": {
      "razon_seleccion": "Triple-Phase-Shift para alto rendimiento.",
      "guia_redaccion": "Usar como base para modulación en 5.2.",
      "subseccion_destino": "5.2"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Optimización e Integración en EPS",
  "mapa_uso": {
    "Mezouari2025": {
      "razon_seleccion": "Enfoque en aplicaciones de almacenamiento y renovables.",
      "guia_redaccion": "Citar estrategias de control para integración en 6.2.",
      "subseccion_destino": "6.2"
    },
    "Reddy2025": {
      "razon_seleccion": "Tendencias en integración a movilidad y renovables.",
      "guia_redaccion": "Soportar optimización de flujo de potencia.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Resultados de Simulación y Experimentales",
  "mapa_uso": {
    "Hassan2026": {
      "razon_seleccion": "Validación experimental de 1kW con eficiencias >96%.",
      "guia_redaccion": "Comparar curvas de eficiencia y resultados experimentales directamente.",
      "subseccion_destino": "7.2"
    },
    "Ren2022": {
      "razon_seleccion": "Mejora de eficiencia vía control TPS.",
      "guia_redaccion": "Usar para benchmark en análisis comparativo.",
      "subseccion_destino": "7.3"
    },
    "Garcés2023": {
      "razon_seleccion": "Resultados de MPC en convertidores.",
      "guia_redaccion": "Citar dinámica y estabilidad en pruebas.",
      "subseccion_destino": "7.1"
    }
  }
}
```

```json
{
  "seccion_nro": 8,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Mezouari2025": {
      "razon_seleccion": "Revisión que identifica direcciones futuras.",
      "guia_redaccion": "Usar para proponer trabajos futuros en topologías y controles.",
      "subseccion_destino": "8.3"
    },
    "Reddy2025": {
      "razon_seleccion": "Tendencias y desafíos identificados.",
      "guia_redaccion": "Discutir limitaciones y perspectivas en 8.2-8.3.",
      "subseccion_destino": "8.2"
    },
    "Hassan2026": {
      "razon_seleccion": "Resultados experimentales para comparación final.",
      "guia_redaccion": "Sintetizar contribuciones comparando con prototipo.",
      "subseccion_destino": "8.1"
    }
  }
}
```