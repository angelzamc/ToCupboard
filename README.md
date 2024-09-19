# Evaluación de Riesgos - Open API de ToCupboard

## Descripción

Este repositorio contiene toda la documentación, código y resultados de la **Evaluación de Riesgos** y la **Mitigación de Hallazgos** realizados en el Open API de ToCupboard. Durante esta fase, hemos implementado prácticas de **DevSecOps** para garantizar la seguridad del Open API y de la pasarela de pagos, cumpliendo con los estándares de seguridad PCI-DSS y protegiendo los datos de los usuarios.

## Estructura del Repositorio

- **/docs**: Contiene la documentación de la evaluación de riesgos y los hallazgos.
  - `README.md`: Descripción general del repositorio.
  - `INFORME_DE_RIESGOS.md`: Documento con los hallazgos detallados y las recomendaciones.
  
- **/src**: Código fuente y scripts de pruebas.
  - **/api**: Código del Open API que fue evaluado.
  - **/test_pipelines**: Scripts de pruebas automatizadas para validar la seguridad del Open API.
  
- **/security**: Reporte de vulnerabilidades y plan de mitigación.
  - `vulnerabilidades_reportadas.json`: Vulnerabilidades identificadas durante la evaluación.
  - `mitigacion_riesgos.yaml`: Plan de mitigación para las vulnerabilidades detectadas.

- **/ci_cd**: Archivos de configuración de CI/CD para la automatización de las pruebas de seguridad.

## Requisitos

- **Node.js** (versión X.X o superior)
- **Python** (versión X.X para las pruebas automatizadas)
- Herramientas de CI/CD: **Jenkins** o **GitLab CI**

1. **Clona el repositorio:**
## Ejecución de Pruebas de Seguridad

2. Para ejecutar las pruebas de seguridad, navega a la carpeta `/src/test_pipelines` y ejecuta:






   ```bash
   git clone https://github.com/ToCupboard/Evaluacion-Riesgos-OpenAPI-ToCupboard.git
   cd Evaluacion-Riesgos-OpenAPI-ToCupboard
