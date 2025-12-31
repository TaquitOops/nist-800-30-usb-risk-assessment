# Análisis de Incidente: USB Baiting - Hospital Retórico

## Descripción del Proyecto
Este repositorio contiene el análisis de seguridad realizado tras el hallazgo de una unidad USB en el aparcamiento del Hospital Retórico. [cite_start]El objetivo es evaluar los riesgos de un ataque de "cebo USB" (USB baiting) y proponer medidas de mitigación basadas en el estándar **NIST SP 800-30**[cite: 1, 3].

## Escenario
Se encontró una unidad flash con el logotipo del hospital en el suelo del estacionamiento. Para minimizar riesgos, la investigación se realizó en un entorno virtual aislado, evitando la conexión directa a la red del hospital.

## Estructura del Repositorio
1. `01-analisis-contenido.md`: Identificación de la información almacenada.
2. `02-mentalidad-atacante.md`: Evaluación de vectores de ataque y explotación.
3. `03-analisis-riesgos.md`: Clasificación del riesgo y controles según NIST.

## Herramientas Utilizadas
* Software de virtualización para inspección segura.
* [cite_start]Guía NIST SP 800-30 Rev. 1 para la evaluación de riesgos[cite: 1, 5].
