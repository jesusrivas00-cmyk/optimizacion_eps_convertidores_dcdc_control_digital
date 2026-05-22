**Title**: Optimización de Sistemas de Potencia (EPS) mediante Convertidores DC-DC de Alta Eficiencia y Control Digital

**Description**: Los sistemas de potencia eléctrica (EPS) enfrentan crecientes demandas de eficiencia, flexibilidad e integración de energías renovables. Esta investigación presenta una metodología integral para la optimización de EPS mediante convertidores DC-DC de alta eficiencia y técnicas de control digital avanzado, incluyendo topologías resonantes (CLCLC), control predictivo por modelo (MPC) y modulación de fase triple. Se logra eficiencia superior al 96% en operación bidireccional mediante modelado en estado-espacio, simulación y validación experimental en prototipos de 1 kW, ofreciendo una solución escalable para microgrids DC, vehículos eléctricos y almacenamiento energético.

**General Objective**: Desarrollar y validar una metodología de optimización de sistemas de potencia eléctrica mediante convertidores DC-DC de alta eficiencia y control digital avanzado.

**Specific Objectives**: 
- Analizar el estado del arte de topologías DC-DC y estrategias de control digital aplicadas a EPS.
- Diseñar y modelar convertidores DC-DC bidireccionales resonantes con conmutación suave (ZVS/ZCS).
- Implementar algoritmos de control predictivo por modelo (MPC) y modulación de fase triple en plataformas digitales.
- Optimizar el flujo de potencia y evaluar la integración del convertidor en microgrids DC.
- Validar experimentalmente el sistema propuesto y comparar sus métricas de eficiencia y respuesta dinámica con el estado del arte.

**Justification**: La transición energética global exige mayor eficiencia en la conversión y gestión de potencia para maximizar el aprovechamiento de fuentes renovables variables y reducir pérdidas energéticas. Los convertidores DC-DC de alta eficiencia con control digital mejoran la estabilidad, densidad de potencia y flexibilidad de los EPS, contribuyendo a la descarbonización, la movilidad eléctrica sostenible y la confiabilidad de los sistemas de distribución moderna, con impacto técnico, económico y ambiental significativo.

**Methodology**: Enfoque cuantitativo basado en modelado matemático en estado-espacio, análisis de pequeña señal e incorporación de efectos parasíticos. Se emplea simulación en MATLAB/Simulink y PSIM para verificación, seguido de diseño de prototipo de 1 kW, implementación de control digital en DSP/FPGA y validación experimental bajo diferentes condiciones de carga y operación bidireccional. Se utilizan técnicas de optimización y análisis comparativo con el estado del arte.

**Scope**: Desarrollo, simulación y validación experimental de convertidor DC-DC bidireccional optimizado de 1 kW para integración en microgrids DC (85 caracteres).

**Activities**: 
1. Revisión del estado del arte y definición de requisitos.
2. Modelado matemático y diseño de la topología propuesta.
3. Desarrollo e implementación de estrategias de control digital.
4. Simulación del sistema completo y optimización.
5. Construcción del prototipo y pruebas experimentales.
6. Análisis de resultados, discusión y documentación.

**Resources**: 
- Software: MATLAB/Simulink, PSIM.
- Hardware: Prototipo convertidor DC-DC 1 kW, DSP/FPGA (Texas Instruments o Xilinx), sensores de voltaje/corriente, cargas electrónicas.
- Equipamiento de laboratorio: Osciloscopios, analizadores de potencia y fuentes programables.
- Bases de datos científicas para revisión bibliográfica.

**Limitations**: Dependencia de disponibilidad de componentes especializados y equipamiento de laboratorio de alta precisión; posibles restricciones en escalabilidad inmediata a potencias superiores a 10 kW sin rediseño; sensibilidad a variaciones de parámetros en entornos industriales reales; y limitaciones temporales en la profundidad de pruebas de envejecimiento y confiabilidad a largo plazo.