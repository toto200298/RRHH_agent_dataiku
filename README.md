# RRHH Agent de Selección y Matching de Candidatos

## Descripción General
Este proyecto desarrollado en **Dataiku** implementa un flujo automatizado para integrar y analizar datos de **Recursos Humanos**.  
El objetivo principal es **optimizar el proceso de selección de candidatos**, cruzando información de múltiples fuentes como ofertas laborales, base de empleados, criterios de aceptación y resultados previos de selección.

El corazón de la solución es un **Visual Agent** que actúa como motor central para consolidar, transformar y aplicar reglas de negocio, generando un proceso más **eficiente, escalable y gobernado**.

---

## Arquitectura del Flujo
El proyecto conecta diferentes datasets y pipelines que se integran en el Visual Agent:

1. **Criterios de aceptación**  
   - Define las reglas y condiciones necesarias para la evaluación de candidatos.  

2. **Visual Agent Results**  
   - Consolida y expone los resultados del análisis y matching.  

3. **RRHH posiciones**  
   - Información proveniente de procesos previos y requerimientos de talento.  

4. **Base de empleados**  
   - Contiene el histórico y características de empleados actuales (útil para benchmarks internos).  

5. **Ofertas laborales**  
   - Lista de vacantes abiertas y requerimientos de cada posición.  

6. **Candidatos**  
   - Perfiles, CVs procesados y atributos relevantes para el matching.

Estos componentes se integran en el **nodo central “Visual Agent”**, que ejecuta la lógica de matching y produce resultados listos para análisis o consumo por parte de equipos de RRHH.

---

## Impacto en el Proceso
- **Automatización:** reducción significativa del tiempo dedicado a la revisión manual de candidatos.  
- **Eficiencia:** integración de múltiples fuentes en un flujo único y reproducible.  
- **Gobernanza:** todos los pasos del proceso son trazables dentro de Dataiku, asegurando calidad y transparencia.  
- **Escalabilidad:** permite añadir nuevas fuentes de datos o reglas de negocio sin modificar el diseño principal.  
- **Valor Estratégico:** habilita decisiones de contratación más objetivas y basadas en evidencia.

---

## Requisitos
- **Plataforma:** Dataiku DSS vX.X o superior  
- **Permisos:** acceso a datasets de RRHH y módulos de preparación/automatización  
- **Conexiones:** almacenamiento en carpeta local o servidor para importar candidatos y ofertas  

---

## Ejecución
1. Importar el proyecto en Dataiku.  
2. Configurar las conexiones de datasets (empleados, candidatos, ofertas, criterios).  
3. Ejecutar cada flujo individual hasta llegar al **Visual Agent**.  
4. Generar resultados y validar los KPIs de selección.  

---

## Capturas de Pantalla
![Flujo en Dataiku](auditoria_agil.png)  
_Estructura visual del proyecto en Dataiku DSS._

---

## Créditos
Desarrollado por **Alfonso Cervantes Barragán**  
Líder en Ciencia de Datos | Keyrus Colombia  

---
